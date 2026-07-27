# Força Dedetizadora - Landing Page de Dedetização

Landing page de alta conversão para serviços de dedetização em Natal/RN.

## Funcionalidades

- Design responsivo (mobile-first)
- Painel lateral de WhatsApp com formulário de captura de leads
- Seção de prova social com contadores animados
- Galeria de fotos com scroll automático
- FAQ interativo (accordion)
- Barra de CTA fixa no mobile
- Countdown de urgência

## Estrutura

```
dedetizacao/
├── index.html          # Página principal (auto-contida)
├── assets/
│   ├── logo.png        # Logo principal
│   ├── favicon-32.png  # Favicon 32x32
│   ├── favicon-192.png # Favicon 192x192
│   ├── apple-touch-icon.png
│   ├── gallery/        # Fotos da galeria
│   │   ├── hero.png
│   │   ├── problema.png
│   │   ├── fc2.png
│   │   ├── fc3.png
│   │   └── fc6.png
│   └── clients/        # Logos de clientes
│       ├── sebrae.webp
│       ├── bmg.png
│       └── sicoob.webp
├── .gitignore
└── README.md
```

## Deploy

### Vercel
1. Conecte o repositório no Vercel
2. Deploy automático a cada push

### Cloudflare Pages
1. Conecte o repositório no Cloudflare Pages
2. Build command: nenhum (arquivo estático)
3. Output directory: `/`

## Tecnologias

- HTML5 semântico
- CSS3 (variáveis, Grid, Flexbox, animações)
- JavaScript vanilla (zero dependências)
- Google Fonts (Archivo)
