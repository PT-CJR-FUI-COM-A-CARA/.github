# 🐊 Fui Com a Cara - Avaliação de Professores

<p align="center">
  <img src="jacaréPc" height="300px" />
</p>

## Sobre

Este projeto é uma plataforma online desenvolvida com foco em proporcionar aos estudantes um ambiente colaborativo para compartilhar e consultar avaliações de professores universitários. Com uma interface amigável e funcionalidades robustas, o sistema visa ajudar na tomada de decisão durante a escolha de disciplinas.

Para realização do projeto, as seguintes tecnologias foram utilizadas:


<p align="left">
  <img src="https://img.icons8.com/color/48/000000/nestjs.png" alt="NestJS" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>NestJS</strong> – Framework Node.js para aplicações server-side escaláveis
</p>

<p align="left">
  <img src="https://i.pinimg.com/736x/4a/2b/e7/4a2be73b1e2efb44355436c40bf496dd.jpg" alt="Next.js" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>Next.js</strong> – Framework React para SSR e SSG
</p>

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>TypeScript</strong> – Superset do JavaScript com tipagem estática
</p>

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>JavaScript</strong> – Linguagem base do ecossistema web
</p>

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prisma/prisma-original.svg" alt="Prisma" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>Prisma</strong> – ORM moderno para Node.js e TypeScript
</p>

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>Tailwind CSS</strong> – Framework CSS utilitário para estilização rápida
</p>

<p align="left">
  <img src="https://raw.githubusercontent.com/react-icons/react-icons/master/react-icons.svg" alt="React Icons" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>React Icons</strong> – Biblioteca de ícones para projetos React
</p>



## Objetivo
O objetivo é fornecer uma comunidade online onde estudantes possam compartilhar experiências e avaliações sobre professores, facilitando a tomada de decisões informadas em relação à escolha de disciplinas durante o período de matrícula.


## Funcionalidades

- Realizar login na plataforma
- Alterar sua senha de forma segura
- Cadastrar um novo perfil com dados personalizados
- Adicionar uma foto ao seu perfil
- Visualizar seus próprios dados e avaliações no perfil
- Criar avaliações sobre professores, associando cada uma a uma disciplina específica
- Visualizar as avaliações de um determinado professor
- Comentar nas avaliações feitas por outros usuários
- Visualizar e excluir seus próprios comentários
- Excluir suas próprias avaliações
- Excluir completamente seu perfil da plataforma
- Ordenar as avaliações por data (da mais nova para a mais antiga e vice-versa)



## Como Executar
   
1. Clone o repositório:
  ```bash
  git clone https://github.com/seu-usuario/jacare-auth-app.git
  cd jacare-auth-app
  ```

2. Instale as dependências:
  ```bash
  npm install
  ```

3. Configure o banco de dados:
  ```bash
  #Crie o arquivo .env com o seguinte conteúdo:
  DATABASE_URL="file:./dev.db"   (ou a URL de sua instância PostgreSQL/MySQL)
  ```

4. Execute a migração inicial
  ```bash
    npx prisma migrate dev --name init
  ```

5. Rode o servidor de desenvolvimento
  ```bash
    npm run dev
  ```

6. Acesse no navegador
  ```bash
    http://localhost:3000 
  ```

## Créditos

<table align="center">
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/205556312?v=4" width=100><br>
            <b><a href="https://github.com/H3ytt0r62">Heyttor Augusto de Assis Silva</a></b><br>
      DEV
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/144493751?v=4" width=100><br>
            <b><a href="https://github.com/joaofmoreiraa">Joao Victor Felix Moreira</a></b><br>
      DEV
    </td>
   <tr>
   <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/169405654?v=4" width=100><br>
            <b><a href="https://github.com/jsalless">Johnnatan de Salles Sanches</a></b><br>
      DEV
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/161513513?v=4" width=100><br>
            <b><a href="https://github.com/pedroiaan">Pedro Ian Guedes De Carvalho</a></b><br>
      DEV
    </td>
   <tr>
</table>
