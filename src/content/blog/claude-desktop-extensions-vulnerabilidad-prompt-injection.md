---
title: 'Claude Desktop Extensions tiene una falla grave de seguridad'
description: 'Investigadores descubren que las extensiones de Claude para Google Calendar permiten ataques de prompt injection que filtran datos sensibles.'
pubDate: 'Feb 11 2026'
heroImage: '/images/posts/claude-desktop-security-flaw.webp'
category: 'Seguridad'
tags: ['Claude', 'Anthropic', 'seguridad', 'prompt injection', 'Google Calendar', 'extensiones']
---

## La noticia

Las extensiones de Claude Desktop (Claude DXT) tienen una **vulnerabilidad seria**.

Investigadores demostraron que un evento malicioso en Google Calendar puede filtrar tus datos a través de prompt injection.

## El problema técnico

Cuando Claude se conecta a tu Google Calendar, lee los eventos para ayudarte. Pero un atacante puede:

1. Crear un evento con instrucciones maliciosas ocultas
2. Claude lee el evento como contexto
3. Las instrucciones engañan a Claude para filtrar datos

![Diagrama mostrando el flujo de un ataque de prompt injection](/images/posts/claude-prompt-injection-diagram.webp)

## Por qué el sandbox no funciona

Los investigadores fueron directos:

> "El contenedor de Claude DXT queda notablemente corto de lo que se espera de un sandbox."

En otras palabras: la protección que debería aislar a Claude de datos sensibles **no está funcionando bien**.

## Datos en riesgo

Si usas Claude Desktop con extensiones, podrían filtrarse:

- **Correos electrónicos** conectados
- **Eventos de calendario** con información sensible
- **Documentos** enlazados en Drive
- **Mensajes** de apps de chat conectadas

## La respuesta de Anthropic

Anthropic aún no ha emitido un comunicado oficial, pero se espera que:

1. Refuercen el sandbox de DXT
2. Implementen filtros de contenido más estrictos
3. Limiten qué datos puede ver Claude de extensiones externas

## Qué debes hacer

**Si usas Claude Desktop:**

- Revisa qué extensiones tienes activas
- Desconecta servicios con datos sensibles temporalmente
- No aceptes invitaciones de calendario de desconocidos

![Lista de extensiones de Claude con opciones de desactivación](/images/posts/claude-extensions-disable.webp)

## El problema más grande

Esto no es solo un problema de Claude. **Todos los agentes de IA** que se conectan a servicios externos enfrentan el mismo riesgo.

La carrera por hacer agentes más útiles está creando superficies de ataque más grandes.

---

**Fuente:** [The Register](https://www.theregister.com/2026/02/11/claude_desktop_extensions_prompt_injection/)
