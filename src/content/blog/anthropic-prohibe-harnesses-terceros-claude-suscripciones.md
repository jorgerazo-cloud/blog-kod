---
title: "Anthropic Prohíbe Usar Claude con Herramientas de Terceros: OpenCode Ya Removió Soporte"
description: "Anthropic clarifica que las suscripciones de Claude solo pueden usarse con herramientas oficiales. OpenCode ya eliminó el soporte por 'solicitudes legales'."
pubDate: 2026-02-23
heroImage: "/images/posts/2026-02-23-anthropic-harnesses.png"
category: "Negocios"
tags: ["Anthropic", "Claude", "OpenCode", "API", "Suscripciones", "Legal"]
author: "KÖD Agency"
---

## Anthropic Cierra la Puerta a Herramientas de Terceros

Anthropic acaba de actualizar sus términos legales para dejar **cristalino** un mensaje: si tienes una suscripción de Claude (Free, Pro, o Max), **solo puedes usarla con Claude.ai o Claude Code**.

Usar tu suscripción en herramientas como OpenCode, Cursor, o Pi está **prohibido**.

## El Problema del Arbitraje de Tokens

Las suscripciones de Claude ofrecen tokens a un precio subsidiado. Esto creó una oportunidad de arbitraje:

1. Pagas $20/mes por Claude Pro
2. Usas esos tokens en una herramienta de terceros
3. Obtienes más valor del que deberías por tu precio

**Anthropic lo llama "violación de términos". Los usuarios lo llamaban "hack inteligente".**

## La Nueva Regla Explícita

El nuevo lenguaje legal dice:

> "Usar tokens OAuth obtenidos a través de cuentas Claude Free, Pro o Max en cualquier otro producto, herramienta o servicio — **incluyendo el Agent SDK** — no está permitido y constituye una violación de los Términos de Servicio."

## OpenCode Ya Se Alineó

El jueves pasado, OpenCode [publicó código](https://github.com/anomalyco/opencode/commit/973715f3da1839ef2eba62d4140fe7441d539411) eliminando soporte para:

- Claves de cuenta Claude Pro y Max
- Claves API de Claude

El mensaje del commit: **"anthropic legal requests"**.

## La Respuesta de la Competencia

Interesantemente, OpenAI aprovechó el momento. Thibault Sottiaux de OpenAI [tuiteó](https://x.com/thsottiaux/status/2009742187484065881?s=20) **apoyando explícitamente** el uso de suscripciones de Codex en harnesses de terceros.

**Traducción**: "Hola desarrolladores frustrados con Anthropic, vengan con nosotros."

## Por Qué Esto Importa

### Para Desarrolladores:
- Menos flexibilidad con Claude
- Necesitan evaluar si el valor de Claude justifica la restricción
- Posible migración a Codex/OpenAI

### Para el Ecosistema:
- Los "frontier models" quieren controlar toda la experiencia
- Las herramientas intermediarias (harnesses) están en riesgo
- La guerra de plataformas se intensifica

## La Perspectiva de Anthropic

El ingeniero Thariq Shihipar explicó la posición de la empresa:

> "Los harnesses de terceros usando suscripciones de Claude crean problemas para los usuarios y están prohibidos por nuestros Términos. Generan patrones de tráfico inusuales sin la telemetría que Claude Code proporciona, haciendo muy difícil ayudar a debuggear cuando tienen preguntas."

## Qué Hacer Si Te Afecta

1. **Evalúa tu uso actual**: ¿Dependes de herramientas no oficiales?
2. **Considera API keys**: Son más caras pero sin restricciones
3. **Explora alternativas**: OpenAI parece más permisivo... por ahora
4. **No arriesgues tu cuenta**: Anthropic está baneando activamente

---

**¿Necesitas asesoría sobre qué stack de IA usar para tu empresa?** En KÖD evaluamos opciones y costos para que tomes la mejor decisión. [Contáctanos](https://wearekod.com).
