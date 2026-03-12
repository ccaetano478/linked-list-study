<p align="center">
  <img alt="Status" src="https://img.shields.io/badge/status-study%20project-blue">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-green">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white">
</p>

---

> 🇺🇸 English | [🇧🇷 Português](#versão-em-português)

---

## 🔗 Linked List

A singly linked list implementation in Java, built as a college exercise for a Data Structures course. The project simulates an employee registry system using a custom linked list — no built-in Java collections used.

> ⚠️ This is a study project and is not actively maintained.

### ✅ What was built

- [x] Custom `Node` and `NodeList` classes from scratch
- [x] Add employee to the beginning of the list (`addH`)
- [x] Add employee to the end of the list (`addE`)
- [x] Remove from the beginning (`removeH`) and end (`removeE`)
- [x] List all employees
- [x] Search employee by ID
- [x] Auto-generated random employee ID
- [x] Terminal menu interface

### ⚠️ Known limitations

- `searchEmployee` may throw `NullPointerException` if employee is not found
- `addE` calls `addH` internally when list is empty, causing `listSize` to increment twice
- Menu option 4 (Remove Employee) has no implementation
- Source files have encoding issues with special characters (accents)

### 🛠 Tech stack

- Java

### 🚀 How to run locally

```bash
# Clone the repository
git clone https://github.com/ccaetano478/linked-list-study.git

# Navigate to the folder
cd linked-list-study

# Compile
javac src/listaEncadeada/*.java -d out

# Run
java -cp out listaEncadeada.main
```

### 🎓 Context

Built during a Data Structures course in college. The goal was to understand how linked lists work internally by implementing one from scratch.

---

<h2 id="versão-em-português">🇧🇷 Versão em Português</h2>

## 🔗 Lista Encadeada

Implementação de uma lista encadeada simples em Java, desenvolvida como exercício de faculdade na disciplina de Estruturas de Dados. O projeto simula um sistema de cadastro de funcionários usando uma lista encadeada própria — sem usar as coleções nativas do Java.

> ⚠️ Este é um projeto de estudo e não está sendo ativamente mantido.

### ✅ O que foi desenvolvido

- [x] Classes `Node` e `NodeList` do zero
- [x] Adicionar funcionário no início da lista (`addH`)
- [x] Adicionar funcionário no final da lista (`addE`)
- [x] Remover do início (`removeH`) e do fim (`removeE`)
- [x] Listar todos os funcionários
- [x] Buscar funcionário por matrícula
- [x] Geração automática de matrícula aleatória
- [x] Menu interativo no terminal

### ⚠️ Limitações conhecidas

- `searchEmployee` pode lançar `NullPointerException` caso o funcionário não seja encontrado
- `addE` chama `addH` internamente quando a lista está vazia, fazendo `listSize` incrementar duas vezes
- Opção 4 do menu (Remover Funcionário) não tem implementação
- Arquivos com problema de encoding nos caracteres especiais (acentos)

### 🛠 Tecnologias

- Java

### 🚀 Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/ccaetano478/linked-list-study.git

# Acesse a pasta
cd linked-list-study

# Compile
javac src/listaEncadeada/*.java -d out

# Execute
java -cp out listaEncadeada.main
```

### 🎓 Contexto

Desenvolvido durante a disciplina de Estruturas de Dados na faculdade. O objetivo era entender como listas encadeadas funcionam internamente, implementando uma do zero.
