### Todas collections testadas

<img width="1916" height="987" alt="image" src="https://github.com/user-attachments/assets/12fa97a1-64ba-4f39-b755-7142f66d8168" />

- Mínimo 12 commits no projeto no usuário do aluno -> 0K
- Endpoints públicos GET /products e GET /products/{id} funcionam sem necessidade de login -> OK
- Endpoint de login funcionando e retornando o token de acesso -> OK
- Endpoints privados de produto (POST/PUT/DELETE) funcionam somente para usuário ADMIN -> OK
- Endpoint GET /users/me retorna usuário logado -> OK
- Endpoints GET /orders/{id} e POST /orders funcionando -> OK
- Usuário que não é ADMIN não consegue acessar pedido que não é dele em GET /orders/{id} -> OK
- Endpoint GET /categories deve ser público e retornar todas categorias -> OK
