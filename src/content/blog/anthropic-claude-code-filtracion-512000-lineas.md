---
title: "Anthropic Filtra 512,000 Líneas de Código de Claude Code: Lo Que Revelan los Archivos"
description: "Un error en npm expuso el código fuente completo de Claude Code, revelando funciones ocultas, modo 'undercover' y herramientas internas."
pubDate: 2026-04-01
author: "KÖD"
heroImage: "/images/posts/claude-code-leak-anthropic-2026.webp"
tags: ["Anthropic", "Claude", "Seguridad", "Código Fuente", "Filtración"]
category: "Seguridad"
featured: true
---

# La Filtración que Expuso los Secretos de Claude Code

**Anthropic, la empresa que se posiciona como la más segura en IA, acaba de cometer un error épico.** Un release de Claude Code en npm incluyó un archivo que apuntaba a un ZIP en el cloud storage de Anthropic — con el **código fuente completo**: 1,900 archivos TypeScript y más de 512,000 líneas de código.

## ¿Qué contenía la filtración?

El investigador Chaofan Shou fue el primero en descubrirlo. El archivo incluye:

- **Comandos slash completos** — Todas las funciones disponibles
- **Herramientas internas** — Capacidades no documentadas públicamente
- **Nombres de modelos futuros** — Referencias a versiones no lanzadas
- **Modo "undercover"** — Un modo que oculta rastros de Anthropic en repos externos
- **Regexes de frustración** — Patrones para detectar cuando el usuario está molesto

## El modo "undercover" es particularmente revelador

Según el análisis del código, `undercover.ts` (unas 90 líneas) implementa un modo que **elimina todas las referencias a Anthropic** cuando Claude Code se usa en repositorios no internos. Básicamente, Claude puede trabajar "de incógnito".

## La respuesta de Anthropic

La empresa confirmó la filtración a VentureBeat:

> "Un release de Claude Code incluyó código fuente interno. **No se expusieron datos de clientes ni credenciales**. Esto se ha corregido y estamos revisando nuestros procesos."

## ¿Por qué importa?

1. **Credibilidad en seguridad** — Anthropic se vende como la empresa más responsable en IA. Esta es la segunda filtración en un año.
2. **Competidores con acceso** — Cualquiera con acceso a npm pudo descargar el código antes de que lo retiraran
3. **Destilación de modelos** — El código revela cómo funciona internamente Claude Code, facilitando copiar su comportamiento

## La ironía

Mientras Anthropic [acusa a labs chinos](/blog/anthropic-acusa-labs-chinos-robar-ia) de robar su IP a través de destilación, ellos mismos publicaron el manual de instrucciones completo por error.

---

*La seguridad en IA no es solo sobre el modelo — es sobre toda la cadena. En KÖD auditamos implementaciones de IA para empresas. [Contáctanos](https://wearekod.com).*
