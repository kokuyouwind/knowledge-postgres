# knowledge-postgres

docker-compose for [knowledge](https://support-project.org/knowledge_info/index)
with postgres database

# setup

Clone this repository, then run `docker-compose up -d` and access `http://localhost/` 

Login admin and access setting page, then fill up form:

- driver class: `org.postgresql.Driver(9.3-1103-jdbc41)`
- URL: `jdbc:postgresql://postgres:5432/postgres`
- user: `postgres`
- password: `postgres`
- schema: `postgres`
