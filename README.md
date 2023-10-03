### Passo a passo

- Copie e cole os arquivos dentro de `/test` para o repositório do aluno.

- Mude o pool de conexão do banco de dados dele para o formato abaixo:
```js
const pool = new Pool({
    host: "postgres-db",
    port: 5432,
    user: "postgres",
    password: "postgres",
    database: "dindin",
});
```

- Mova o `dump.sql` para a raiz do repositório do aluno, renomeie o arquivo se precisar.

- Mude a porta do servidor express para 3000

- Rode `docker-compose up --build` no terminal dentro da raíz do repositório do aluno.