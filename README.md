# Teste iOS

## Desafio
O objetivo é implementar um app onde podemos ver a lista de personagens da Marvel.

 - [ ] O app deve mostrar uma lista e ser possível navegar para os detalhes de cada personagem. 
- [ ] Além disso, o personagem poderá ser favoritado tanto na lista quanto na tela de detalhes. 
- [ ] Os personagens favoritados devem ser persistidos no device para que possam ser acessados offline e serem mostrados em uma aba própria.

Nos entregue quando estiver orgulhoso do que fez! =)

## API
Para desenvolver o app você vai precisar usar o endpoint de "Characters" da API Marvel. Mais informações: https://developer.marvel.com/docs.

## Interface
A interface do app é dividida em 3 partes e deve ser desenvolvida conforme os pontos abaixo.

### Home - Characters
* Listagem dos personagens.
* Botão para favoritar nas células.
* Barra de busca para filtrar lista de personagens por nome.
* Interface de lista vazia, erro ou sem internet.

### Detalhes do personagem
* Botão de favorito.
* Foto em tamanho maior
* Descrição (se houver).

### Favoritos
* Listagem dos personagens favoritados pelo usuário.
* Interface de lista vazia, erro ou sem internet.

## Requisitos Essenciais
* Usar Swift 5
* Tratamento para falha de conexão.
* O teste não pode apresenter crash.
* App universal, desenvolva uma interface que se adapte a telas maiores.

## Bônus
* Testes de interface
* Testes unitários
* Integração com alguma ferramenta de CI/CD
* Integração com fastlane para cobertura de testes.
* Slather

## Importante
* Subir o desafio em um repositório no github/gitlab/bitbucket e mandar o link.
* Não ter nenhuma mensão do Itaú/Iti no Repositório/Projeto.

## Observações
* Você pode utilizar bibliotecas de terceiros e gerenciadores de dependências como preferir.
* Foque o desenvolvimento nos requisitos essenciais. 
* O bônus vai diferenciar você dos outros candidatos, mas os requisitos essenciais são mais importantes.
