# 💳 Sistema Bancário em Python

Este projeto é um sistema bancário simples desenvolvido em Python, utilizando conceitos de **Programação Orientada a Objetos (POO)** e **classes abstratas**. Ele permite a criação de clientes, contas correntes, depósitos, saques e visualização de extratos.

## 📁 Estrutura do Projeto

- `Cliente`: Classe base para clientes do banco.
- `PessoaFisica`: Subclasse de `Cliente`, representa pessoas físicas.
- `Conta`: Classe base para contas bancárias.
- `ContaCorrente`: Subclasse de `Conta`, com regras específicas de saque.
- `Historico`: Armazena transações realizadas.
- `Transacao`: Classe abstrata para operações bancárias.
  - `Deposito`: Subclasse que representa depósitos.
  - `Saque`: Subclasse que representa saques.

## 🧠 Funcionalidades

- Criar cliente (Pessoa Física)
- Criar conta corrente
- Realizar depósito
- Realizar saque (com limite de valor e quantidade)
- Exibir extrato
- Listar contas

## ▶️ Como Executar

1. Certifique-se de ter o Python instalado.
2. Salve o código em um arquivo, por exemplo `banco.py`.
3. No terminal, execute:

```bash
python banco.py
