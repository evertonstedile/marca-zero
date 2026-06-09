# Marca Zero — Apresentação Premium

Apresentação web cinematográfica (scrollytelling) da mentoria **Marca Zero / Método RAIZ**, construída como single-file para GitHub Pages. Cada seção ("mundo") veste a identidade nativa da plataforma que apresenta — Shopify, Meta, TikTok Shop, Google, Claude… — dentro da moldura visual da Marca Zero.

## Estrutura

| Caminho | O que é |
|---|---|
| `index.html` | A apresentação — single-file (HTML + CSS + JS inline, fontes via CDN) |
| `assets/` | Logos, vídeo do hero (desktop 16:9 e mobile 9:16, keyframes densos), poster e teaser |

## Stack

- **Zero build step** — um único `index.html`
- **Lenis** para scroll suave no desktop (mobile usa scroll de toque nativo)
- **GSAP ScrollTrigger** para o video-scroll do hero, trilho de progresso e transições entre mundos
- Tipografia **Sora** (títulos) + **Inter** (corpo) via CDN
- `prefers-reduced-motion` neutraliza animações e desliga o motor de scroll

## Identidade

Fundo `#04090A` · creme `#EFEFE5` · verde-raiz `#99AC62` · chartreuse `#C8D890` · verde profundo `#67843C`. A barra **"/"** é o device de transição entre mundos; a **raiz** é a barra de progresso do scroll.

## Deploy

GitHub Pages servindo a raiz do repositório na branch `main`.
