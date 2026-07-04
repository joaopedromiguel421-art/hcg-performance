# HCG Performance Equina

Site institucional da **HCG Performance Equina** — M.V. Helena Cafasso Galli.
Fisioterapia, reabilitação, quiropraxia e acupuntura equina. São Paulo.

> _Excelência em movimento._

## Sobre

Landing page estática (um único `index.html`, sem dependências e sem build).
Basta abrir o `index.html` no navegador ou publicar em qualquer hospedagem estática.

## Estrutura

- `index.html` — a página completa (HTML + CSS + JS inline, JSON-LD no head)
- `logo-860.webp` / `logo-860.png` — logotipo do hero (WebP + fallback), LCP da página
- `logo-transparente.png` — arquivo-fonte do logotipo sem fundo
- `logo.png` — logotipo original (fundo verde), usado em OG/schema/favicons
- `helena.webp` / `helena.jpg` — foto da seção "Sobre" (WebP + fallback)
- `favicon.png` / `apple-touch-icon.png` — ícones
- `fonts/` — Cormorant Garamond e Jost (woff2 latin, self-hosted)
- `llms.txt` — resumo estruturado para agentes de IA (GEO)
- `robots.txt` / `sitemap.xml` — indexação (crawlers de IA liberados)
- `vercel.json` — cache imutável de assets + headers de segurança

## Publicação (Vercel)

Projeto estático — o Vercel detecta automaticamente. Sem configuração necessária.

## Contato

- Instagram: [@hcg.performance](https://www.instagram.com/hcg.performance/)
- Agendamentos: via WhatsApp
