
#O que contem
 - Regras de negocio
 - Conexao BD - SQLite
 - Envio de e-mail
 

Packages instaladas (npm instal {package})
- express
- nodemon -D (somente para o ambiente de DEV)
- sqlite3 (Driver para o banco de dados)

#Comandos para o Knex
npx knex  (help)
npx knex init
npx knex migrate:latest
npx knex migrate:status (quais foram executadas)
npx knex migrate:rollback (volta a ultima)

#Comando para o Node
node index.js (subir servidor)