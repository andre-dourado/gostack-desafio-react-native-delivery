<img alt="GoStack" src="https://res.cloudinary.com/andredourado/image/upload/v1593100530/GoStack/bg_gostack_ya1jev.png" />

<h3 align="center">
  Desafio 11: GoRestaurant Mobile
</h3>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/andrewdourado/gostack-desafio-react-native-delivery.svg">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/andrewdourado/gostack-desafio-react-native-delivery.svg">
  
  <a href="https://github.com/andrewdourado/twitter-layout/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/andrewdourado/gostack-desafio-react-native-delivery.svg">
  </a>

  <a href="https://github.com/andrewdourado/twitter-layout/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/andrewdourado/gostack-desafio-react-native-delivery.svg">
  </a>

  <img alt="GitHub" src="https://img.shields.io/github/license/andrewdourado/gostack-desafio-react-native-delivery.svg">
</p>

<p align="center">
  <a href="#gear-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-instalação">Instalação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="App Demo" src="https://res.cloudinary.com/andredourado/image/upload/v1593107897/GoStack/delivery_app_1.gif" width="400px">
  <img alt="App Demo" src="https://res.cloudinary.com/andredourado/image/upload/v1593107923/GoStack/delivery_app_2.gif" width="400px">
</p>

## :gear: Tecnologias

-  [Typescript](https://www.typescriptlang.org/) 
-  [React Native](https://reactnative.dev/) 
-  [Styled Components](https://www.styled-components.com/)
-  [Axios](https://github.com/axios/axios) 
-  [Jest](https://jestjs.io/) 

## :information_source: Instalação

Para clonar e executar esta aplicação, você precisa do [Git](https://git-scm.com) e [Yarn v1.13](https://yarnpkg.com/) ou maior instalados.

Antes de tudo, para exibir os dados em tela, é necessário utlizar uma fake API para prover esses dados.

Para isso, há no package.json uma dependência chamada `json-server`, e um arquivo chamado `server.json` que contém os dados. Para execução segue o 
seguinte comando: 

```js
  yarn json-server server.json -p 3333
```

Logo em seguida execute os seguintes comandos: 

```bash
# Clona este repositório
$ git clone https://github.com/andrewdourado/gostack-desafio-react-native-delivery

# Acessa o repositório clonado
$ cd gostack-desafio-react-native-delivery

# Instala as dependências
$ yarn

# Dependências nativas do ios (apenas Mac)
$ cd ios
$ pod install

# Executa o projeto. iOS apenas no Mac.
$ yarn ios
$ yarn android
```

## :rocket: Sobre o desafio

Neste desafio foi desenvolvido a GoRestaurant na versão mobile voltada para o cliente. Desenvolvida em React Native 
junto com TypeScript, a aplicação fica responsável por lidar com pedidos de comida.

Essa é aplicação que se conecta a uma Fake API, exibe e filtra os pratos de comida da API e permite a criação de novos pedidos.


### Funcionalidades da aplicação

- **`Listar os pratos de comida da sua API`**: Na página `Dashboard` é capaz de exibir uma listagem, com o campo `name`, `value` e  `description` de 
todos os pratos de comida que estão cadastrados na API.

- **`Listar as categorias da sua API`**: Na página `Dashboard` é capaz de exibir uma listagem, com o campo `title` e `image_url` de todas as categorias 
que estão cadastrados na API.

- **`Filtrar pratos de comida por busca ou por categorias`**: Na página Dashboard permite que o input de pesquisa e os botões de categoria façam uma busca 
na API de acordo com o que estiver selecionado ou escrito no input.

- **`Listar os pedidos da sua API`**: Na página `Orders` é capaz de exibir uma listagem, com o campo as informações do produto pedido, com `name` e `description` 
de todos os pedidos que estão cadastrados na API.

- **`Listar os pratos favoritos da sua API`**: Na página `Favorites` é capaz de exibir uma listagem, com o campo as informações do produto favorito, 
com `name` e `description` de todos os pedidos que estão cadastrados na API.

- **`Realizar um pedido`**: Na página `Dashboard`, ao clicar em um item, ele redireciona o usuário para a página `FoodDetails`, onde é possível realizar um 
novo pedido, podendo controlar a quantidade desse item pedido, ou adicionar ingredientes extras. Todo o valor é calculado de acordo com a quantidade pedida.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/andrewdourado/gostack-desafio-react-native-delivery/blob/master/LICENSE) para mais informações.

---

Made with ♥ by André Dourado :wave: [Get in touch!](https://www.linkedin.com/in/andre-dourado/)
