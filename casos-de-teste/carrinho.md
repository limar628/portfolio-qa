  # Casos de teste: carrinho de compras

## CT-02 – Quantidade acima do máximo permitido

- **Objetivo:** Validar se o sistema impede que o usuário adicione mais de 10 unidades de um produto ao carrinho.
- **Pré-condição:** Usuário possui um produto adicionado ao carrinho.
- **Dados de teste:**
  - Quantidade atual: 1
  - Quantidade informada: 11
  - Limite máximo permitido: 10

- **Passos:**
  1. Abrir o carrinho de compras.
  2. Localizar o campo Quantidade do produto.
  3. Informar 11 unidades.
  4. Clicar em "Atualizar".

- **Resultado esperado:** O sistema deve recusar a quantidade informada, manter a quantidade dentro do limite de 10 unidades e exibir uma mensagem informando que a quantidade máxima
 permitida é 10 unidades.