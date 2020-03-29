# Rotas/Recursos

# Métodos HTTP:
- **GET**: Buscar/listar uma informação do back-end
- **POST**: Criar uma informação no back-end
- **PUT**: Alterar uma informação no back-end
- **DELETE**: Deletar uma informação no back-end

# Tipos de parâmetros:
- **Query params**: parâmetros nomeados enviados na rota após o símbolo "?"", servem para filtros, paginação.
- **Route params**: parâmetros utilizados para identificar recursos.
- **Request Body**: corpo da requisição, utilizado para criar ou alterar

# Tipos de Banco de Dados:
- **SQL**: MySQL, SQLite, PostgreSQL, Oracle, Microsoft SQL Server.
- **NoSQL**: MongoDB, CouchDB, etc.

#### Driver:
* `SELECT * FROM users` 

#### Query Builders:
* `table('users').select('*').where()`