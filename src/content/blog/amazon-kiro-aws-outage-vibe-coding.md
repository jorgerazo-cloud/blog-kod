---
title: "Amazon Kiro Tumba AWS: Cuando el Vibe Coding Se Sale de Control"
description: "La herramienta de vibe coding de Amazon habría causado dos caídas de AWS esta semana. Amazon culpa a 'controles de acceso mal configurados', pero la historia es más compleja."
pubDate: 2026-02-21
heroImage: "/images/posts/2026-02-21-amazon-kiro-aws-outage.png"
category: "tecnología"
tags: ["AWS", "Amazon", "Kiro", "vibe coding", "outage", "IA", "agentes"]
author: "KÖD"
---

# El Vibe Coding de Amazon Tumba AWS

Esta semana, **dos caídas menores de AWS** habrían sido causadas por las acciones de herramientas de IA de Amazon, según reportes de The Register.

El protagonista: **Kiro**, la herramienta de "vibe coding" de Amazon que permite a los desarrolladores describir en lenguaje natural lo que quieren y deja que la IA escriba el código.

## ¿Qué pasó?

Amazon afirma que las caídas fueron causadas por "error de usuario, específicamente controles de acceso mal configurados". Pero la realidad es más interesante.

Los sistemas de IA agentic como Kiro tienen la capacidad de:
- Escribir código
- Ejecutar comandos
- Modificar configuraciones
- Desplegar cambios

Cuando algo sale mal, **el daño puede escalar rápidamente**.

## La ironía del vibe coding

El "vibe coding" se llama así porque el desarrollador describe la "vibra" de lo que quiere, y la IA interpreta e implementa.

Funciona así:
1. "Quiero que los usuarios puedan subir fotos"
2. La IA escribe todo el código
3. Despliega automáticamente
4. 🙏 Esperemos que funcione

El problema: **la IA no siempre entiende las implicaciones de seguridad** de lo que está haciendo.

## Lo que dice Amazon

> "Los incidentes fueron causados por errores de usuario, específicamente controles de acceso mal configurados."

Traducción: "El humano que supervisaba la IA no revisó bien lo que la IA estaba haciendo."

## La lección para empresas

| Riesgo | Mitigación |
|--------|------------|
| IA modifica configuraciones críticas | Revisión humana obligatoria para cambios de infra |
| Código generado sin pruebas | Pipelines de CI/CD con tests automatizados |
| Despliegues automáticos | Aprobación manual en producción |
| Escalamiento de errores | Monitoreo y rollback automático |

## Para México y LATAM

Si tu empresa usa AWS y está experimentando con herramientas de IA para desarrollo:

1. **No dar permisos de producción a herramientas de IA** — Sandbox primero
2. **Revisar todo código generado** — La IA acelera, no reemplaza
3. **Implementar guardrails** — Límites claros de lo que la IA puede tocar
4. **Tener rollback listo** — Siempre poder revertir

## El panorama más amplio

Este incidente es parte de una tendencia creciente: **los agentes de IA están ganando más autonomía**, pero los sistemas de seguridad no evolucionan al mismo ritmo.

MIT CSAIL acaba de publicar su AI Agent Index 2025 que muestra que la mayoría de los agentes de IA operan sin reglas claras ni divulgación de sus capacidades.

---

*El vibe coding es poderoso, pero con gran poder viene gran responsabilidad. Y aparentemente, caídas de AWS.*
