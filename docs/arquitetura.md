# 🏗️ Arquitetura do Sistema

## 📌 1. Visão Geral

Este documento descreve a arquitetura da aplicação desenvolvida no contexto do trabalho prático da disciplina de Engenharia de Software.

A solução proposta consiste em um sistema web para monitoramento de hábitos saudáveis, permitindo que usuários registrem e acompanhem informações relacionadas à sua saúde e bem-estar.

---

## ⚙️ 2. Tecnologias Escolhidas

As tecnologias foram selecionadas considerando facilidade de uso, conhecimento prévio e adequação ao projeto.

### 🔹 Backend

* Java
* Spring Boot
  Responsável pela implementação da lógica de negócio e disponibilização de uma API REST.

### 🔹 Frontend

* HTML
* CSS
* JavaScript
  Responsável pela interface com o usuário.

### 🔹 Banco de Dados

* PostgreSQL (ou MySQL)
  Responsável pelo armazenamento persistente dos dados.

---

## 🧠 3. Modelo Arquitetural

A aplicação segue uma arquitetura do tipo **cliente-servidor**, organizada em três camadas principais:

* **Camada de Apresentação (Frontend)**
  Responsável pela interação com o usuário.

* **Camada de Aplicação (Backend)**
  Responsável pelo processamento das requisições, regras de negócio e comunicação com o banco de dados.

* **Camada de Dados (Banco de Dados)**
  Responsável pela persistência das informações.

Essa separação promove melhor organização, manutenção e escalabilidade do sistema.

---

## 📊 4. Modelo C4

Para representação da arquitetura, foi utilizado o modelo C4, que permite visualizar o sistema em diferentes níveis de abstração.

---

### 🔹 4.1 Diagrama de Contexto (Nível 1)

Neste nível, o sistema é apresentado como uma caixa única, mostrando sua interação com atores externos.

**Elementos:**

* Usuário: interage com o sistema por meio da interface web
* Sistema de Monitoramento de Hábitos: aplicação desenvolvida
* Banco de Dados: responsável pelo armazenamento das informações

---

### 🔹 4.2 Diagrama de Containers (Nível 2)

Neste nível, o sistema é dividido em seus principais componentes internos.

**Containers definidos:**

* **Frontend (Aplicação Web)**
  Interface acessada pelo usuário via navegador

* **Backend (API REST)**
  Responsável pelo processamento das requisições

* **Banco de Dados**
  Responsável pelo armazenamento dos dados

---

## 🎯 5. Justificativa da Arquitetura

A arquitetura adotada foi escolhida pelos seguintes motivos:

* Separação clara de responsabilidades
* Facilidade de manutenção e evolução
* Baixo acoplamento entre componentes
* Facilidade de integração entre frontend e backend
* Adequação ao escopo do projeto

Além disso, o uso do modelo C4 permite uma melhor compreensão da estrutura do sistema, facilitando a comunicação e documentação.

---

## 🚀 6. Considerações Finais

A arquitetura proposta atende aos requisitos do sistema e permite sua evolução futura, possibilitando a inclusão de novas funcionalidades e melhorias sem grandes impactos na estrutura existente.
