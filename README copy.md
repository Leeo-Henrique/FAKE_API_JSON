### Cadastro

POST /register<br/>
POST /signup<br/>
POST /users<br/>

Espera-se: 
```json
{
  "email": "email@mail.com",
  "password": "Senha123",
  "name": "User Teste",
  "age": 25,
  "pokemon": []
}
```

Espera um nome um email data senha e um pokemon inicial.

Login
POST /login
POST /signin
```json
{
  "email": "email@mail.com",
  "password": "Senha123",
}
```

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"
