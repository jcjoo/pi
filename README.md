# Sales Pro
## Estrutura dos sistema
O sistema será composto de um banco de dados, uma api, um painel web para configurações dos gestores e o um aplicativado mobile.
Tecnologias propostas:
- Mysql
- React
- Bun + Hono + DrizzleORM
- Java

![sistema](./diagramas/sistema.drawio.svg)

## Banco de dados
Banco de dados em MySQL utilizando estrutura de code frist com DrizzleORM.

### Diagrama conceitual

![er](./diagramas/db.drawio.svg)

### Diagrama ER

![er](./diagramas/er.drawio.svg)

### Dicionario de dados

![er](./diagramas/dbdict.drawio.svg)

## Componentes do sistema
### Exemplo

![exemplo](./diagramas/class.drawio.svg)

### [API](./api/README.md)

Api RESTfull em typescript utilizando Bun + Hono + DrizzleORM.

![api](./diagramas/class.api.drawio.svg)

### [Aplicação Web](./client/README.md)

Interface simplificada para gerenciamento do sistema utilizando React.

![client](./diagramas/class.client.drawio.svg)

### [Aplicativo](./app/README.md)

Aplicativo para android utilizando java.

![app](./diagramas/class.app.drawio.svg)



