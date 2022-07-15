## FinAPI - API Financeira

---

### Requisitos

- [] Deve ser posssível criar uma conta
- [] Deve ser posssível buscar o extrato bancário do cliente
- [] Deve ser posssível realizar um depósito
- [] Deve ser posssível realizar um saque
- [] Deve ser posssível buscar o extrato bancário do cliente por data
- [] Deve ser posssível atualizar dados da conta do cliente
- [] Deve ser posssível obter dados da conta do cliente
- [] Deve ser posssível deletar uma conta

---

### Regras de negócio

- [] Não deve ser posssível cadastrar uma conta com CPF já existente
- [] Não deve ser posssível fazer depósito em uma conta não existente
- [] Não deve ser posssível buscar extrato em uma conta não existente
- [] Não deve ser posssível fazer um saque em uma conta não existente
- [] Não deve ser posssível excluir uma conta não existente
- [] Não deve ser posssível fazer saque quando o saldo for insuficiente

___

### Itens de uma conta

- cpf -> string
- name -> string
- id -> uuid
- statement []

---