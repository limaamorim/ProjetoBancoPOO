# Sistema Bancário em Python

Este é um **projeto de estudo** de um sistema bancário simples em Python, que permite:

- Criar usuários (clientes)
- Criar contas bancárias associadas a usuários
- Realizar depósitos e saques
- Consultar extrato bancário
- Listar contas cadastradas

O sistema foi desenvolvido em **Python puro**, utilizando listas e dicionários para armazenar informações. É uma versão **procedural**, sem uso de banco de dados ou orientação a objetos.

---

## Funcionalidades

1. **Depósito**
   - Adiciona um valor ao saldo da conta
   - Atualiza o extrato

2. **Saque**
   - Permite sacar valores respeitando limite diário e saldo disponível
   - Atualiza o extrato
   - Limite de saques por dia configurável

3. **Extrato**
   - Exibe todas as movimentações da conta
   - Mostra o saldo atual

4. **Novo usuário**
   - Cadastra um usuário com CPF, nome, data de nascimento e endereço
   - Verifica se o usuário já existe

5. **Nova conta**
   - Cria uma conta associada a um usuário existente
   - Cada conta tem número, agência e titular

6. **Listar contas**
   - Lista todas as contas cadastradas com seus titulares

---

## Como usar

1. Clone ou baixe este repositório:

```bash
git clone https://github.com/seuusuario/projeto-banco-python.git
