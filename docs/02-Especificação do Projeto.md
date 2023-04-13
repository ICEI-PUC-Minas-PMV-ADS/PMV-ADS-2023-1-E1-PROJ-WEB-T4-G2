# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação dos usuários em um trabalho de imersão feita pelos membros da equipe a partir da observação dos usuários em seu local natural e por meio de entrevistas. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.

## Personas

Jade Andrade, de 19 anos, é uma estudante de Publicidade e Propaganda que trabalha como Designer Gráfico nas horas vagas. Ela é apaixonada pela arte e busca inspirar outras jovens mulheres a perseguir seus sonhos, enquanto procura oportunidades para aprimorar suas habilidades. Jade tem como hobbies dançar, tocar violão, escrever poesia e fotografar. No entanto, ela enfrenta frustrações por nunca ter tido a oportunidade de fazer aulas de dança formalmente, ser pressionada a encontrar um emprego estável e não ter tido sorte em relacionamentos. Jade cresceu em uma família modesta em uma cidade pequena. Seus aplicativos de uso regular são o Instagram, Twitter, TikTok, Tinder e LinkedIn.

Gilberto Sousa, de 26 anos, é um Desenvolvedor Pleno que trabalha em uma empresa de tecnologia em São Paulo. Ele busca progressão de carreira e procura aliviar o estresse do trabalho saindo com os amigos e mantendo uma vida saudável. No entanto, ele enfrenta frustrações devido à sobrecarga no trabalho, falta de tempo para seus hobbies e isolamento social. Gilberto é apaixonado por jogos de computador, pratica esportes, faz trilhas e gosta de sair com os amigos. Seus aplicativos de uso regular são o Discord, LinkedIn, Instagram e Reddit.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO...| QUERO/PRECISO ... |PARA ... |
|--------------------|------------------------------------|----------------------------------------|
|Jade Andrade | Visualizar os restaurantes mais relevantes do momento | Estar por dentro dos restaurantes em alta |
|Gilberto Souza| Visualizar restaurantes que contém meu prato preferido | Gastar menos tempo olhando o cardápio de cada restaurante |
|Jade Andrade|Buscar por um restaurante mais perto da minha localização|Não me locomover grandes quilometragens|
|Gilberto Souza|Fazer comentários em restaurantes e avaliar minhas experiências|Ajudar pessoas que tem interesse em visitar o restaurante|
|Jade Andrade|Compartilhar fotos e vídeos dos restaurantes que frequento|Que outras pessoas que estão interessadas nesse restaurante possam ver|
|Gilberto Souza|Salvar um restaurante aos favoritos|Achá-lo caso eu queira visualizar o cardápio ou fazer uma nova avaliação|

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Requisito | Descrição do Requisito | Prioridade |
|------|-----------|------------------------|------------|
|RF-01|Manter cadastro dos restaurantes|O site deve apresentar na página principal os restaurantes cadastrados para a realização de buscas. Esse cadastro permitirá a utilização de imagens para uma visualização dinâmica.|ALTA|
|RF-02|Manter cardápio e preços|O site deve apresentar cardápio (disponibilizado pelo restaurante) com valores atualizados.|ALTA|
|RF-03|Buscar restaurante|Na ferramenta de busca o usuário poderá fazer a busca pelo prato desejado e será apresentado a lista dos restaurantes com a opção desejada|MÉDIA|
|RF-04|Avaliações|O site deve permitir que o usuário avalie os estabelecimentos cadastrados, inserindo nota e comentário após sua experiência.|MÉDIA|
|RF-05|Localização|O site deve oferecer uma funcionalidade de busca de restaurantes considerando a localização do usuário.|MÉDIA|
|RF-06|Contato|O site deve permitir visualizar as informações de contatos do mantenedor do site|MÉDIA|
|RF-07|Favoritos|O site deve permitir salvar os restaurantes favoritos.|BAIXA|
|RF-08|Filtros|Filtros de busca por pratos/restaurantes por locais , o site oferecerá diversos filtros.|BAIXA|

### Requisitos não Funcionais

|ID     | Requisito  | Descrição do Requisito | Prioridade |
|-------|------------|------------------------|------------|
|RNF-01|Ambiente|O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, Heroku)|ALTA| 
|RNF-02|Layout|O site deverá ser responsivo permitindo a visualização em um celular de forma adequada.|ALTA|
|RNF-03|Compatibilidade|O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge)|ALTA|
|RNF-04|Vincular usuário|Login do usuário para registro das avaliações (poderá ser com conta google, apple ou usuário do facebook)|MÉDIA|
|RNF-05|Campos de cadastros|Campos obrigatórios para cadastro dos cardápios com os valores dos produtos.|MÉDIA|
|RFN-06|Cadastro de imagens|O usuário devidamente logado poderá incluir imagens da sua experiência no estabelecimento|BAIXA|

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.


|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01|O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 07/07/2023.|
|RE-02|O aplicativo deve se restringir às tecnologias básicas da Web no Frontend|
|RE-03|A equipe não pode subcontratar o desenvolvimento do trabalho.|
