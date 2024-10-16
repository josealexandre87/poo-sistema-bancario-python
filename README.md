# 🏦 Desafio: Modelando o Sistema Bancário em POO com Python

![Python](https://img.shields.io/badge/Python-3.12%2B-blue.svg) ![Status](https://img.shields.io/badge/Status-Completed-green) ![POO](https://img.shields.io/badge/POO-Aplicado-success) ![ABC](https://img.shields.io/badge/ABC-Aplicado-important)

Bem-vindo ao **Sistema Bancário em POO com Python**! Este projeto simula um sistema bancário utilizando Programação Orientada a Objetos (POO) para organizar melhor as funcionalidades de Depósito, Saque, Extrato e Gestão de Usuários.

## 📋 Funcionalidades

- 📥 **Depósito:** Adicione saldo à conta de um cliente.
- 💸 **Saque:** Realize saques respeitando limites diários e de saldo disponível.
- 📜 **Extrato:** Consulte o histórico de transações da conta.
- 🧑‍💼 **Novo de Usuário:** Registre novos clientes no sistema.
- 🏦 **Nova Conta Corrente:** Abra uma nova conta para clientes cadastrados.
- 📑 **Listar Contas:** Veja todas as contas correntes cadastradas.
- ❌ **Saída:** Encerre a operação do sistema.

## 🚀 Tecnologias Utilizadas

- **Python 3.12+** 🐍
  - Programação Orientada a Objetos (POO)
  - Decoradores: `@property`, `@classmethod`, `@abstractmethod`
  - **ABC** (Abstract Base Classes) para abstração de métodos
  - Manipulação de datas e horas com **datetime**
  - Controle de fluxo com **while**, **if-elif-else**
  - Manipulação de listas e controle de transações
  - Interação com o usuário via `input()` e exibição com `print()`

## 🎯 Objetivo

O projeto visa melhorar a implementação do sistema bancário utilizando POO e outras ferramentas avançadas do Python, como classes abstratas e manipulação de datas, proporcionando uma maior clareza e escalabilidade ao código. Desenvolvido como parte do exercício prático da Formação Python Funtamentals da DIO.

## 🛠️ Como Executar

1. Certifique-se de ter o **Python 3.12+** instalado.

2. Clone o repositório:
    
    ```bash
    git clone https://github.com/josealexandre87/poo-sistema-bancario-python.git
    ```

3. Acesse a pasta do projeto:
    
    ```bash
    cd poo-sistema-bancario-python
    ```

4. Execute o script:

    ```bash
    python extensao_desafio_poo_sistema_bancario-python.py
    ```
## 🖼️ Diagrama de Classes (UML)

![Diagrama UML](/diagrama_de_clases.png)

## 🎉 Exemplo de Execução

```bash
================ MENU ================
[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo usuário
[q] Sair

=> nu
Informe o nome do cliente: João Silva
Informe o CPF do cliente: 12345678900
Informe a data de nascimento (dd/mm/yyyy): 01/01/1985
Novo cliente cadastrado com sucesso!

=> nc
Informe o CPF do cliente: 12345678900
Conta corrente criada com sucesso!

=> d
Informe o valor do depósito: 500
Depósito de R$ 500.00 realizado com sucesso!

=> s
Informe o valor do saque: 200
Saque de R$ 200.00 realizado com sucesso!

=> e
================ EXTRATO ================
Depósito: R$ 500.00
Saque: R$ 200.00

Saldo Atual: R$ 300.00
=========================================

=> lc
Lista de Contas:
- Conta Corrente [Agência: 0001 | Número: 12345-6 | Titular: João Silva]

=> q
Sistema encerrado. Obrigado por utilizar nossos serviços!
```
