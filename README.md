### Cadastro

POST /register<br/>
POST /signup<br/>
POST /users<br/>

`https://api-capstone-grupo1.herokuapp.com`<br/>
Espera-se:

```json
{
  "email": "email@mail.com",
  "password": "Senha123",
  "name": "User Teste",
  "img": "https://davidgabrieloliveira.gallerycdn.vsassets.io/extensions/davidgabrieloliveira/mussumipsum/1.0.0/1567042744450/Microsoft.VisualStudio.Services.Icons.Default",
  "pokemon": []
}
```

Espera um nome um email data senha e um pokemon inicial.

### Troca

Patch /users/id <br/>
`https://api-capstone-grupo1.herokuapp.com/users/{ID}`<br/>
Espera-se:

```json
{
  "pokemon": [
    {
      "name": "charmander",
      "status": 1
    }
  ]
}
```

Login
POST /login
POST /signin

```json
{
  "email": "email@mail.com",
  "password": "Senha123"
}
```

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"
