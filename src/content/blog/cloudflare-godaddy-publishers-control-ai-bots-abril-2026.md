---
title: 'Cloudflare y GoDaddy se unen para dar a publishers el control que Big Tech les quitó (y que ahora la IA amenaza con destruir)'
description: 'GoDaddy integra herramientas de Cloudflare para que publishers puedan bloquear, permitir o cobrar a bots de IA. OpenAI, Anthropic y Google entran en la mira.'
pubDate: 2026-04-10
author: 'KODU Data'
image: '/images/posts/cloudflare-godaddy-ai-crawl-control-abril-2026.webp'
tags: ['Cloudflare', 'GoDaddy', 'AI Crawlers', 'Publishers', 'OpenAI', 'Google']
---

GoDaddy, el registrador de dominios más grande del mundo, acaba de integrarse con **Cloudflare** para dar a millones de publishers algo que Big Tech les arrebató hace años: **control sobre quién usa su contenido**.

Y esta vez, el enemigo no es Google Search — son los **bots de IA** de OpenAI, Anthropic, Google, Meta y compañía.

## El problema: los bots de IA no devuelven tráfico

Durante años, publishers toleraron a Google porque había un trato implícito:

✅ Google crawlea tu contenido  
✅ Google te envía tráfico de vuelta  
✅ Tú monetizas con anuncios  

Pero los bots de IA **rompieron ese trato**.

Ahora:
- ❌ Anthropic, OpenAI, Google scrapers entrenan modelos con tu contenido  
- ❌ Los usuarios obtienen respuestas directamente del chatbot  
- ❌ Nunca visitan tu sitio  
- ❌ No ves un centavo  

## La solución de Cloudflare: AI Crawl Control

Cloudflare, que maneja el tráfico del **20% de la web**, lanzó **AI Crawl Control** — una herramienta que permite a publishers:

1. **Bloquear bots** completamente  
2. **Permitir solo ciertos bots** (por ejemplo, OpenAI sí, Anthropic no)  
3. **Cobrar** a las empresas de IA por acceso  

Y ahora, **GoDaddy lo integró directamente** en su panel de control.

## Por qué GoDaddy + Cloudflare es una combinación letal

**GoDaddy:**
- Más de 20 millones de clientes  
- Millones de pequeñas empresas y publishers  
- El registrador de dominios #1 del mundo  

**Cloudflare:**
- Maneja tráfico del 20% de la web  
- Infraestructura de seguridad y performance  
- Ya tiene relaciones con OpenAI, Anthropic, Google  

Juntos, representan **una fracción masiva de la web abierta**.

## El argumento de Cloudflare contra Google

Cloudflare publicó recientemente un documento explosivo dirigido a reguladores del Reino Unido:

**Problema:** Googlebot es **un solo bot** que sirve para:
- Indexar para Google Search  
- Entrenar modelos de Google (Gemini)  
- Probablemente otras cosas que Google no revela  

**Consecuencia:** Si bloqueas Googlebot para protegerte de IA, **también te desapareces de Google Search**.

**Solución propuesta:** Obligar a Google a **separar Googlebot** en crawlers distintos para cada propósito.

## Qué pueden hacer los publishers ahora

Con la integración de GoDaddy:

**Opción 1: Bloquear todo**
```
User-agent: GPTBot
Disallow: /

User-agent: Claude-Web
Disallow: /
```

**Opción 2: Permitir solo búsqueda, bloquear entrenamiento**
```
User-agent: Googlebot
Allow: /

User-agent: Google-Extended
Disallow: /
```

**Opción 3: Cobrar**
- Cloudflare puede configurar un sistema de pago por acceso
- Las empresas de IA negocian directamente contigo

## El futuro: ¿Data licensing obligatorio?

Cloudflare y GoDaddy están apostando a que la regulación eventualmente obligará a las empresas de IA a:

1. **Identificarse claramente** (bots separados por propósito)  
2. **Respetar robots.txt**  
3. **Pagar por contenido premium**  

Pero por ahora, la batalla es voluntaria.

## Lo que está en juego

Para pequeños publishers y creadores de contenido:
- ❌ Sin tráfico de búsqueda tradicional (Google Search está muriendo)  
- ❌ Sin tráfico de chatbots (los usuarios nunca salen del chat)  
- ❌ Sin compensación por entrenamiento de modelos  

GoDaddy + Cloudflare es la primera línea de defensa real que tienen.

---

**Fuentes:** Cloudflare Blog, Business Insider, GoDaddy, The Verge
