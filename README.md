# Site de Casamento — Thales & Beatriz 💍

Site estático (HTML/CSS/JS puro) pronto para hospedar no **GitHub Pages**.

## Estrutura

```
site/
├── index.html      # todo o site (estilo, conteúdo e scripts)
└── img/
    ├── logo.jpeg   # monograma dos noivos
    ├── qrcode.jpeg # QR Code Pix
    └── foto1.jpg ... foto8.jpg
```

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `casamento`).
2. No terminal, dentro da pasta `site/`:

   ```bash
   git init
   git add .
   git commit -m "Site de casamento Thales & Beatriz"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/casamento.git
   git push -u origin main
   ```

3. No GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
4. Em ~1 minuto o site estará em `https://SEU_USUARIO.github.io/casamento/`.

## Personalizações rápidas (em `index.html`)

- **Cores**: variáveis CSS no topo do `<style>` (`--navy`, `--terracotta`, etc.).
- **Valores dos presentes**: no `<script>`, o laço `for(let valor = 100; valor <= 800; valor += 50)`.
- **Nomes/ícones dos presentes**: array `nomes` no `<script>`.
- **Texto do versículo**: no `<footer>`.
