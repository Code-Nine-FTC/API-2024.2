<img src="CodeNine.png">
<br>
<h1> Fatec Prof° Jessen Vidal - 2º Semestre de 2024 </h1>
<p> Projeto desenvolvido por alunos do 3º semestre do curso de Desenvolvimento de Software Multiplataforma para o API (Aprendizagem por Projetos Integrados),
 com o objetivo de produzir um portal de transparência para uma fundação, visando a capacidade de inserção de dados dos projetos, busca utilizando filtros, portabilidade dos dados do sistema legado e a formulação de estatísticas acerca dos proejetos cadastrados sendo exibidas em gráficos e contendo filtros aplicáveis.  </p>
<br>

<h2> 🗂️ Índice </h2>

- [Metodologia Utilizada](#metodologias)
- [Tecnologias Utilizadas](#tecnologias)
- [Manual do Usuário](#manual)
- [MVP](#mvp)
- [Requisitos do Cliente](#requisitoscliente)
- [Product Backlog](#productbacklog)
- [Sprints](#sprints)
- [DoR e DoD](#doredod)
- [Padrão de Commit](#padraocommit)
- [Integrantes do grupo](#integrantes)

<br>

<h2> 📋 Metodologia Utilizada </h2><a name="metodologias"></a>

<p> O framework de Metodologia Ágil utilizado no produto foi o Scrum, um método ágil adaptativo, iterativo, flexível e eficaz.
Entre as ferramentas utilizadas no Scrum, uma é a divisão do projeto em Sprints. Para selecionar quais seriam as entregas das nossas Sprints, primeiro definimos nosso MVP, priorizando as tarefas que trariam maior entrega de valor para o cliente. Então, a partir das Tarefas foi construído o Backlog do Produto,  o qual foi aprovado pelo cliente e dividido em 4 Backlogs de Sprint. </p>

<br>

<h2> 🖥️ Tecnologias Utilizadas </h2><a name="tecnologias"></a>

<p> Essas foram as Tecnologias Utilizadas para produção do projeto. </p>

<br>

<div align="center">
  <a href="https://discord.com/"><img src="https://img.shields.io/badge/Discord-4a1fa8?style=for-the-badge&logo=discord&logoColor=white&color=00046D"/>
  <a href="https://www.figma.com/"><img src="https://img.shields.io/badge/Figma-3ad6b2?style=for-the-badge&logo=figma&logoColor=c41f1f&color=00046D"/>
  <a href="https://github.com/"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white&color=00046D"/>
  <a href="https://www.w3schools.com/html/"><img src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=da5d1e&color=00046D"/>
  <a href="https://www.w3schools.com/Css/"><img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=1e6fda&color=00046D"/>
  <a href="https://www.typescriptlang.org"> <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white&color=00046D"/>
  <a href="https://www.java.com/pt-BR/"> <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white&color=00046D"></a>
  <a href="https://react.dev"><img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=white&color=00046D"/>
  <a href= "https://slack.com/intl/pt-br"><img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white&color=00046D"/>
  <a href="https://www.mysql.com/"><img src="https://img.shields.io/badge/MySQL-4a1fa8?style=for-the-badge&logo=mysql&logoColor=white&color=00046D"/>

<br>
<br>

<h2> Manual do Usuário </h2><a name="manual"></a>

<p> Os links abaixo exibem os manuais de usuário, destinados para cada tipo de usuário do produto.</p>


[Mapeamento de rotas (endpoinsts)](Docs/mapeamentoderotas.pdf)
<br>
<br>
[Manual Usuário Comum]
<p> Em desenvolvimento</p>
[Manual Administrador]
<p> Em desenvolvimento</p>

<h2> 🏆 MVP </h2><a name="mvp"></a>

<h3> Primeira Sprint </h3>

<h4> Busca e visualização de projetos pelo usuário </h4>

https://github.com/user-attachments/assets/d781b36e-cebc-4fee-9636-185fd3ad808d

<h4> Gerenciamento do projeto e login do administrador </h4>

https://github.com/user-attachments/assets/f9e47738-1a1a-42ec-8a94-ab079430d7bb

h3> Segunda Sprint </h3>

<h3> Busca de estátisticas dos projetos cadastrados por meio do dashboard </h3>

<p> Em desenvolvimento </p>

<h3> Implementação dos projetos do sistema legado na aplicação atual </h3>

<p> Em desenvolvimento </p>


<h2> 📖 Requisitos do Cliente </h2><a name="requisitoscliente"></a>

| Número	| Requisito do Cliente |
| --- | --- |
| 1 | Importar os dados dos projetos da ferramenta legado para o novo site |
| 2	| Interface para cadastro de novos projetos onde esses possuirão apenas campos relacionados a planos de trabalho, contratos e termos aditivos |
| 3	| Um mecanismo de busca para os projetos de uma forma que não separe por categoria como é feito no site antigo |
| 4	| Criação de uma credencial pro usuário Administrador, que terá todas as permissões do site |
| 5	| Relatórios/dashboards de projetos desenvolvidos, com diferentes tipos de filtros |

<h3> Requisitos não funcionais </h3>

| Número	| Requisito do Cliente |
| --- | --- |
| 1 | Manual do Usuário e Mapeamento de Endpoints |
| 2	| Software Web |
| 3	| Responsividade para uma melhor experiência do usuário |
| 4	| Segurança da Informação |

<br>

# Proposta de Solução

O site funcionará como um portal de transparência para pesquisas de pós-Graduandos, contendo uma ferramenta de busca para os projetos e um dashboard, ambos com filtragem para apresentação das informações dos projetos, onde o administrador poderá criar e editar os próprios projetos, otimizando a gestão. 
Propomos a implementação de um sistema que permita a padronização automática das informações. Para otimizar a gestão e apresentação dos dados dos projetos. Nossa solução incluirá os seguintes recursos:

Padronização de Dados: Desenvolveremos um modelo uniforme para os dados dos projetos, garantindo que todas as informações sejam consistentes e de fácil compreensão. 

Integração com o Banco de Dados: Quando arquivos Excel ou PDF forem carregados no site, o sistema extrairá e processará os dados automaticamente, enviando-os diretamente para o banco de dados. Isso garantirá que todas as informações estejam sempre atualizadas e centralizadas.

<h2> 📒 Product Backlog </h2><a name="productbacklog"></a>

| Id | Prioridade | Tarefas | Estimativa | Requisito do Cliente | Critério de Aceitação |
| --- | --- | --- | --- | --- | --- |
| 1 | Alta  | Como Administrador, eu quero criar um projeto para o site de tranparência, para que o Usuário possa visualizar todos os detalhes do projeto. | 5 | 2 | Somente o Administrador poderá criar novos projetos, devendo preencher todas as informações relevantes para garantir maior transparência ao Usuário. |
| 2 | Alta  | Como Usuário, eu quero ter a possibilidade de buscar  projetos com um filtro, para que eu possa encontrar de forma mais precisa e rápida os projetos que atendem aos meus critérios de interesse. | 3 | 3 | Prévia com informações básicas do projeto para maior facilidade do Usuário ao visualizar o projeto |
| 3 | Alta  | Como Administrador, eu quero ser capaz de enviar, editar ou excluir todos os projetos, para que eu consiga administrar o portal de transparência. | 3 | 2 | O Administrador deve ter todas as permissões para manipular o projeto |
| 4 | Alta  | Como Administrador, eu quero realizar login no sistema utilizando e-mail e senha, para que eu possa acessar as funcionalidades administrativas de maneira segura. | 3 | 3 | O Administrador deve ter credenciais protegidas para conseguir efetuar o login sem vazamentos de dados |
| 5 | Alta  | Como Usuário, eu quero poder visualizar os detalhes relacionado ao projeto, para que eu possa entender o andamento e o progresso do projeto de forma clara e objetiva. | 3 | 4 | Criação de uma página de visualizar um projeto em específico onde irá conter todas as informações referentes ao projeto |
| 6 | Alta  | Como Administrador, eu quero poder visualizar os detalhes e os relatórios relacionado ao projeto, para que eu possa monitorar o andamento e manter o site atualizado sem modificar o conteúdo ou interferir nas decisões dos projetos. | 3 | 2 | Criação de uma página de visualizar um projeto em específico onde irá conter todas as informações referentes ao projeto |
| 7 | Alta  | Como Administrador, eu quero transformar os dados da ferramenta legado, para que esses dados sejam compatíveis e utilizáveis no novo sistema, permitindo a continuidade dos processos e projetos. | 4 | 1 | As informações dos projetos do Site Legado deverá ser importado ao novo sistema |
| 8 | Média | Como Administrador, eu quero ter acesso a um dashboard centralizado, para que eu possa visualizar de forma clara e rápida as informações mais relevantes sobre os projetos. | 5 | 4 | Dashboard contendo as informações da situação de todos os projetos |
| 9 | Média | Como Administrador, eu quero importar projetos em formato PDF e/ou Excel dos dados da aplicação legada no novo banco de dados, para que todos os dados históricos e ativos sejam migrados corretamente para o novo sistema e possam ser acessados e gerenciados no portal atualizado. | 6 | 1 | As informações dos projetos do Site Legado deverá ser importado ao novo sistema |
| 10 | Média | Como Administrador, eu quero conseguir visualizar oque foi alterado em um registro no site para conseguir visualizar as mudanças de um determinado projeto | 8 | 5 | A visualização do projeto deverá possuir um campo mostrando todos os campos que foi alterado mostrando a Informação anterior |
| 11 | Média | Como Administrador, eu quero conseguir ocultar um determinado campo ou projeto do usuário comum porém o Administrador ainda tem acesso a essas informações para caso precise ocultar determinado projeto | 8 | 5 | No projeto deverá haver um botão para ocultar o projeto ou campos do projeto porém ainda mostrando ao Administrador na visualização | 
| 12 | Média | Como Administrador, eu quero transformar as informações do Banco de Dados em arquivos do formato do PDF e/ou Excel, para que eu possa compartilhar, armazenar e analisar os dados de maneira eficiente e compatível com outras ferramentas. | 5 | 1 | Na página de visualização do projeto o Administrador poderá anexar um Arquivo PDF ou Excel |
| 13 | Baixa | Como Usuário, eu quero que o site tenha um design responsivo, para que eu possa acessá-lo e utilizá-lo confortavelmente em qualquer dispositivo, seja desktop, tablet ou celular. | 2 | 3 | O site deverá ser responsível para Mobile, Desktop |
<br>

<h2> 📑 Sprints </h2><a name="sprints"></a>

| Sprint | Início     | Entrega    | Relatório            | Status |
|--------|------------|------------|----------------------|--------|
|   01   | 09/09/2024 | 29/09/2024 | <a href="https://github.com/Code-Nine-FTC/API-2024.2/tree/Sprint-1"> 1° Relatório </a> |   ✅   |
|   02   | 30/09/2024 | 20/10/2024 | <a href="https://github.com/Code-Nine-FTC/API-2024.2/tree/Sprint-2"> 2° Relatório </a> |   🔁   |
|   03   | 21/10/2023 | 10/11/2024 | <a> 3° Relatório </a> |   ❌   |
|   04   | 11/11/2023 | 01/12/2023 | <a> 4° Relatório </a> |   ❌   |

<br>
</div>
<h2 align="center"> DoR e DoD </h2><a name="doredod"></a>

# Definition of Ready (DoR) 

### User Stories

- User story devidamente priorizado e tem valor para o cliente/usuário.
- A descrição do User story está clara e compreensível para todos os membros da equipe

### Critérios de Aceitação 

- Critérios de aceitação estão definidos e revisados
- Especificações técnicas ou requisitos adicionais, se necessários, estão definidos

### Tarefas 

- Recursos e permissões necessárias para implementação foram garantidos
- O user story é pequeno o suficiente para ser concluído dentro de uma sprint


<br>
<br>

# Definition of Done (DoD)

### Código e Integração

- O código foi implementado, revisado e integrado com sucesso no repositório principal.
- O código foi revisado e aprovado por outro desenvolvedor ou pela equipe.

### Critérios de Aceitação

- Todos os critérios de aceitação definidos no user story foram atendidos.
- A funcionalidade foi validada em ambientes diferentes (testes de responsividade, performance, dispositivos variados).
- O user story foi revisado e aceito pelo Product Owner ou partes interessadas.

### Testes e Qualidade

- Os testes foram realizados, garantindo que o comportamento é o esperado.
- Não há bugs conhecidos ou regressões, e o sistema permanece estável.

### Documentação

- A documentação técnica foi atualizada, caso seja necessário.
- A documentação do usuário, se aplicável, foi criada ou atualizada (manual do usuário, guia de uso).

### Implantação e Feedback

- A funcionalidade foi implantada em produção, se aplicável, e está funcionando corretamente.
- Feedback pós-implementação, se aplicável, foi coletado e considerado.

<div align="center">
<h2> Padrão de Commit </h2><a name="padraocommit"></a>

| Prefixo |   Função  |  Exemplo  |
| :------: | :--------: | :-------: |
| Feat | Informar uma funcionalidade adiconada | feat: Função de verificação de CPF criada |
| Fix | Informar um erro corrigido | fix: Erro de autenticação ao logar com dados vazios corrigido |
| Style | Utilizado para formatações no código que não afetam as funcionalidades | style: Identações da classe de login do cliente corrigidas |
| Docs | Utilizado para indicar adições à documentação do projeto | docs: Documentação dos endpoints adicionada |
| Refactor | Utilizado para reestruturações no código, melhorando o código para uma versão mais limpa | refactor: Estrutura da tela de dashboard refeita, funções desnecessárias retiradas |

<h2> 🙎 Integrantes do Grupo </h2><a name="integrantes"></a>

|          |   Nome   |  Função  |  GitHub  | LinKedin |
| :------: | :------: | :------: | :------: | :------: |
| <img src="https://avatars.githubusercontent.com/u/104574671?v=4" alt="foto de perfil" height="64px" width="64px">         |   Davi Maciel  |  Scrum Master     | <a href="https://github.com/DfMaciel"><img src="https://img.shields.io/badge/GitHub-13196a?style=for-the-badge&logo=github&logoColor=white">         | <a href="https://www.linkedin.com/in/dfmaciel"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>          |
| <img src="https://avatars.githubusercontent.com/u/142221456?v=4" alt="foto de perfil" height="64px" width="64px">         |   Pedro Oliveira |  Product Owner      | <a href="https://github.com/OliveiraPedro09"><img src="https://img.shields.io/badge/GitHub-13196a?style=for-the-badge&logo=github&logoColor=white">         | <a href="https://www.linkedin.com/in/pedrooliv9"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>          | 
| <img src="https://avatars.githubusercontent.com/u/142221848?v=4" alt="foto de perfil" height="64px" width="64px">         |   Jonas Miguel |  Developer        | <a href="https://github.com/Jonasoliver"><img src="https://img.shields.io/badge/GitHub-13196a?style=for-the-badge&logo=github&logoColor=white">         | <a href="https://www.linkedin.com/in/jonas-miguel-ol"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>          |
| <img src="https://avatars.githubusercontent.com/u/142221532?v=4" alt="foto de perfil" height="64px" width="64px">         |   Renato Júnior |  Developer        | <a href="https://github.com/Renato-Cruz-Jr"><img src="https://img.shields.io/badge/GitHub-13196a?style=for-the-badge&logo=github&logoColor=white">         | <a href="https://www.linkedin.com/in/renato-fernandes-da-cruz-junior-798582204/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>         |
| <img src="https://avatars.githubusercontent.com/u/126177243?v=4" alt="foto de perfil" height="64px" width="64px">         |   Gustavo Castilho |  Developer        | <a href="https://github.com/GustavoCastilhoLucena"><img src="https://img.shields.io/badge/GitHub-13196a?style=for-the-badge&logo=github&logoColor=white">         | <a href="https://www.linkedin.com"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>         |
| <img src="https://avatars.githubusercontent.com/u/111767391?v=4" alt="foto de perfil" height="64px" width="64px">         |   Ivan Suiyama |  Developer        | <a href="https://github.com/IvanSuiyama"><img src="https://img.shields.io/badge/GitHub-13196a?style=for-the-badge&logo=github&logoColor=white">         | <a href="https://www.linkedin.com/in/ivan-silva-248042186/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>         |
| <img src="https://media.licdn.com/dms/image/D4D03AQECpQ1TjLb7mQ/profile-displayphoto-shrink_200_200/0/1696098623322?e=2147483647&v=beta&t=DLisI-vHChLbCiEQ88konsGhNkt2i_LQhYzaJjjEeg4" alt="foto de perfil" height="64px" width="64px">         |   Eduardo Namiuti  |  Developer        | <a href="https://github.com/eduardofsn"><img src="https://img.shields.io/badge/GitHub-13196a?style=for-the-badge&logo=github&logoColor=white">         | <a href="https://br.linkedin.com/in/eduardo-namiuti-5641b627b"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>         |

