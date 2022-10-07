<h1 align="center">
  <img width="280px" src="https://ik.imagekit.io/imagens/RocketShoes/logo_rocketshoes.png" alt="Logo RocketShoes" />
</h1>

<p align="center">
<img alt="GitHub language count" src="https://img.shields.io/github/languages/count/TalissonOliveira/desafio-ignite-03-reactjs-hook-de-carrinho-de-compras?style=flat-square">

<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/TalissonOliveira/desafio-ignite-03-reactjs-hook-de-carrinho-de-compras?style=flat-square">

<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/TalissonOliveira/desafio-ignite-03-reactjs-hook-de-carrinho-de-compras?style=flat-square">
</p>

<p align="center">
    <a href="#book-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#test_tube-testes">Testes</a>
</p>

<p align="center">
    <img alt="Preview" src="https://ik.imagekit.io/imagens/RocketShoes/rocketshoes-preview_jUCkMcBS5.gif">
</p>


# :book: Sobre o desafio

Desafio 03 da trilha de ReactJS do [Ignite](https://rocketseat.com.br/ignite) proposto pela [Rocketseat](https://www.rocketseat.com.br/) para treinar os conhecimentos adquiridos no Chapter II.
No desafio, foi feito criação de um hook para gerenciar um carrinho de compras.
A aplicação tem duas páginas, um componente e um hook para implementar as funcionalidades pedidas nesse desafio:
-   Adicionar um novo produto ao carrinho;
-   Remover um produto do carrinho;
-   Alterar a quantidade de um produto no carrinho;
-   Cálculo dos preços subtotal e total do carrinho;
-   Validação de estoque;
-   Exibição de mensagens de erro;
-   Entre outros.

## :rocket: Tecnologias
Neste desafio pratiquei as seguintes tecnologias:

- [ReactJS](https://reactjs.org/)
- [json-server](https://github.com/typicode/json-server)
- [react-toastify](https://fkhadra.github.io/react-toastify/introduction)
- [Axios](https://axios-http.com/)

# :test_tube: Testes

### Header
- [x] should be able to render the amount of products added to cart
### Home
- [x] should be able to render each product quantity added to cart
- [x] should be able to add a product to cart
### Cart
- [x] should be able to increase/decrease a product amount
- [x] should not be able to decrease a product amount when value is 1
- [x] shoud be able to remove a product
### useCart
- [x] should be able to initialize cart with localStorage value
- [x] should be able to add a new product
- [x] should not be able add a product that does not exist
- [x] should be able to increase a product amount when adding a product that already exists on cart
- [x] should not be able to increase a product amount when running out of stock
- [x] should be able to remove a product
- [x] should not be able to remove a product that does not exist
- [x] should be able to update a product amount
- [x] should not be able to update a product that does not exist
- [x] should not be able to update a product amount when running out of stock
- [x] should not be able to update a product amount to a value smaller than 1

---

Feito com :heart: por Talisson Oliveira