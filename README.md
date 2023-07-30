# Aplicação de uma página de Venda de E-commerce

Esta é a página de venda do E-commerce desenvolvida em TypeScript, utilizando Next.js e Tailwind CSS em conjunto com o Shadcn/ui para estilização.

A página de vendas se comunica com a página de administração, onde o projeto está localizado neste [repositório](https://github.com/pedrohxiv/ecommerce-admin), para um funcionamento completo da aplicação.

## Descrição

Esta página de venda é parte integrante do E-commerce, proporcionando aos usuários uma experiência intuitiva e atraente ao navegar e comprar produtos. Ela foi construída com tecnologias modernas, como React e Next.js, para garantir uma experiência de usuário responsiva e de alto desempenho.

O Tailwind CSS, aliado ao Shadcn/ui, é utilizado para criar uma interface estilizada, com componentes prontos para uso que agilizam o desenvolvimento e garantem uma aparência visualmente agradável.

## Funcionalidades

- Visualização detalhada do produto, incluindo imagem, preço, descrição e detalhes relevantes.
- Adição do produto ao carrinho de compras com opções de quantidade selecionáveis.
- Navegação intuitiva e responsiva para uma experiência de usuário fluida em dispositivos desktop e móveis.
- Integração com Stripe para realização da venda dos produtos.

## Pré-requisitos

Antes de visualizar a página de venda do E-commerce, certifique-se de ter as seguintes dependências instaladas:

- Node.js
- npm ou Yarn

## Instalação

1. Faça o clone deste repositório para o seu ambiente local.
2. Navegue até o diretório do projeto no terminal.
3. Execute o comando `npm install` ou `yarn install` para instalar as dependências do projeto.

## Configuração

Antes de iniciar a aplicação, você precisará configurar as seguintes variáveis de ambiente:

- `NEXT_PUBLIC_API_URL`: URL da sua página de administração para a realização do checkout do carrinho de compras.

Certifique-se de criar um arquivo `.env` na raiz do projeto e adicionar as variáveis de ambiente necessárias.

## Uso

Após a instalação, execute o seguinte comando para iniciar a página de venda:

```
npm run dev
```

Isso iniciará o servidor de desenvolvimento do Next.js e você poderá acessar a página de venda do E-commerce no seu navegador através do endereço `http://localhost:3001`.
