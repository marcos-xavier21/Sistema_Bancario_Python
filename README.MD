
# 🏦 Sistema Bancário Simples em Python

Este repositório contém a simulação um sistema bancário simples implementado em Python. O sistema permite a criação de usuários e contas, além de realizar operações básicas como depósitos, saques e a exibição de extratos.

## 🚀 Funcionalidades

- **Depósito**: Permite adicionar fundos a uma conta bancária.
- **Saque**: Permite retirar fundos de uma conta, com verificação de limite e número máximo de saques por dia.
- **Extrato**: Exibe o histórico de transações e o saldo atual da conta.
- **Criação de Usuário**: Permite criar um novo usuário informando dados como CPF, nome e endereço.
- **Criação de Conta**: Associa uma nova conta a um usuário existente.
- **Listar Contas**: Exibe todas as contas criadas, incluindo agência, número da conta e nome do titular.

## 🛠️ Estrutura do Código

### Funções principais

- `menu()`: Exibe o menu de opções e solicita a escolha do usuário.
- `depositar(saldo, valor, extrato)`: Realiza depósitos e atualiza o saldo e o extrato.
- `sacar(saldo, valor, extrato, limite, numero_saques, limite_saques)`: Realiza saques com verificação de saldo, limite e número de saques.
- `exibir_extrato(saldo, extrato)`: Mostra o extrato das operações realizadas e o saldo atual.
- `criar_usuario(usuarios)`: Cria um novo usuário e armazena suas informações (CPF, nome, data de nascimento e endereço).
- `criar_conta(agencia, numero_conta, usuarios)`: Cria uma nova conta para um usuário existente.
- `listar_contas(contas)`: Lista todas as contas bancárias criadas.
- `filtrar_usuario(cpf, usuarios)`: Busca um usuário pelo CPF na lista de usuários.
- `main()`: Função principal que controla o fluxo do sistema, gerenciando as interações do usuário.

## 🔧 Como Executar

1. **Clone este repositório**:
   ```
   git clone https://github.com/marcos-xavier21/Sistema_Bancario_Python.git
   ```

2. **Navegue até o diretório do projeto**:
   ```
   cd sistema-bancario
   ```

3. **Execute o script Python**:
   ```
   python sistema_bancario.py
   ```

4. **Siga as instruções no menu** para realizar operações bancárias como depósitos, saques, criar usuários e listar contas.

## 📋 Funcionalidades no Menu

- **[d] Depositar**: Realiza um depósito em uma conta.
- **[s] Sacar**: Realiza um saque com verificação de saldo e limite.
- **[e] Extrato**: Exibe o extrato de todas as movimentações da conta.
- **[nc] Nova Conta**: Cria uma nova conta associada a um usuário existente.
- **[lc] Listar Contas**: Exibe todas as contas criadas.
- **[nu] Novo Usuário**: Cadastra um novo usuário no sistema.
- **[q] Sair**: Encerra o sistema.

## 📌 Observações

- **Limite de Saques**: O usuário pode realizar até 3 saques por dia, com um limite máximo de R$ 500,00 por saque.
- **Saldo Insuficiente**: O sistema não permite saques se o saldo da conta for insuficiente.
- **Validação de Dados**: O sistema valida a entrada de dados, como valor negativo para depósitos e saques.

---

**Desenvolvido por**: [Marcos Xavier](https://www.linkedin.com/in/marcos-s-xavier/)
```
