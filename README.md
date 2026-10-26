# WMS TASK BOT — Tarefa Mais Antiga

Tutorial estático do WMS para publicar no GitHub Pages. As imagens incluídas mostram instalação do Tampermonkey, liberação de scripts de usuário e o painel WMS em Sub Picking.

## Publicar
1. Crie o repositório `tarefa-mais-antiga-guia` no GitHub.
2. Envie o conteúdo da pasta (inclusive `imagens/`) para a branch `main`.
3. Em **Settings → Pages**, selecione **Deploy from a branch → main → /(root)** e salve.
4. O site ficará em `https://SEU-USUARIO.github.io/tarefa-mais-antiga-guia/`.

## Vincular script funcional
Este pacote contém o guia, **não** o bot funcional. Envie o seu código final como `tarefa-mais-antiga.user.js`. Depois, edite no final do `index.html` a constante `SCRIPT_URL` com a URL de instalação do userscript no GitHub Pages. Não utilize scripts desconhecidos.

**Observação:** os gráficos de instalação são orientativos. A interface do Chrome/Tampermonkey pode mudar.
