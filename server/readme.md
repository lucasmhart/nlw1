# Comands
```
# iniciar a aplicação
npm run dev
```

# Requests

* Request param: Parâmetros que vem na própria rota que identificam um recurso
* Query param: Parâmetros que vem na própria rota, geralmente opcionais para fltros e paginações
* Request body: Parâmetros para criação/atualização de informações

# Migrations
```
# Run migrations
npx knex migrate:latest --knexfile knexfile.ts migrate:latest
```