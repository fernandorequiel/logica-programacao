# 🧮 Lógica de Programação - Calculadora em Python

Projeto desenvolvido durante o curso de **Lógica de Programação em Python**, com o objetivo de praticar conceitos fundamentais de programação, estruturação de código e execução de aplicações via terminal Linux.

---

## 📖 Sobre o Projeto

A aplicação consiste em uma **calculadora desenvolvida em Python**, capaz de realizar operações matemáticas básicas por meio da interação com o usuário pelo terminal.

Além do desenvolvimento em Python, o projeto utiliza um **script Shell (Bash)** para facilitar a execução da aplicação em ambientes Linux.

---

## 🚀 Tecnologias Utilizadas

* Python 3
* Shell Script (Bash)
* Linux (Ubuntu)
* Git
* GitHub

---

## ✨ Funcionalidades

A calculadora permite realizar as seguintes operações:

* ➕ Soma
* ➖ Subtração
* ✖️ Multiplicação
* ➗ Divisão
* ⚠️ Tratamento para divisão por zero
* 🔄 Menu interativo com execução contínua até o encerramento pelo usuário

---

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/fernandorequiel/logica-programacao.git
```

### 2. Acesse a pasta do projeto

```bash
cd logica-programacao
```

### 3. Conceda permissão de execução ao script

```bash
chmod 744 calculadora.sh
```

### 4. Execute a aplicação

```bash
./calculadora.sh
```

---

## 📁 Estrutura do Projeto

```text
logica-programacao/
├── calculadora.py
├── calculadora.sh
├── comandos.txt
└── README.md
```

---

## 📝 Explicação do Código

O programa solicita dois números ao usuário e apresenta um menu contendo as operações disponíveis.

Cada operação matemática foi implementada em uma função específica, tornando o código mais:

* Organizado
* Legível
* Fácil de manter
* Reutilizável

Após a execução do cálculo, o sistema pergunta se o usuário deseja realizar uma nova operação. Caso a resposta seja positiva, a aplicação continua em execução utilizando um laço de repetição (`while`). Caso contrário, o programa é encerrado.

---

## 📚 Conceitos Aplicados

Durante o desenvolvimento foram utilizados conceitos fundamentais de programação, como:

* Variáveis
* Funções
* Estruturas condicionais (`if`, `elif` e `else`)
* Laços de repetição (`while`)
* Entrada e saída de dados
* Operações matemáticas
* Tratamento de erros

---

## 💻 Exemplo de Utilização

```text
=== CALCULADORA ===

Digite o primeiro número: 55
Digite o segundo número: 5

Escolha uma operação:

1 - Soma
2 - Subtração
3 - Multiplicação
4 - Divisão

Opção: 1

Resultado: 60
```

---

## 🎯 Objetivo

Este projeto tem como finalidade consolidar os conhecimentos iniciais em programação utilizando Python, praticando lógica, organização de código e utilização de ferramentas de versionamento com Git e GitHub.
