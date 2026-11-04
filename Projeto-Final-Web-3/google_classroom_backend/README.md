# Classroom — Backend

API HTTP em Node.js para autenticação, usuários, turmas, atividades, respostas e avisos.

**Tecnologias:** Node.js e MySQL, com o pacote `mysql`.

## Executar

1. Crie o banco MySQL `googleclassroom`.
2. Ajuste a conexão em `databases/connections/mysql_connection.js`. As tabelas são criadas pelo código ao conectar.
3. Abra o terminal nesta pasta:

```powershell
npm install
node server.js
```

O servidor utiliza `http://localhost:3000`. Há exemplos de requisições HTTP em `requests`.

Os controladores utilizam as implementações de `databases/mysql_databases`. A pasta `databases/local_databases` contém implementações em memória que não estão selecionadas pelos controladores.

[Voltar ao projeto](../README.md)
