# Produtos

### Base URL: https://dummyjson.com


### CT301 - Adicionar produto

Passos:

1. Enviar solicitação POST para "/produtos/add"
2. Informar dados do produto

Resultado esperado:

- Status code: 201
- Json com dados do produto

---

### CT302 - Buscar todos os produto

Passos:

1. Enviar solicitação GET para "/produtos"

Resultado esperado:

- Status code: 200
- Json com lista de todos os produtos

---

### CT303 - Buscar produto por id

Passos:

1. Enviar solicitação GET para "/produtos/id"

Resultado esperado:

- Status code: 200
- Json com dados do produto
