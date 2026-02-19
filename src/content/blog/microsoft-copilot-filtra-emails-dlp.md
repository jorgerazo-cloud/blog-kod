---
title: "Microsoft Copilot Filtra Emails Confidenciales: La Falla de DLP que Preocupa a Empresas"
description: "Copilot puede leer y resumir correos que no debería tocar, exponiendo información sensible. Microsoft enfrenta críticas por fallas en Data Loss Prevention."
pubDate: 2026-02-19
heroImage: "/images/posts/2026-02-19-copilot-filtra-emails-dlp.png"
category: "seguridad"
tags: ["Microsoft", "Copilot", "seguridad", "DLP", "privacidad", "empresas"]
author: "KÖD"
---

# Copilot está leyendo emails que no debería

Un nuevo reporte de The Register revela que **Microsoft Copilot** está resumiendo correos electrónicos marcados como confidenciales, ignorando las políticas de **Data Loss Prevention (DLP)** configuradas por las empresas.

## El problema explicado

Las empresas configuran DLP para proteger información sensible. Por ejemplo:
- Documentos marcados como "Confidencial" no deberían copiarse fuera de la organización
- Emails con datos financieros tienen restricciones de acceso
- Información de clientes no debe aparecer en resúmenes automáticos

**Copilot está ignorando estas reglas.** La IA resume contenido que debería estar protegido, exponiendo información a usuarios que no deberían verla.

## Ejemplos de riesgo

| Escenario | Riesgo |
|-----------|--------|
| Email de HR sobre despidos | Copilot lo incluye en resumen a toda la empresa |
| Información de salario en correo privado | Aparece en "highlights" del día |
| Negociaciones confidenciales con cliente | Copilot las menciona a otros empleados |

## La respuesta de Microsoft

Microsoft dice estar trabajando en:

1. **Mejorar la integración con políticas DLP existentes**
2. **Etiquetas de sensibilidad más granulares**
3. **Controles de administrador más estrictos**

Pero mientras tanto, las empresas están expuestas.

## ¿Qué deben hacer las empresas?

Si tu organización usa Copilot, considera:

- **Auditar qué acceso tiene Copilot** a correos y documentos
- **Revisar políticas de DLP** y asegurar que estén actualizadas
- **Capacitar a empleados** sobre qué información no poner por escrito
- **Monitorear resúmenes de Copilot** para detectar filtraciones

## El problema más grande: IA y privacidad corporativa

Este incidente es síntoma de un problema sistémico:

> Las herramientas de IA empresarial se están desplegando más rápido de lo que se pueden asegurar.

Copilot no es el único. Cualquier IA con acceso a datos internos puede potencialmente filtrar información si no está correctamente configurada.

## Para México: Implicaciones legales

Con la **Ley Federal de Protección de Datos Personales**, las empresas mexicanas que usen Copilot podrían enfrentar:

- Multas si datos personales se filtran por fallas de la herramienta
- Obligación de notificar a usuarios afectados
- Auditorías del INAI

---

*La IA empresarial es poderosa, pero también peligrosa si no se configura correctamente. Antes de activar Copilot en tu organización, asegúrate de que tu equipo de seguridad haya revisado todas las implicaciones.*
