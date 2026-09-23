# CISSP Flashcards — Felipe Nicácio

Interface de estudo com 1.071 cartões originais, organizados pelos oito domínios do CISSP. Clique no cartão para revelar a resposta; filtre por domínio, embaralhe e marque cartões dominados ou pendentes.

## Executar

Abra `index.html` em um navegador. Os dados estão em `cards.js`; a aplicação não requer servidor nem dependências externas.

## Publicação no GitHub

O login com Google citado por Felipe é a forma de entrar na conta do GitHub; não é um mecanismo de autenticação desta aplicação. Use um repositório **privado** para guardar o código e os 1.071 cartões. Para manter os cartões privados na internet, publique os arquivos por um serviço que aplique autenticação no servidor antes de entregar `index.html` e `cards.js`, como Cloudflare Pages protegido pelo Cloudflare Access. Configure a política de acesso para a conta autorizada e valide que uma sessão anônima não consegue obter nenhum dos dois arquivos.

O GitHub Pages, por si só, entrega arquivos estáticos e não restringe o acesso aos cartões. Uma tela de login implementada somente em JavaScript também não protege `cards.js`. Não ative GitHub Pages neste repositório enquanto os cartões precisarem permanecer privados.

## Dados e progresso

Os cartões são uma cópia da base de estudo do Notion em 23 de setembro de 2026. Alterações no Notion não são sincronizadas automaticamente; substitua `cards.js` ao publicar uma revisão. O estado “Já sei” é salvo somente no `localStorage` do navegador, sem sincronização entre dispositivos ou com o Notion.

## Conteúdo

Perguntas e respostas são conteúdo de estudo elaborado para este projeto; não reproduzem os textos dos cartões da Wiley. Revise o conteúdo editorial antes de redistribuí-lo.
