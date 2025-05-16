# UniTech - Plataforma Educacional

## Descrição

UniTech é um projeto de plataforma educacional web que oferece aos usuários a possibilidade de visualizar cursos, obter informações sobre a instituição, entrar em contato e gerenciar perfis de usuário. O projeto é construído com HTML, Tailwind CSS e JavaScript para interatividade no lado do cliente.

## Funcionalidades

* **Navegação:** Interface de navegação intuitiva com links para as principais seções do site.
* **Página Inicial:** Apresenta a UniTech, seus diferenciais e galeria de fotos.
* **Sobre Nós:** Detalha a história, missão, visão e valores da instituição, além de depoimentos.
* **Cursos:** Lista de cursos disponíveis com filtros por categoria, duração e dias da semana. Permite visualizar detalhes de cada curso em um modal.
* **Contato:** Formulário para os usuários enviarem mensagens.
* **Perfil do Usuário:** Exibe informações do perfil do usuário (foto e nome), com opção de logout.
* **Registro de Usuário:** Permite que novos usuários criem uma conta.
* **Login de Usuário:** Permite que usuários registrados acessem suas contas.
* **Seção de Programação:** Página informativa sobre o curso de programação com recursos úteis.

## Páginas do Projeto

O projeto é composto pelas seguintes páginas HTML:

* `Home.html`: Página principal da plataforma.
* `sobre.html`: Página com informações sobre a UniTech.
* `cursos.html`: Página de listagem e busca de cursos.
* `contato.html`: Página com formulário de contato.
* `perfil.html`: Página de perfil do usuário.
* `registro.html`: Página para registro de novos usuários.
* `programacao.html`: Página dedicada a informações sobre programação.
* `login.html` (referenciada em `Home.html` e `sobre.html`): Embora o arquivo `login.html` não tenha sido fornecido, ele é referenciado nas páginas Home e Sobre, indicando sua existência e propósito para o login de usuários.

## Tecnologias Utilizadas

* **HTML5:** Estrutura das páginas web.
* **Tailwind CSS:** Framework CSS para estilização rápida e responsiva.
* **JavaScript:** Para interatividade do usuário, manipulação do DOM (como modais, filtros de cursos, funcionalidade de login/registro e atualização da navbar).

## Como Executar

1.  Clone este repositório (ou baixe os arquivos).
2.  Abra qualquer um dos arquivos `.html` em seu navegador de preferência.
    * Recomenda-se começar pelo `Home.html` para ter a experiência de navegação completa.

**Observação:** As funcionalidades de login, registro e perfil utilizam o `localStorage` do navegador para simular o armazenamento de dados do usuário. Não há um backend real implementado para persistência de dados em servidor.

---

Este README fornece uma visão geral do projeto UniTech. Sinta-se à vontade para explorar os arquivos e o código para mais detalhes.
