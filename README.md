# Dashboard Materiais — versão leve para GitHub Pages

Esta versão separa o dashboard em arquivos menores para publicar no GitHub Pages.

## Estrutura

- `index.html` — página principal
- `style.css` — estilos
- `app.js` — regras, filtros, upload e renderização
- `data.js` — dados compactados em arrays, gerado a partir do HTML original

## Como publicar no GitHub

1. Crie um repositório no GitHub.
2. Envie estes arquivos para a raiz do repositório.
3. Vá em **Settings > Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/root`.
6. Salve e aguarde o link do GitHub Pages.

## Observação

Para Excel (`.xlsx/.xls`), o upload usa SheetJS via CDN. Para funcionar offline, prefira CSV.
