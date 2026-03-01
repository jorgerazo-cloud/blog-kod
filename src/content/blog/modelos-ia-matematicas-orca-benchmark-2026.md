---
title: "Los Modelos de IA Mejoran en Matemáticas — Pero Todavía Reprobarían"
description: "El benchmark ORCA 2026 muestra progreso: Gemini 3 Flash alcanza 72.8% de precisión. Pero los LLMs siguen siendo 'motores de predicción, no de lógica'."
pubDate: 2026-03-01
heroImage: "/images/posts/2026-03-01-ia-matematicas-orca.png"
category: "tecnología"
tags: ["LLMs", "matemáticas", "benchmark", "Gemini", "ChatGPT", "DeepSeek", "Grok", "ORCA"]
author: "KÖD"
---

# Los Modelos de IA Mejoran en Matemáticas — Pero Todavía Reprobarían

Los LLMs actuales son motores de predicción, no de lógica. Solo pueden encontrar la solución **más probable**, que no necesariamente es la **correcta**. Aunque los modelos populares han mejorado, incluso el mejor performer recibiría una **C** si fuera evaluado con calificaciones escolares.

## Los resultados del benchmark ORCA 2026

Investigadores de Omni Calculator sometieron a los principales modelos de IA a su benchmark ORCA, que consiste en **500 problemas matemáticos prácticos**.

### Resultados actuales vs anteriores

| Modelo | Precisión actual | Cambio |
|--------|-----------------|--------|
| **Gemini 3.1 Flash** | 72.8% | +9.8 pts |
| **DeepSeek V3.2** | 55.2% | +3.2 pts |
| **ChatGPT 5.2** | 54.0% | +4.6 pts |
| **Grok 4.1** | 60.2% | -2.6 pts |

**Gemini lidera**, pero con 72.8% apenas pasaría un examen. ChatGPT y DeepSeek reprobarían con poco más del 50%.

## El problema fundamental

> "Una calculadora es predecible. Pregúntale lo mismo hoy o el próximo año, y la respuesta será la misma. La IA no funciona así."
> — Dawid Siuda, investigador de ORCA

### Por qué los LLMs fallan en matemáticas

Los modelos predicen **el siguiente número o palabra más probable** basándose en patrones que han visto antes. Es como un estudiante que memoriza todas las respuestas de un libro de matemáticas pero nunca aprende a sumar.

- **Funcionan** en problemas que han visto antes
- **Fallan** en problemas únicos o con múltiples pasos
- **Son inconsistentes** — pueden dar respuestas diferentes a la misma pregunta

## El factor de inestabilidad

Los investigadores midieron qué tan frecuentemente los modelos cambiaron sus respuestas cuando se les preguntó lo mismo dos veces:

| Modelo | Inestabilidad (% cambios en errores) |
|--------|-------------------------------------|
| Gemini 3 Flash | 46.1% |
| ChatGPT | 65.2% |
| DeepSeek V3.2 | 68.8% |

**Gemini es el más consistente**, pero aún así cambia su respuesta casi la mitad de las veces cuando se equivoca.

## Dónde mejoraron (y dónde no)

### Mejoras notables
- **DeepSeek en Biología y Química:** de 10.5% a 43.9%
- **Gemini en Conversiones Matemáticas:** alcanzó 93.2%

### Retrocesos
- **Grok en Salud y Deportes:** perdió 9 puntos
- **Grok en Biología y Química:** perdió 5.3 puntos

Los investigadores especulan que las actualizaciones de Grok priorizaron otras capacidades sobre el razonamiento cuantitativo.

## Lo que los números ocultan

Un hallazgo preocupante: **los errores de cálculo ahora representan el 39.8%** de todos los errores (antes 33.4%), mientras que los errores de redondeo bajaron.

**Traducción:** Los modelos son mejores haciendo que las matemáticas **se vean bien** (formateo correcto), pero siguen luchando con la **aritmética real**.

## ¿Hay solución?

### Function calling (llamadas a funciones)
La solución más prometedora: hacer que la IA delegue los cálculos a fuentes determinísticas.

> "Las grandes empresas como Google y OpenAI ya hacen esto — la IA llama a una función para hacer el cálculo real. El dolor de cabeza es con problemas largos donde la IA tiene que rastrear cada pequeño resultado."

### Verificación con pruebas formales
Google DeepMind desarrolló un enfoque que obtuvo medalla de plata en la Olimpiada Matemática Internacional usando aprendizaje por refuerzo basado en pruebas formales con el lenguaje Lean.

## Para profesionales en México

Si usas IA para trabajo que involucra números:

1. **Nunca confíes ciegamente** — Verifica siempre los cálculos críticos
2. **Usa herramientas especializadas** — Excel, calculadoras, no ChatGPT
3. **Documenta la verificación** — Si un cliente pregunta, demuestra que validaste
4. **Considera function calling** — Si desarrollas, integra APIs de cálculo

---

*Los LLMs son increíbles para texto, código y creatividad. Para matemáticas, son estudiantes que memorizaron las respuestas pero nunca aprendieron el proceso. Usa calculadoras para calcular.*
