# fermentation-project

## Presentación

La presentación está en `index.qmd` (Quarto + reveal.js). Para generarla:

```bash
quarto render            # genera _site/index.html
quarto preview           # recarga en vivo
```

## Publicar en GitHub Pages

```bash
quarto publish gh-pages
```

Esto genera la presentación y la sube a la rama `gh-pages`. La primera vez,
en GitHub ve a *Settings → Pages* y elige la rama `gh-pages` (carpeta `/ (root)`)
como fuente. La presentación queda en
<https://altamarmx.github.io/fermentation-project/>.
