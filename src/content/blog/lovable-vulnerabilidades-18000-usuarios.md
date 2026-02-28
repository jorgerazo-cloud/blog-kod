---
title: "App de Lovable expone datos de 18,000 usuarios por fallas básicas"
description: "Investigador descubre vulnerabilidades críticas en aplicación construida con plataforma de vibe coding. ¿Quién tiene la culpa?"
pubDate: 2026-02-28
heroImage: "/images/posts/lovable-vulnerabilidades.jpg"
category: "seguridad"
tags: ["lovable", "vibe coding", "vulnerabilidades", "seguridad", "desarrollo", "ia"]
author: "KÖD Agency"
---

# El lado oscuro del vibe coding

Una aplicación construida con Lovable — la popular plataforma de desarrollo por IA — acaba de exponer los datos de **18,000 usuarios** debido a vulnerabilidades de seguridad básicas.

## Qué pasó

Un investigador de seguridad descubrió que la aplicación (cuyo nombre no se ha revelado) tenía:

- **Autenticación rota** que permitía acceso a cuentas ajenas
- **Endpoints de API expuestos** sin validación
- **Datos sensibles en localStorage** sin encriptación
- **Inyección SQL** en formularios de búsqueda

Sí, errores básicos que cualquier desarrollador junior debería evitar.

## ¿De quién es la culpa?

### ¿De Lovable?
La plataforma argumenta que genera advertencias de seguridad que los usuarios pueden ignorar. También ofrece configuraciones de seguridad que el creador de la app simplemente no activó.

### ¿Del creador de la app?
El investigador apunta a que la persona que construyó la app claramente no tenía conocimientos de seguridad — y usó Lovable pensando que la IA se encargaría de todo.

### La verdad incómoda
**Ambos tienen responsabilidad**, pero el problema de fondo es más grande: las herramientas de vibe coding democratizan la creación de software, pero también permiten que personas sin conocimientos técnicos lancen aplicaciones inseguras.

## El patrón que estamos viendo

Este no es un caso aislado:

- **Startups que lanzan MVPs** sin revisión de seguridad
- **No-coders que construyen SaaS** sin entender las implicaciones
- **Equipos pequeños** que confían ciegamente en el código de IA

## Qué debería cambiar

### Para las plataformas de IA:
- Hacer que las configuraciones seguras sean **por default**
- Bloquear deploys que tengan vulnerabilidades críticas
- Ofrecer auditorías de seguridad automatizadas

### Para los usuarios:
- **No lanzar a producción** sin revisión de seguridad
- Entender que "funciona" ≠ "es seguro"
- Contratar revisión de seguridad si no tienes expertise interno

## El mensaje

Las herramientas de IA son increíblemente poderosas. Pero el poder sin conocimiento es peligroso.

Si vas a construir software que maneje datos de usuarios, **la seguridad no es opcional** — no importa qué tan fácil sea la plataforma que uses.

---

**¿Construiste tu app con IA y quieres validar que sea segura?** En KÖD ofrecemos auditorías de seguridad para startups. [Escríbenos](https://wearekod.com/contacto).
