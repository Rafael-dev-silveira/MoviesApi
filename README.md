
Catálogo de Filmes com Vite + React
=

Este projeto consiste na criação de um site responsivo que utiliza o Vite e React para consumir uma API de filmes (como a TMDb API) e apresentar um catálogo interativo. A aplicação permite listar os 20 melhores filmes, realizar buscas personalizadas e acessar informações detalhadas de cada filme em páginas dedicadas. O projeto foi construído com React Hooks e implementa rotas utilizando o React Router.


Funcionalidades do Projeto:
Listagem Inicial de Filmes
=

Ao carregar o site, os 20 filmes mais bem avaliados são exibidos em uma grade responsiva.
Cada filme apresenta título, imagem e avaliação por estrelas.
Busca Dinâmica de Filmes.

Um campo de busca permite que os usuários pesquisem filmes específicos na API.
A pesquisa é realizada em tempo real, exibindo resultados relevantes na mesma página,
e detalhes do Filme.

Ao clicar em um filme, o usuário é redirecionado para uma página com informações detalhadas, incluindo:
Imagem em alta resolução,
Título e descrição completa,
Orçamento e receita do filme,
Avaliação representada por estrelas.
A página de detalhes também inclui um botão para retornar à página inicial.

Interface Responsiva
=

O site é totalmente responsivo, garantindo uma experiência otimizada em desktops, tablets e smartphones.

Ferramentas e Tecnologias Utilizadas:
=
Vite: Configuração leve e rápida para o desenvolvimento com React.

React: Biblioteca principal para a construção da interface.

React Hooks: Gerenciamento de estado com useState e useEffect.

React Router: Gerenciamento de rotas para navegação entre as páginas.

Axios: Requisições HTTP para consumir a API de filmes.

CSS Responsivo: Estilização moderna com Flexbox e Grid.

Etapas de Desenvolvimento:
Configuração Inicial
=

Instalação do Vite e criação do template base em React.

Configuração das dependências como React Router e Axios.

Consumo da API
=

Configuração de chamadas para a API de filmes.

Implementação de endpoints para listar filmes populares e buscar filmes específicos.

Criação dos Componentes
=

Componente de Header com campo de busca.

Grid de Filmes para exibir os 20 melhores filmes.

Página de Detalhes do Filme para exibir informações completas.

Gerenciamento de Rotas
=

Configuração de rotas para navegação entre a página inicial e os detalhes do filme.

Estilização e Responsividade
=
Utilização de CSS com Media Queries para adaptar o layout a todos os dispositivos.

Conclusão :
=
Com este projeto, você terá uma aplicação moderna que demonstra habilidades práticas em React, consumo de APIs, e desenvolvimento front-end responsivo.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
