## FinAPI - API Financeira

---

### Requisitos

- [x] Deve ser posssível criar uma conta
- [x] Deve ser posssível buscar o extrato bancário do cliente
- [x] Deve ser posssível realizar um depósito
- [x] Deve ser posssível realizar um saque
- [x] Deve ser posssível buscar o extrato bancário do cliente por data
- [x] Deve ser posssível atualizar dados da conta do cliente
- [x] Deve ser posssível obter dados da conta do cliente
- [x] Deve ser possível deletar uma conta
- [x] Dever ser possível retornar o balance

---

### Regras de negócio

- [x] Não deve ser posssível cadastrar uma conta com CPF já existente
- [x] Não deve ser posssível buscar extrato em uma conta não existente
- [x] Não deve ser posssível fazer depósito em uma conta não existente
- [x] Não deve ser posssível fazer um saque em uma conta não existente
- [x] Não deve ser posssível fazer saque quando o saldo for insuficiente
- [x] Não deve ser posssível excluir uma conta não existente

___

### Itens de uma conta

- cpf -> string
- name -> string
- id -> uuid
- statement [...]

---