# Sales Pro

## Estrutura dos sistema

O sistema será composto de um banco de dados, uma api, um painel web para configurações dos gestores e o um aplicativado mobile.
Tecnologias propostas:

- Mysql
- React, React Native, Java ou Kotlin
- Bun + Hono + DrizzleORM

![sistema](./.diagramas/sistema.drawio.svg)

## Banco de dados

Banco de dados em MySQL utilizando estrutura de code frist com DrizzleORM.

### Diagrama conceitual

![er](./.diagramas/db.drawio.svg)

### Diagrama ER

![er](./.diagramas/er.drawio.svg)

### Dicionario de dados

![er](./.diagramas/dbdict.drawio.svg)

## Componentes do sistema

### [API](./api/README.md)

Api RESTfull em typescript utilizando Bun + Hono + DrizzleORM.

![api](./.diagramas/class.api.drawio.svg)

### [Client](./client/README.md)

Interface do sistema

![client](./.diagramas/class.client.drawio.svg)
