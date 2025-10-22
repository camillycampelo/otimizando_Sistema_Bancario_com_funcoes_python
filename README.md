# Otimizando o Sistema Bancário com Funções em Python

Este repositório apresenta uma evolução de um sistema bancário simples, originalmente desenvolvido para realizar operações de depósito, saque e consulta de extrato. Aqui, o foco é **modularizar** e **organizar** melhor o código, utilizando funções em Python para tornar o sistema mais legível, sustentável e extensível.

## Conteúdo

- `desafio.py` — Versão inicial após modularização.  
- `desafio2.py` — **Nova versão atualizada** com funcionalidades adicionais (ver detalhes abaixo).  
- `README.md` — Este arquivo de documentação.

## Funcionalidades da versão `desafio.py`

Na versão original (arquivo `desafio.py`):

- Operação **Depósito**: permite ao usuário depositar um valor na conta.  
- Operação **Saque**: permite ao usuário sacar valores, respeitando limite diário e saldo disponível.  
- Operação **Extrato**: consulta das movimentações (depósitos e saques) e do saldo atual.  
- Uso de funções para cada operação, visando melhor estruturação do código.

## Novidades da versão `desafio2.py`

O arquivo `desafio2.py` introduz melhorias e novas funcionalidades. Algumas das principais adições incluem:

1. **Cadastro de usuários** — Permite registrar novos clientes, armazenar dados básicos (nome, CPF, conta, etc).  
2. **Criação de conta vinculada a usuário** — Cada usuário pode ter uma ou mais contas, e a lógica agora diferencia usuário versus conta.  
3. **Listagem de contas** — Possibilidade de visualizar todas as contas criadas, associadas aos usuários.  
4. **Operações adaptadas a conta/usuário** — As operações de depósito, saque e extrato agora são realizadas considerando o usuário e a conta selecionada.  
5. **Melhorias de validação de entrada** — Verificação de dados (uso de CPF válido, conta existente, saldo suficiente, etc).  
6. **Registro de transações por conta** — Históricos de depósitos e saques são mantidos por conta, permitindo extratos específicos.  
7. **Limite de saques aprimorado** — A lógica de limite diário ou número de saques segue melhor estruturada (caso aplicável).  
8. **Documentação interna** — Comentários adicionais e estrutura de menu melhorada para navegação.

## Como usar

1. Clone o repositório:  
   ```bash
   git clone https://github.com/camillycampelo/otimizando_Sistema_Bancario_com_funcoes_python.git
