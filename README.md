<h1 align="center">
    <img alt="NextLevelWeek" title="#NextLevelWeek" src="https://camo.githubusercontent.com/8c13dc2618dbd7f76d1d574350b98fdee1335ce5/68747470733a2f2f726f636b6574736561742d63646e2e73332d73612d656173742d312e616d617a6f6e6177732e636f6d2f626f6f7463616d702d6865616465722e706e67" width="250px" />
</h1>

# :ledger: GoStack Bootcamp - Challange #9 - TypeORM Relations

Project purpose: https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-database-relations

## :rocket: Technologies
This project was developed with the following technologies:
- NodeJS
- Jest
- Yarn
- Docker
- Postgres Database

## :runner: Running

```bash
# Clone this repository
git clone https://github.com/estevaolucena/typeorm-relations.git

# Go into the project folder
cd typeorm-relations

# Install dependencies
yarn install

# Create a docker container for Postgres database
docker run --name gostack-postgres -e POSTGRES_PASSWORD=root -p 5432:5432 -d postgres

# Create a database with the following name
gostack_desafio09

# Run the project
yarn dev:server

# For run the tests suits
# Create a new database with the following name
gostack_desafio09_tests

# Run the test suit
yarn test
```


Made with ♥ by Estevão Lucena :wave: [Get in touch!](https://www.linkedin.com/in/estevaolucena/)
