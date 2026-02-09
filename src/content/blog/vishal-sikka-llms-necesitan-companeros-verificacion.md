---
title: 'Pionero de IA advierte: "Nunca confíes en un LLM que corre solo"'
description: 'Vishal Sikka, alumno de John McCarthy (quien acuñó el término "inteligencia artificial"), explica por qué los LLMs necesitan sistemas compañeros que verifiquen su trabajo.'
pubDate: 'Feb 09 2026'
heroImage: '/images/posts/sikka-llm-companeros.webp'
category: 'IA'
tags: ['LLM', 'Vishal Sikka', 'alucinaciones', 'verificación', 'confiabilidad', 'inteligencia artificial']
---

## La noticia

Vishal Sikka, CEO de Vianai Systems y figura legendaria en IA, advierte: los LLMs **no deben correr solos**. Necesitan "bots compañeros" que verifiquen su trabajo para ser confiables.

Sikka no es cualquier voz: su asesor en Stanford fue **John McCarthy**, el hombre que acuñó el término "inteligencia artificial" en 1955.

## El problema fundamental

Según Sikka, hay un error conceptual en cómo pensamos sobre LLMs:

> "Esperar que un modelo entrenado con cierta cantidad de datos pueda hacer un número arbitrariamente grande de cálculos confiables es una suposición incorrecta."

En otras palabras: **los LLMs tienen límites computacionales**. Cuando los empujas más allá, alucinan.

![Cerebro digital con señales de sobrecarga y advertencia](/images/posts/llm-limites-computacionales.webp)

## La evidencia

Sikka y su hijo publicaron un paper: *"Hallucination Stations: On Some Basic Limitations of Transformer-Based Language Models"*.

El hallazgo clave:
- Dos prompts con **tokens idénticos** generan el **mismo número de operaciones**
- No importa si pides un cálculo complejo o un texto simple
- El modelo hace las mismas operaciones internamente

Cuando la tarea excede esa capacidad → alucinación.

## Por qué importa para agentes

Sikka es directo sobre los agentes de IA:

> "Cuando decimos 'reserva un boleto, carga mi tarjeta, deduce de mi banco, publica en mi app financiera' — estás pidiendo acciones con semántica específica para ti. Si es un LLM puro debajo, tiene capacidad limitada para ejecutar estas tareas. Con uso agéntico de LLMs puros, debes tener **extrema precaución**."

![Agente de IA intentando ejecutar múltiples tareas con señales de error](/images/posts/agente-ia-sobrecarga.webp)

## La solución: Sistemas compañeros

La clave está en **rodear al LLM con sistemas de verificación**:

1. **El LLM genera** — Usa su poder computacional para crear candidatos
2. **El compañero verifica** — Un sistema "no imaginativo" valida la salida
3. **Se itera** — El ciclo se repite hasta lograr confiabilidad

Es como lo hace **AlphaFold** de Google:
- Evoformer (LLM) genera candidatos de proteínas
- Sistema verificador confirma que son proteínas válidas
- Resultado: 250,000 proteínas descubiertas que antes tomaban años

## Aplicación real: Hila de Vianai

El producto de Sikka, Hila, usa este enfoque:

> "Combinamos el LLM con un modelo de conocimiento para un dominio particular. Después de eso, Hila no comete errores."

Ejemplo: Reducir reportes financieros de **20 días de trabajo humano a 5 minutos**.

![Dashboard de Hila mostrando verificación de reportes financieros](/images/posts/hila-verificacion-financiera.webp)

## La perspectiva histórica

Sikka ha visto **cuatro ciclos de hype de IA** en su carrera:

1. **Años 80** — Hardware custom, aplicaciones prometidas, empresas como "Thinking Machines"
2. **Años 90** — Sistemas expertos
3. **Años 2010** — Deep learning
4. **Ahora** — LLMs y agentes

En cada ciclo: promesas grandes, realidad limitada, ajuste de expectativas.

## El dato duro

Sikka cita el estudio de MIT: **95% de los proyectos de IA fracasan**.

> "Con productos cuidadosamente elegidos, hay retorno dramático de inversión. Pero uso general de LLMs requiere mucho cuidado."

## La analogía perfecta

Sikka compara el uso actual de IA con los **primeros noticieros de TV**:

> "Los presentadores leían las noticias al aire, igual que en radio. Aún no habíamos descubierto qué hacía único a la TV."

Estamos haciendo lo mismo con IA: usándola para replicar lo que ya hacíamos.

![TV antigua con presentador leyendo noticias, transicionando a TV moderna con gráficos](/images/posts/tv-radio-evolucion.webp)

## El takeaway

No confíes ciegamente en un LLM corriendo solo. La confiabilidad viene de **sistemas compuestos**: LLMs para generar + verificadores para validar.

Si vas a automatizar algo crítico con IA, necesitas el "amigo" que revise el trabajo.

---

*¿Quieres más noticias de IA que importan? Síguenos en [@wearekod](https://instagram.com/wearekod)*
