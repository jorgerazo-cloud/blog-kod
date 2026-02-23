---
title: "Claude Code Oculta Qué Archivos Edita: Desarrolladores Protestan Contra Anthropic"
description: "La nueva versión de Claude Code esconde los nombres de archivos que lee y edita. La comunidad de desarrolladores critica la falta de transparencia."
pubDate: 2026-02-23
heroImage: "/images/posts/2026-02-23-claude-code-oculta.png"
category: "Desarrollo"
tags: ["Anthropic", "Claude Code", "Coding", "Transparencia", "Desarrolladores"]
author: "KÖD Agency"
---

## Anthropic Oculta las Acciones de Claude Code

Anthropic actualizó Claude Code, su herramienta de coding con IA, y los desarrolladores **no están contentos**. El cambio principal: ahora la herramienta **oculta los nombres de archivos** que está leyendo, escribiendo o editando.

## El Cambio Controversial

En la versión 2.1.20, en lugar de mostrar qué archivos específicos está tocando Claude, ahora solo aparece:

> "Read 3 files (ctrl+o to expand)"

Los detalles completos siguen disponibles con un atajo de teclado, pero según los desarrolladores, esto es **impráctico y peligroso**.

## Por Qué Los Desarrolladores Están Molestos

### 🔒 Seguridad
Necesitan ver qué archivos accede Claude para detectar comportamiento sospechoso.

### 🎯 Contexto Correcto
Si Claude está leyendo archivos incorrectos, quieren saberlo **inmediatamente** para corregir el rumbo.

### 💰 Costo de Tokens
Ver qué hace Claude permite **interrumpir a tiempo** y evitar gastar tokens en direcciones equivocadas.

### 📜 Auditoría
El historial de conversación servía para revisar qué archivos se tocaron, ahora eso se perdió.

## La Respuesta de Anthropic

Boris Cherny, creador de Claude Code, defendió el cambio:

> "Esto no es una feature de 'vibe coding', es una forma de simplificar la UI para que puedas enfocarte en lo que importa: diffs y outputs de bash/mcp."

Sugirió usar el modo verbose, pero la respuesta de la comunidad fue clara: **"Verbose mode tiene demasiado ruido."**

## El Verdadero Problema

Un desarrollador lo resumió perfectamente:

> "Si tu mejor idea para simplificar es 'Read 3 files', no estás simplificando — estás **removiendo información valiosa** de forma idiota."

## Lo Que Esto Significa Para Ti

Si usas Claude Code, esto es lo que debes saber:

1. **El nuevo default oculta información** - Acostúmbrate a usar Ctrl+O frecuentemente
2. **Verbose mode fue modificado** - Ya no muestra todo lo que antes
3. **Anthropic escucha pero no revierte** - Hicieron ajustes, pero el comportamiento por defecto sigue

## La Lección Para la Industria

Cuando las herramientas de IA ocultan lo que hacen, **los errores pasan desapercibidos**. Como dijo otro desarrollador:

> "Claude no puede ser confiado para hacer las cosas bien sin supervisión constante. Si no puedo seguir su razonamiento, la sesión solo quema mi cuota de tokens."

---

**¿Necesitas implementar herramientas de IA de forma transparente en tu flujo de trabajo?** En KÖD ayudamos a empresas a integrar IA sin perder control. [Contáctanos](https://wearekod.com).
