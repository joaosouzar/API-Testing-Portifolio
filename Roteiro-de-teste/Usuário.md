# Usuário

### Base URL: https://dummyjson.com


### CT101 - Buscar usuário por id

Dados: usuário id 

Passos:

1. Enviar solicitação GET para "/user/id"


Resultado esperado:

- Status code: 200
- Json com dados do usuário 

---

### CT102 - Buscar todos os usuários

Passos:

1. Enviar solicitação GET para "/user"


Resultado esperado:

- Status code: 200
- Json com dados de todos usuários

---

### CT103 - Adicionar usuário

Passos:

1. Enviar solicitação POST para "/user/add"
2. Informar "firstName" do novo usuário
3. Informar "lastNmane" do novo usuário


Resultado esperado:

- Status code: 201
- Json com dados do novo usuário 

---

### CT104 - Adicionar usuário sem dados

Passos:

1. Enviar solicitação POST para "/user/add"
2. Não informar nenhum dado

Resultado esperado:

- Status code: 400
- Mensagem de erro "Unexpected end of JSON input"