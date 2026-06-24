# Login

### Base URL: https://dummyjson.com


### CT001 - Login com credenciais válidas

Pré condição: Usuário cadastrado

Passos:

1. Enviar solicitação POST para "/user/login"
2. Informar usuário válido
3. Informar senha válida

Resultado esperado:

- Status code: 200
- Token retornado no corpo da resposta.

---

### CT002 - Login sem usuário

Pré condição: Usuário cadastrado

Passos:

1. Enviar solicitação POST para "/user/login"
2. Não Informar usuário
3. Informar senha válida

Resultado esperado:
- Status Code: 400
- Mensagem de erro apresentada "Username and password required".

---

### CT002 - Login com usuário inválido

Pré condição: Usuário cadastrado

Passos:

1. Enviar solicitação POST para "/user/login"
2. Informar usuário inválido
3. Informar senha válida

Resultado esperado:
- Status Code: 400
- Mensagem de erro apresentada "Invalid credentials".