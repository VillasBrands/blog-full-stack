# Forum Full-Stack com Ruby on Rails

Este é um projeto de teste para uma vaga de desenvolvedor Ruby on Rails. O objetivo é criar um fórum simples com autenticação de usuários, posts e comentários. O tema do fórum será focado em discussões sobre construção e engenharia civil, atendendo às necessidades de uma empresa de construção.

## Contexto do Projeto

Você deve inventar um nome para a empresa de construção fictícia que deseja criar um espaço online onde engenheiros, arquitetos, operários e entusiastas da construção possam compartilhar conhecimentos, discutir projetos e resolver dúvidas. Este fórum servirá como uma plataforma para conectar profissionais da área e facilitar a troca de informações técnicas e experiências de campo.

## Requisitos Técnicos

- Ruby: 3.1.2
- Rails: 7.0.4
- Banco de Dados: PostgreSQL
- Devise
- Git

## Funcionalidades

1. **Autenticação de Usuários:**
   - Registro de usuários
   - Login
   - Logout

2. **Posts do Fórum:**
   - Criação de posts (usuários autenticados)
   - Edição de posts (usuários autenticados)
   - Exclusão de posts (usuários autenticados)
   - Cada post deve ter um título e um conteúdo
   - Cada post deve estar associado a um usuário

3. **Comentários nos Posts:**
   - Adição de comentários nos posts (usuários autenticados)
   - Cada comentário deve estar associado a um usuário e a um post

## Front-End

Você pode criar o front-end responsivo da maneira que preferir, contanto que atenda aos seguintes requisitos:

1. **Tela de Login e Cadastro:**
   - Tela para usuários se registrarem.
   - Tela para usuários fazerem login.

2. **Navbar:**
   - Exibir o nome do usuário logado.
   - Opção para o usuário fazer logout.
   - Link para "Meus Posts" que exibe apenas os posts criados pelo usuário logado.

3. **Página Inicial:**
   - Listar todos os posts com o título e uma descrição reduzida.
   - Botão "Ver Mais" para cada post que leva à página de visualização do post completo.

4. **Página de Visualização do Post (Show):**
   - Exibir o post completo.
   - Formulário para adicionar comentários abaixo do post.

5. **Página "Meus Posts":**
   - Exibir todos os posts criados pelo usuário logado.
   - Permitir que o usuário edite ou delete seus próprios posts.

## Documentação

Inclua no `README.md` as seguintes informações:

- Como configurar e rodar o projeto localmente.
  * Instruções detalhadas sobre como clonar o repositório, instalar dependências, configurar o banco de dados e iniciar o servidor Rails.
- Como foi feito o fluxo:
  * Descrição detalhada do fluxo de usuários na aplicação, desde o registro e login até a criação e interação com posts e comentários.
- Decisões importantes tomadas durante o desenvolvimento:
  * Explicações sobre escolhas tecnológicas ou arquiteturais significativas.
  * Justificativas para a estrutura do banco de dados, a escolha de bibliotecas ou gems, e padrões de design aplicados.
  * Descrição de qualquer desafio encontrado e como foi resolvido.

## Entrega

- Envie o código do projeto em um repositório público no GitHub.
- Compartilhe o link do seu repositório público conosco.

Boa sorte! Estamos ansiosos para ver seu trabalho.
