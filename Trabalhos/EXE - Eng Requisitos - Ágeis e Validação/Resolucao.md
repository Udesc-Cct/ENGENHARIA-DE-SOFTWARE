# EXE - Eng Requisitos - Ágeis e Validação
### 1. Quais são as três partes de uma história de usuário? Responda usando o acrônimo 3C's.
```
As três partes de uma história de usuário são conhecimento (conhecimento sobre o usuário,
 suas necessidades e objetivos), contexto (contexto em que o usuário está inserido, como
ambiente, plataforma, dispositivos) e critérios de aceitação (critérios específicos que
devem ser atendidos para que a história seja considerada concluída). Essas três partes
são representadas pelo acrônimo 3C's.
```
### 2.Suponha uma rede social como o Facebook. Escreva um conjunto de cinco histórias para essa rede, assumindo o papel de um usuário típico. Em seguida, pense em mais um papel de usuário e escreva pelo menos duas histórias para ele.
```
Histórias de usuário para um usuário típico:

1. Quero poder criar um perfil na rede social, adicionando informações pessoais como nome, foto e localização.
2. Quero poder adicionar amigos à minha lista de contatos para interagir e compartilhar conteúdo com eles.
3. Quero poder publicar fotos e vídeos no meu perfil para compartilhar momentos importantes da minha vida.
4. Quero poder curtir e comentar as publicações dos meus amigos para expressar minha opinião e interagir com eles.
5. Quero receber notificações de novas atividades dos meus amigos, como comentários em minhas publicações ou convites para eventos, para estar sempre atualizado e participar das interações.

Histórias de usuário para um papel adicional de usuário (ex: administrador da rede social):

1. Quero poder moderar e remover conteúdo inapropriado ou ofensivo para manter um ambiente seguro e agradável para os usuários.
2. Quero poder analisar e monitorar o engajamento dos usuários, como número de curtidas e compartilhamentos, para entender o sucesso das funcionalidades e melhorar a experiência do usuário
```
### 3. O seguinte caso de uso possui apenas o fluxo normal. Escreva algumas extensões para ele referente a fluxos alternativos.
Comprar Livro
Ator: Usuário da loja virtual
Fluxo normal:
1. Usuário pesquisa catálogo de livros
2. Usuário seleciona livros e coloca no carrinho de compra
3. Usuário decide fechar a compra
4. Usuário seleciona endereço de entrega
5. Usuário seleciona tipo de entrega
6. Usuário seleciona modo de pagamento
7. Usuário confirma pedido
   
```
Extensões para o caso de uso "Comprar Livro":

Fluxo alternativo: Usuário decide voltar para o catálogo de livros
1. No passo 3 do fluxo normal, o usuário decide voltar para o catálogo de livros.
2. O sistema retorna o usuário ao catálogo de livros para continuar pesquisando.

Fluxo alternativo: Usuário decide remover livro do carrinho
1. No passo 2 do fluxo normal, o usuário decide remover um livro do carrinho.
2. O sistema remove o livro selecionado do carrinho e atualiza o valor total da compra.

Fluxo alternativo: Usuário decide adicionar cupom de desconto
1. No passo 6 do fluxo normal, o usuário decide adicionar um cupom de desconto.
2. O sistema permite que o usuário insira o código do cupom.
3. O sistema valida o cupom e aplica o desconto ao valor total da compra.

Essas extensões permitem que o usuário tenha mais opções durante o processo de compra, como voltar para o catálogo de livros, remover itens do carrinho e aplicar cupons de desconto. Isso proporciona uma experiência mais flexível e personalizada para o usuário.
```
