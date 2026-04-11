---
title: "Anthropic lanza Claude Mythos Preview: el modelo de IA 'demasiado peligroso para el público'"
description: "Claude Mythos Preview encuentra vulnerabilidades zero-day de 27 años. Anthropic lo considera demasiado peligroso para liberarlo públicamente y creó Project Glasswing con 40+ empresas tech para usarlo solo en defensa."
pubDate: 2026-04-11
author: "KODU Data"
tags: ["anthropic", "claude mythos", "ciberseguridad", "project glasswing", "zero-day"]
heroImage: "/images/posts/anthropic-mythos-peligroso.jpg"
---

**Anthropic acaba de anunciar Claude Mythos Preview** — y es tan poderoso en ciberseguridad que la empresa decidió **NO liberarlo al público**.

En su lugar, creó **Project Glasswing**: una coalición de 40+ empresas tech (Apple, Microsoft, Google, Amazon, Cisco, Linux Foundation) que usarán Mythos **solo para defensa**.

Esto es histórico. Y aterrador.

## El modelo que rompe todo

**Nombre:** Claude Mythos Preview  
**Especialidad:** Ciberseguridad ofensiva/defensiva  
**Nivel de acceso:** Restringido (solo coalición Glasswing)  
**Razón:** "Riesgos de ciberseguridad sin precedentes"

### ¿Qué puede hacer Mythos?

Según Anthropic, Claude Mythos:
- Encuentra **vulnerabilidades zero-day** en código legacy
- Identifica bugs de **27 años de antigüedad** (ej: ffmpeg, OpenBSD)
- Automatiza **exploit development** 80-90%
- Supera equipos de red team humanos en velocidad y cobertura

**Un ejemplo real:**  
Mythos encontró una vulnerabilidad crítica en OpenBSD que existía desde **1999** y que los mejores investigadores de seguridad del mundo nunca detectaron.

## Project Glasswing: la coalición defensiva

Anthropic entendió que liberar Mythos públicamente sería **irresponsable**. En su lugar, creó Project Glasswing:

**Miembros fundadores (40+):**
- **Tech giants:** Apple, Microsoft, Google, Amazon
- **Ciberseguridad:** Cisco, Palo Alto Networks, CrowdStrike
- **Open source:** Linux Foundation, Apache Foundation
- **Gobierno:** Contratos clasificados con CISA

**Objetivo:**  
Usar Mythos para **encontrar y parchear vulnerabilidades ANTES de que atacantes las exploten**.

### Cómo funciona Glasswing:

1. **Miembros pagan** por acceso API a Mythos
2. **Anthropic comprometió $100M** en créditos API para organizaciones sin fines de lucro
3. **Auditoría continua:** Anthropic monitorea TODOS los usos de Mythos
4. **Veto power:** Anthropic puede revocar acceso a cualquier miembro que abuse

## ¿Por qué es "demasiado peligroso"?

Anthropic publicó un paper técnico explicando los riesgos. Los highlights:

### Automatización de exploits
Un investigador de seguridad tarda **días o semanas** en desarrollar un exploit funcional. Mythos lo hace en **minutos**.

### Escalabilidad de ataques
Un atacante con Mythos podría:
- Escanear MILLONES de repos de GitHub buscando bugs
- Encontrar zero-days en software crítico (OpenSSL, Linux kernel, etc.)
- Automatizar campañas de ransomware imposibles de rastrear

### Democratización del hacking
Antes, solo hackers elite podían encontrar zero-days. Con Mythos, **cualquiera con acceso podría hacerlo**.

Anthropic decidió que ese riesgo es inaceptable.

## La reacción de la industria

**Apoyo mayoritario:**
- Apple, Google, Microsoft **elogiaron** la decisión de Anthropic
- Investigadores de seguridad dijeron que es "la decisión correcta"
- El Pentágono (sí, después del drama) dijo que Glasswing es "modelo a seguir"

**Críticas:**
- **Investigadores independientes:** "Esto consolida poder en manos de Big Tech"
- **Comunidad open source:** "Viola el principio de transparencia en seguridad"
- **Academia:** "Retrasa investigación legítima"

## El elefante en la sala: el Pentágono

Esto pasa **SEMANAS** después de que el Pentágono catalogara a Anthropic como "supply chain risk" y la sacara de contratos militares.

**Ironía máxima:**  
El gobierno que tildó a Anthropic de "riesgosa" ahora tiene que reconocer que Glasswing es exactamente lo que debería existir para seguridad nacional.

**Fuentes internas** (NYT, The Guardian) dicen que:
- El Pentágono está negociando re-entrada a Glasswing
- La Casa Blanca presionó para levantar el ban
- Anthropic puso condiciones: "Solo defensa, nunca ofensiva"

## Comparación con competidores

| Empresa | Modelo Ciberseguridad | Acceso Público |
|---------|----------------------|----------------|
| Anthropic | Claude Mythos | ❌ Solo Glasswing |
| OpenAI | Codex Security | ✅ Research Preview |
| Google | Gemini Security | ✅ Disponible en Vertex AI |
| Microsoft | Copilot Security | ✅ Enterprise tier |

**Anthropic es la ÚNICA que restringe acceso por razones de seguridad.**

## ¿Qué viene después?

Anthropic prometió:
- **Transparencia trimestral** sobre uso de Mythos
- **Auditorías externas** de organizaciones de ética en IA
- **Eventual liberación** si se desarrollan suficientes defensas

Pero por ahora, Mythos es **el modelo más poderoso que el público nunca usará**.

## Implicaciones para la industria

Esto sienta un **precedente masivo**:

1. **Los modelos más poderosos NO serán públicos** — fin de la era "libera todo gratis"
2. **Coaliciones privadas** (como Glasswing) manejarán IA crítica
3. **Transparencia ≠ acceso público** — puedes saber que existe sin poder usarlo
4. **Ética > Marketing** — Anthropic sacrificó revenue por hacer lo correcto

## Conclusión

Claude Mythos Preview es la respuesta a la pregunta: **"¿Qué pasa cuando la IA se vuelve tan poderosa que liberarla es irresponsable?"**

Anthropic dijo: **"No la liberamos. Creamos una coalición defensiva y la controlamos estrictamente."**

Es el momento en que la industria reconoció que **algunos modelos son demasiado peligrosos para democratizar**.

Y probablemente, no será el último.

**Fuentes:**  
- [NYT](https://www.nytimes.com/2026/04/07/technology/anthropic-claims-its-new-ai-model-mythos-is-a-cybersecurity-reckoning.html)  
- [The Guardian](https://www.theguardian.com/technology/2026/apr/10/anthropic-new-ai-model-claude-mythos-implications)  
- [Anthropic Blog](https://www.anthropic.com/)
