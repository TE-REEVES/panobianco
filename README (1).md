# Panobianco Estrada do Alvarenga

Projeto estático pronto para deploy no GitHub Pages.

## Estrutura

```text
panobianco-alvarenga/
├── index.html
├── style.css
└── assets/
    ├── logo-panobianco.svg
    └── academia-bg.png
```

## Deploy no GitHub Pages

1. Envie `index.html`, `style.css` e a pasta `assets` para a raiz do repositório.
2. Vá em **Settings > Pages**.
3. Em **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. Salve.

## Feed Instagram

O feed usa Revukit:

```html
<div data-revukit-instagram="igw_r9zhif1GHrQ9LKr93hRliwsjnMbcJLzl"></div>
<script async src="https://www.revukit.com/widgets/instagram/v1/embed.js"></script>
```

## Observação

O layout foi revisado com breakpoints para desktop, tablet, mobile, telas muito estreitas e landscape.
