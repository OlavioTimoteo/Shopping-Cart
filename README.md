# Projeto Shopping Cart

## Descrição

Nesse projeto, você será capaz de:

- Fazer requisições a uma API _(Application Programming Interface)_ do Mercado Livre;

- Utilizar os seus conhecimentos sobre JavaScript, CSS e HTML;

- Trabalhar com funções assíncronas;

---

# Entregáveis

Para entregar o seu projeto você deverá criar um Pull Request neste repositório.

Lembre-se que você pode consultar nosso conteúdo sobre [Git & GitHub](https://app.betrybe.com/course/fundamentals/git) sempre que precisar!

## O que será desenvolvido

Nesse projeto vocês farão um **carrinho de compras** totalmente dinâmico! E o melhor: consumindo dados diretamente de uma **API!** Isso mesmo. Da sigla em inglês _Application Programming Interface_, uma API é um ponto de contato na internet com determinado serviço. Através de **requisições HTTP** a essa API é possível interagir com ela da forma como quem a criou planejou. Aqui usaremos a API do Mercado Livre para buscarmos produtos à venda.

![Project Gif](./out.gif)

---

## Instale as dependências:

- `npm install`

- Verifique que você está na branch `main`

### ESLint e Stylelint

Para garantir a qualidade do código, são utilizados neste projeto os linters `ESLint` e `Stylelint`.

Assim o código estará alinhado com as boas práticas de desenvolvimento, sendo mais legível

e de fácil manutenção! Para rodá-los localmente no projeto, execute os comandos abaixo:

```bash

npm run lint

npm run lint:styles

```

### Cypress

Você pode rodar o cypress localmente para verificar se seus requisitos estão passando, para isso execute um dos seguintes comandos:

Para executar os testes apenas no terminal:

```bash

npm test

```

Para executar os testes e vê-los rodando em uma janela de navegador:

```bash

npm run cypress:open

```

**_ou_**

```bash

npx cypress open

```

---
