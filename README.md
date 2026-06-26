 # 🏦 Geek Bank - Sistema Bancário em Python

## 📖 Descrição

O **Geek Bank** é um sistema bancário simples desenvolvido em **Python** para execução via terminal. O projeto simula as principais operações de um caixa eletrônico (ATM), permitindo o gerenciamento de contas bancárias de forma prática.

O sistema utiliza programação orientada a objetos (POO), separando as responsabilidades entre clientes, contas e a aplicação principal.

---

## ✨ Funcionalidades

* ✅ Criar uma nova conta bancária
* 💰 Realizar depósitos
* 💸 Efetuar saques
* 🔄 Realizar transferências entre contas
* 📋 Listar todas as contas cadastradas

---

## 🛠 Tecnologias Utilizadas

* Python 3
* Programação Orientada a Objetos (POO)
* Type Hints (`typing`)
* Biblioteca padrão (`time`)

---

## ⚙️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/geek-bank.git
```

### 2. Entre na pasta do projeto

```bash
cd geek-bank
```

### 3. Execute o programa

```bash
python main.py
```

ou

```bash
python3 main.py
```

---

## 📌 Menu do Sistema

Ao iniciar o programa será exibido o seguinte menu:

```
================= ATM =================
============= Geek Bank ===============

1 - Criar Conta
2 - Efetuar Saque
3 - Efetuar Depósito
4 - Efetuar Transferência
5 - Listar Contas
6 - Sair do Sistema
```

---

## 🏦 Operações Disponíveis

### Criar Conta

Solicita as seguintes informações:

* Nome
* E-mail
* CPF
* Data de nascimento

Após o cadastro, uma nova conta é criada automaticamente.

---

### Depósito

Permite adicionar saldo à conta informando:

* Número da conta
* Valor do depósito

---

### Saque

Permite sacar um valor da conta, desde que haja saldo suficiente (conforme as regras implementadas na classe `Conta`).

---

### Transferência

Realiza uma transferência entre duas contas.

São solicitados:

* Conta de origem
* Conta de destino
* Valor da transferência

---

### Listar Contas

Exibe todas as contas cadastradas juntamente com seus dados.

---

## 📚 Conceitos Aplicados

Este projeto utiliza diversos conceitos importantes da linguagem Python:

* Programação Orientada a Objetos
* Classes
* Objetos
* Encapsulamento
* Listas
* Funções
* Tipagem estática com Type Hints
* Organização em módulos

---

## 📌 Dependências

Este projeto utiliza apenas bibliotecas nativas do Python.

Não é necessário instalar pacotes externos.

---

Este projeto é de uso livre para estudos e aprendizado.
