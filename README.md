# API-Rest-Vinho

API Rest full utilizada no projeto de conclusão do curso Entra21, da turma Vue.js, através da API era possível fazer o CRUD, encaminhar emails para os usuários que se cadastrassem para receber o "newsletter". O Frontend foi desenvolvido em Vue.js.
Foi utilizado o Prisma ORM para gerenciar facilmente o banco de dados, utilizando sua linguagem de consulta simples e intuitiva chamda Prisma Schema. Existem tabelas de relação 1-1, 1-n e n-n neste projeto.
O banco de dados utilizado foi o SQlite.

# Prismaa.bat

Arquivo criado para facilitar o inicio da instalação do Prisma, TypeScript, Express, Dotenv, Cors que foram utilizados no backend, através de comandos via terminal.

## Descrição

Esta API fornece endpoints para realizar várias operações, como autenticação, envio de e-mails, consulta de dados e muito mais.
Dentro da pasta SRC consta o Service (serviçõs de consultas criados para acessar e receber os dados do Banco de Dados) e Router(rotas criadas) utilizado para cada "tabela".
No diretório principal consta também um arquivo seed.ts para facilitar a introdução de dados iniciais ao banco de dados.

## Instalação

1. Certifique-se de ter o Node.js instalado na sua máquina.
2. Clone este repositório:
3. Navegue até o diretório do projeto: `cd api`
4. Instale as dependências: `npm install`

## Execução

Para executar a API em modo de desenvolvimento, use o comando: `npm run dev`

## Endpoints

Aqui está uma lista de alguns endpoints disponíveis:

- `/buscar-id-usuario-por-email`: Endpoint pesquisa de ID do usuário com base no email cadastrado.
- `/enviar-email`: Endpoint para enviar e-mails.
- `/api/country`: Endpoint para pesquisar os paises cadastrados.
- `/api/grape`: Endpoint para pesquisar as uvas cadastradas.
- `/api/harmony`: Endpoint para pesquisar as harmonias cadastradas.
- `/api/type`:Endpoint para pesquisar as uvas cadastradas.
- `/api/user`: Endpoint para pesquisar os usuários cadastrados.
- `/api/shopping`: Endpoint para pesquisar as compras cadastradas.
- `/api/review`: Endpoint para pesquisar os reviews cadastrados.
- `/api/wines`: Endpoint para pesquisar os vinhos cadastrados.

## Dependências

Esta API depende das seguintes bibliotecas:

- express: ^4.18.2
- cors: ^2.8.5
- dotenv: ^16.4.1
- nodemon: ^3.0.3

## Licença

Esta API está licenciada sob a [licença ISC](https://opensource.org/licenses/ISC).
