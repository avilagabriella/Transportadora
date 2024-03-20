# 🚚 Transportadora 🚚
## Projeto Full Stack de uma Transportadora mvc.

- MVC (Modal View Controller)
- CRUD (Create Read Update Delete)
- API (Aplication Programing Interface)
- Testes unitários

## `Tecnologias:`
- [XAMPP](https://www.apachefriends.org/pt_br/index.html), MYSQL, MariaDB - Banco de dados Relacional
- [NodeJS](https://nodejs.org/en) Framework para desenvolvimento back-End
- [Vs Code](https://code.visualstudio.com) IDE (Ambiente Integrado de desenvolvimento)
- [Insomnia](https://app.insomnia.rest/app/organization/create) Ferramenta para testes unitários da API BackEnd

## `Dependências:`
- mysql
- express
- cors
 
## `Como testar:`
- 1 Faça download deste repositório
- 2 Abra com VsCode
- 3 Abra um terminal cmd ou bash
- 4 Navegue até a pasta ./api e instale as dependências usando npm e execute com nodemon ou node

  ```
  cd api
  npm i
  ```
 - 5 Abra o XAMPP e clique em Start nos serviços Apache e MySQL, depois abra o Shell e acesse o MariaDB.

    ```
    mysql -u root
     ```
 - 6 Copie o script de criação do banco de dados e cole no shell do MariaDB (./bd/script.sql), copie também os dados de teste que estão na pasta (./testes/populacaobd.sql)
 - 7 Abra o insomnia e importe o arquivo de teste (./teste/insomnia.json)
 

