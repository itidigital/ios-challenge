# Desafio iOS

## Descrição
O objetivo é construir a primeira versão de um *app* onde possamos obter a lista de personagens da Marvel.

### Funcionalidades requeridas

O aplicativo deverá:

- [ ] Apresentar uma lista com todos os personagens disponíveis com a opção de busca por nome;
- [ ] Permitir a navegação para os detalhes de cada personagem;
- [ ] Conter uma seção própria com os personagens favoritos, onde os personagens possam ser marcados tanto na lista quanto nos detalhes;
- [ ] Persistir no dispositivo os personagens favoritos para que possam ser acessados em modo *offline*; 

### Informações importantes

Esse é um MVP do nosso projeto, adicionaremos novas funcionalidades no futuro. Portanto, é importante que as decisões tomadas sobre a organização e arquitetura sejam pensadas no futuro desse aplicativo. ;)

Apesar da pouca complexidade do projeto, não ignore fazer o desenvolvimento utilizando as melhores práticas de engenharia de software, estes critérios serão considerados em na nossa avaliação.

Nos entregue quando estiver orgulhoso do que fez! =)

## API
Para desenvolver o app você vai precisar usar o endpoint de "Characters" da API Marvel. Para mais informações acesse [https://developer.marvel.com/docs](https://developer.marvel.com/docs).

## Interface
A interface do app é dividida em 3 partes e deve ser desenvolvida conforme os pontos abaixo.

### Home - Characters
* Listagem dos personagens.
* Botão para marcar como favorito nas células.
* Barra de busca para filtrar a lista de personagens por nome.
* Interface de lista vazia, erro ou sem internet.

### Detalhes do personagem
* Botão de favorito.
* Foto em tamanho maior
* Descrição (se houver).

### Favoritos
* Listagem dos personagens marcados como favorito pelo usuário.
* Interface de lista vazia.

## Importante
* Subir o desafio em qualquer repositório **público** de sua preferência, i.e. (github, gitlab, bitbucket, etc.) e nos enviar o link.
* **Não faça nenhuma menção da marca Itaú e/ou Iti** no repositório e no projeto.

## Considerções finais
* Você pode utilizar bibliotecas de terceiros e gerenciadores de dependências como preferir.
