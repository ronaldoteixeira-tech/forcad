# Forca Dedetizadora - LP Cupim

Landing page estatica para descupinizacao em Natal/RN.

## Estrutura

```text
cupim/
  index.html
  assets/
    brand/
    gallery/
    icons/
    images/
  _headers
  vercel.json
  package.json
```

## Rodar localmente

Abra `index.html` direto no navegador ou rode:

```bash
python -m http.server 4173
```

Depois acesse `http://localhost:4173`.

## Deploy

### Vercel

1. Suba esta pasta como raiz do repositorio, ou configure `cupim` como Root Directory.
2. Framework preset: `Other`.
3. Build command: deixe vazio.
4. Output directory: deixe vazio ou `.`.

### Cloudflare Pages

1. Configure `cupim` como diretorio raiz do projeto.
2. Build command: deixe vazio.
3. Build output directory: `.`.

## Observacoes

- O site e estatico e nao precisa de build.
- Todos os assets usados pela pagina estao em `assets/`.
- Os CTAs abrem um painel de coleta e so depois enviam a mensagem pelo WhatsApp.
