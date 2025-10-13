# Otimizando Sistema Bancário com Funções em Python 🏦

Este projeto aprimora uma implementação básica de sistema bancário em Python, extraindo funcionalidades em **funções** para tornar o código mais organizado, modular e reutilizável.

---

## 🔍 Estrutura do Repositório

- `desafio.py` — arquivo principal com a lógica do sistema bancário (menu, depósito, saque, extrato) implementada com funções.  
- `README.md` — este arquivo de documentação.  

---

## 🚀 Funcionalidades do Sistema

- Depósito de valores positivos  
- Saque com verificação de:
  - Saldo disponível  
  - Limite por operação  
  - Quantidade máxima diária de saques  
- Emissão de extrato com histórico das operações  
- Loop contínuo até o usuário optar por sair  

---

## 🛠 Detalhamento das Funções

- `depositar(saldo, valor, extrato)`: processa depósito, valida valor e retorna saldo + histórico atualizados  
- `sacar(saldo, valor, extrato, limite, numero_saques, limite_saques)`: gerencia as condições de saque e retorna os dados atualizados  
- `exibir_extrato(saldo, extrato)`: imprime o histórico de movimentações e o saldo atual  
- `menu()`: exibe o menu de opções e retorna a escolha do usuário  
- `main()`: controla o fluxo principal do programa  

---

## 📦 Como Executar

1. Clone este repositório:  
   ```bash
   git clone https://github.com/camillycampelo/otimizando_Sistema_Bancario_com_funcoes_python.git
