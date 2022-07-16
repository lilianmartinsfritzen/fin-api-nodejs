## FinAPI - API Financeira

---

### Requisitos

- [x] Deve ser posssível criar uma conta
- [x] Deve ser posssível buscar o extrato bancário do cliente (Inicialmente estamos passando cpf por Route Params para fins didáticos, mas nenhum dado sensível deve ser passado dessa forma)
- [x] Deve ser posssível realizar um depósito
- [x] Deve ser posssível realizar um saque
- [x] Deve ser posssível buscar o extrato bancário do cliente por data
- [x] Deve ser posssível atualizar dados da conta do cliente
- [] Deve ser posssível obter dados da conta do cliente
- [] Deve ser posssível deletar uma conta

---

### Regras de negócio

- [x] Não deve ser posssível cadastrar uma conta com CPF já existente
- [x] Não deve ser posssível buscar extrato em uma conta não existente
- [x] Não deve ser posssível fazer depósito em uma conta não existente
- [x] Não deve ser posssível fazer um saque em uma conta não existente
- [] Não deve ser posssível excluir uma conta não existente
- [] Não deve ser posssível fazer saque quando o saldo for insuficiente

___

### Itens de uma conta

- cpf -> string
- name -> string
- id -> uuid
- statement [...]

---