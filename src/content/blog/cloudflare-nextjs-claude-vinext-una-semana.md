---
title: "Cloudflare Porta el 94% de Next.js en Una Semana Usando Claude"
description: "Un ingeniero de Cloudflare implementó casi toda la API de Next.js con IA, gastando solo $1,100 en tokens. El proyecto Vinext podría cambiar cómo desarrollamos software."
pubDate: 2026-03-01
heroImage: "/images/posts/2026-03-01-cloudflare-nextjs-claude.png"
category: "desarrollo"
tags: ["Cloudflare", "Next.js", "Claude", "Anthropic", "desarrollo", "Vinext", "Vite", "IA coding"]
author: "KÖD"
---

# Cloudflare Porta el 94% de la API de Next.js en Una Semana con Claude

Un ingeniero de **Cloudflare** acaba de demostrar lo que muchos consideraban imposible: **implementar el 94% de la API de Next.js en solo una semana**, dirigiendo a Claude de Anthropic y gastando aproximadamente **$1,100 en tokens**.

## El problema con Next.js

Según Steve Faulkner, director de ingeniería de Cloudflare, el tooling de Next.js es "enteramente a medida". Si quieres desplegarlo en Cloudflare, Netlify o AWS Lambda, tienes que tomar el output del build y transformarlo para que la plataforma objetivo pueda ejecutarlo.

**El problema real:** Vercel controla el ecosistema. Aunque existen "deployment adapters", estos siguen dependiendo de Turbopack, la herramienta de bundling propietaria de Vercel.

## La solución: Vinext

Cloudflare creó **[Vinext](https://github.com/cloudflare/vinext)**, un proyecto open source que:

- Usa **Vite** en lugar de Turbopack
- Fue escrito casi completamente por IA
- Tiene builds **4.4x más rápidos** que Next.js 16 con Turbopack
- Genera bundles de cliente **56% más pequeños**

## Cómo lo hicieron

El proceso fue sorprendentemente directo:

1. **2 horas de arquitectura** — Faulkner definió el plan con Claude en OpenCode
2. **Implementación pieza por pieza** — La IA escribió cada componente de la API
3. **Tests como guía** — Usaron el test suite existente de Next.js para validar
4. **Corrección humana constante** — "Tuve que corregir el rumbo regularmente"

> "Aunque la IA escribió el código, el elemento humano fue crítico" — Steve Faulkner

## Lo que esto significa para desarrolladores

### El lado bueno
- **Escape del vendor lock-in** — Puedes correr Next.js fuera de Vercel con rendimiento similar o mejor
- **Builds más rápidos** — 4.4x no es un número menor en pipelines de CI/CD
- **Bundles más pequeños** — Mejor Core Web Vitals, mejor SEO

### Las advertencias
- **Ningún humano ha revisado el código** (según el README)
- **Solo funciona en Cloudflare Workers** por ahora
- **Proyecto en desarrollo activo** — No es para producción todavía

## La implicación más grande

Faulkner observó algo profundo: la mayoría de las abstracciones de software existen para ayudar a los humanos a entender código. La IA puede "mantener todo el sistema en contexto" sin esas abstracciones.

**Esto abre la puerta a:**
- Reimplementar APIs populares rápidamente
- Software que ningún humano puede entender
- Una nueva era de desarrollo asistido por IA

## Para equipos en México y LATAM

Si usas Next.js y estás frustrado con los costos de Vercel o la complejidad del deployment:

1. **Mantén Vinext en tu radar** — Aún no está listo para producción, pero es prometedor
2. **Considera Vite** — El tooling moderno de JavaScript está madurando rápido
3. **No temas a Cloudflare Workers** — Los precios son competitivos y el edge computing tiene ventajas reales

---

*El futuro del desarrollo web puede ser código escrito por IA, optimizado por IA, desplegado en el edge. Cloudflare acaba de mostrar que ese futuro está más cerca de lo que pensábamos.*
