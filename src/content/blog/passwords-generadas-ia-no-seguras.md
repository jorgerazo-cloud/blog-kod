---
title: "Las Contraseñas Generadas por IA No Son Seguras: Se Crackean en Horas"
description: "Investigadores demuestran que las contraseñas que parecen complejas creadas por ChatGPT y otros LLMs son predecibles y pueden romperse rápidamente."
pubDate: 2026-02-19
heroImage: "/images/posts/2026-02-19-passwords-ia-no-seguras.png"
category: "seguridad"
tags: ["contraseñas", "seguridad", "ChatGPT", "ciberseguridad", "hacking", "LLMs"]
author: "KÖD"
---

# Tus contraseñas de ChatGPT no son tan seguras como crees

¿Le pediste a ChatGPT que te genere una contraseña "fuerte"? Malas noticias: investigadores de seguridad demostraron que esas contraseñas **se pueden crackear en cuestión de horas**.

## El problema: no son realmente aleatorias

Cuando le pides a un LLM que genere una contraseña, produce algo que **parece** aleatorio pero **no lo es**. Los modelos de lenguaje tienen patrones inherentes:

| Lo que parece | Lo que es |
|---------------|-----------|
| `Tr0p!cAl_Sun$et2024` | Patrón predecible: palabra + símbolos + año |
| `xK9#mL2$nP5@` | Distribución de caracteres no uniforme |
| `Blue!Mountain#42` | Combinación de palabras comunes |

Los hackers pueden entrenar modelos para predecir estos patrones.

## Cómo lo demostraron

Los investigadores:

1. Generaron **10,000 contraseñas** usando ChatGPT, Claude y Gemini
2. Analizaron los patrones de generación
3. Crearon un modelo de ataque optimizado
4. **Crackearon el 87% en menos de 24 horas**

El tiempo promedio de crackeo fue de **4.2 horas** para contraseñas de 12 caracteres.

## ¿Por qué pasa esto?

Los LLMs no están diseñados para generar aleatoriedad criptográfica. Su objetivo es:

- Predecir el siguiente token más probable
- Generar texto que "suene" correcto
- Seguir patrones del entrenamiento

Esto es lo **opuesto** de lo que necesita una buena contraseña: verdadera aleatoriedad.

## La solución: generadores criptográficos

Para contraseñas realmente seguras, usa:

- **Gestores de contraseñas** — 1Password, Bitwarden, LastPass
- **Generadores del sistema** — `/dev/urandom` en Linux/Mac
- **Hardware tokens** — YubiKey con generación on-device

Estos usan **generadores de números pseudoaleatorios criptográficamente seguros (CSPRNG)**, no modelos de lenguaje.

## Qué hacer si usaste IA para generar contraseñas

1. **Identifica qué cuentas usaron esas contraseñas**
2. **Cambia por contraseñas de un gestor profesional**
3. **Activa 2FA** donde sea posible (esto mitiga mucho el riesgo)
4. **No reutilices contraseñas** entre servicios

## Para empresas

Si tu equipo usa ChatGPT para generar credenciales:

- **Política clara**: Los LLMs no son para generar secretos
- **Herramientas aprobadas**: Provee gestores de contraseñas corporativos
- **Auditoría**: Revisa si hay contraseñas débiles en sistemas críticos

---

*La IA es increíble para muchas cosas, pero la criptografía no es una de ellas. Para secretos, usa herramientas diseñadas específicamente para eso. Tu seguridad depende de ello.*
