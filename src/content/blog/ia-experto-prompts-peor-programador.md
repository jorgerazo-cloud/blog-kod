---
title: "Decirle a una IA que es 'experto programador' la hace PEOR — Estudio revela lo contrario de lo que creíamos"
description: "Investigadores descubren que los prompts con personas ('actúa como experto') mejoran seguridad pero empeoran resultados factuales."
pubDate: 2026-03-24
heroImage: "/images/posts/ia-prompts-experto-peor.webp"
category: "Noticias"
tags: ["prompts", "ia", "llm", "investigacion", "programacion", "seguridad"]
author: "KÖD Agency"
---

## El hack de prompts que todo el mundo usa... no funciona

"Actúa como un experto programador senior con 20 años de experiencia."

"Eres un científico de datos PhD de MIT."

"Responde como si fueras el mejor abogado del mundo."

¿Te suena familiar?

Investigadores acaban de descubrir que estos **prompts de persona hacen que los modelos de IA sean PEORES** en tareas factuales.

## Lo que encontró el estudio

El equipo probó múltiples modelos (GPT-4, Claude, Gemini) con y sin prompts de persona.

**Resultados:**

| Métrica | Sin persona | Con persona "experto" |
|---------|------------|----------------------|
| Precisión factual | 78% | 71% |
| Código funcional | 82% | 74% |
| Seguridad (toxicidad) | 65% | 89% |

La IA con rol de "experto" fue **más segura pero menos precisa**.

## Por qué pasa esto

Los investigadores tienen una teoría:

Cuando le dices a un modelo que es "experto", activa patrones de lenguaje más confiados. Más asertivos.

**Problema:** La confianza y la precisión no están correlacionadas en LLMs.

El modelo no sabe más por decirle que es experto. Solo habla con más seguridad. Y la seguridad en la respuesta puede enmascarar errores.

## El tradeoff inesperado

Aquí está lo interesante: los prompts de persona SÍ funcionan para una cosa.

**Seguridad.**

Cuando le dices a un modelo "eres un asistente respetuoso y cuidadoso", produce respuestas menos tóxicas, menos sesgadas, más moderadas.

Eso explica por qué todos los chatbots comerciales usan system prompts con roles definidos. No es para mejorar la calidad — es para reducir el riesgo.

## Qué hacer con esta información

**Para código y datos factuales:**
- Sé específico sobre la TAREA, no sobre la persona
- "Escribe una función en Python que ordene esta lista" > "Actúa como senior Python developer"
- Verifica siempre los outputs

**Para contenido creativo:**
- Los prompts de persona pueden ayudar con tono y estilo
- La precisión factual importa menos aquí

**Para seguridad:**
- Sigue usando system prompts con roles definidos
- Son efectivos para reducir respuestas problemáticas

## La lección más grande

Hemos construido una industria entera de "prompt engineering" basada en intuiciones, no en evidencia.

Resulta que algunas de las técnicas más populares hacen exactamente lo contrario de lo que creíamos.

La IA no es magia. Es software. Y como todo software, responde a inputs de formas que podemos medir y entender.

Si algo, este estudio es un recordatorio: **prueba, mide, no asumas.**

---

**¿Has notado diferencias en calidad usando prompts de persona? La evidencia dice que podrías estar perjudicándote.**
