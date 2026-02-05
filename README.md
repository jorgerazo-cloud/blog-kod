# ⚡ KÖD Blog

Blog de noticias de IA, Tech y Marketing Digital para [@wearekod](https://instagram.com/wearekod).

## 🚀 Quick Start

```bash
# Instalar dependencias (ya hecho)
npm install

# Iniciar servidor de desarrollo
npm run dev

# Construir para producción
npm run build

# Preview del build
npm run preview
```

## 📁 Estructura

```
blog-kod/
├── src/
│   ├── content/
│   │   └── blog/           # ← Artículos en Markdown
│   ├── components/         # Componentes Astro
│   ├── layouts/            # Layouts
│   ├── pages/              # Páginas
│   └── styles/             # CSS global
├── public/                 # Assets estáticos
└── dist/                   # Build de producción
```

## 📝 Crear nuevo artículo

Crea un archivo `.md` en `src/content/blog/`:

```markdown
---
title: 'Título del artículo'
description: 'Descripción corta para SEO'
pubDate: 'Feb 05 2026'
heroImage: '/images/mi-imagen.png'
category: 'IA'
tags: ['tag1', 'tag2']
---

Contenido del artículo en Markdown...
```

### Categorías disponibles
- IA
- Negocios
- Tech
- Marketing

## 🎨 Colores de marca

- Violeta: `#7C6AEF`
- Negro: `#0D0D0D`
- Background secundario: `#1A1A1A`
- Gris texto: `#E5E7EB`
- Gris subtle: `#9CA3AF`

## 🌐 Despliegue

### Opción 1: Vercel (recomendado)
1. Conecta el repo a Vercel
2. Configura el dominio `blog.wearekod.com`

### Opción 2: Netlify
1. Conecta el repo a Netlify
2. Build command: `npm run build`
3. Publish directory: `dist`

### Opción 3: Manual
1. `npm run build`
2. Sube la carpeta `dist/` a tu servidor
3. Configura el subdominio apuntando al servidor

## 📂 Subdominio

Para configurar `blog.wearekod.com`:

1. En tu DNS, agrega un registro CNAME:
   - Nombre: `blog`
   - Valor: tu servidor de hosting (Vercel/Netlify/etc)

2. En el hosting, agrega el dominio personalizado

## 🔄 Flujo de contenido

1. Kodu genera carrusel para Instagram
2. Kodu crea artículo correspondiente en el blog
3. Jorge publica carrusel en Instagram
4. Jorge hace deploy del blog (o se hace automático)

## 📊 SEO incluido

- Meta tags automáticos
- Open Graph tags
- Sitemap XML
- RSS Feed (`/rss.xml`)

---

Hecho con ⚡ por KÖD
