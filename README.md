# Nutrichele

Painel de cozinha para organizar o plano alimentar da semana: rotação de refeições, receitas, lista de compras com custo estimado, sorteio de combinações e livro de receitas.

Aplicativo estático (HTML/CSS/JS puro, sem backend). Todos os dados — rotação da semana, preços, receitas criadas, listas de mercado — ficam salvos **só no navegador de cada pessoa que usa** (armazenamento local do navegador). Nada é enviado a nenhum servidor.

## Usar

Acesse a página publicada (link do GitHub Pages, ver abaixo) em qualquer navegador — celular, tablet ou computador. Não precisa instalar nada.

## Publicar sua própria cópia (GitHub Pages)

1. Crie um repositório novo no GitHub (pode ser público).
2. Suba o arquivo `index.html` (e este `README.md`, opcional) pra raiz do repositório — dá pra arrastar e soltar direto na interface web do GitHub, sem precisar de terminal.
3. Vá em **Settings → Pages**.
4. Em "Build and deployment", escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`. Salve.
5. Em alguns minutos o GitHub mostra o link público, algo como:
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`
6. Esse link pode ser compartilhado com qualquer pessoa — cada uma que abrir terá seus próprios dados salvos localmente, sem interferir nos dados de outra pessoa.

## Atualizar depois de mudanças

Sempre que uma nova versão do `index.html` for gerada, é só substituir o arquivo no repositório (upload de novo ou `git push`) — o GitHub Pages atualiza a página publicada automaticamente em 1–2 minutos.

## Aviso

Este painel não substitui orientação nutricional individualizada. As estimativas marcadas em âmbar (quantidades sem peso definido no plano original, ou custos calculados a partir de preços digitados pelo usuário) são aproximações, não valores oficiais.
