# Projeto Final — C216 Sistemas Distribuídos (API REST/CRUD)

Projeto final da disciplina **C216 — Sistemas Distribuídos**: implementação de uma **API REST** com **CRUD** usando **Flask**, persistência com **SQLAlchemy** e **MySQL** (via **PyMySQL**), além de um frontend simples em **HTML** consumindo os endpoints. O ambiente é **containerizado com Docker** para facilitar execução e reprodutibilidade.

---

## ✨ Funcionalidades
- API **REST** com endpoints HTTP (GET/POST/PUT/PATCH/DELETE)
- Operações **CRUD** (Create, Read, Update, Delete)
- Persistência em **MySQL** com **SQLAlchemy**
- Serialização de dados (**dict → JSON**) para respostas da API
- **CORS** habilitado com `Flask-CORS` para permitir consumo por front em outra porta/domínio
- Execução via **Docker** (e opcionalmente `docker compose`)

---

## 🧰 Tecnologias
- **Flask**
- **Flask-CORS**
- **SQLAlchemy**
- **MySQL** + **PyMySQL**
- **Docker**
- **HTML** (front simples)
- **JSON** (troca de dados API)

---

## 🧠 O que é CORS (bem rápido)
**CORS** (Cross-Origin Resource Sharing) é uma política do navegador que bloqueia requisições do front para uma API em **outro domínio/porta** (ex.: `localhost:5500` chamando `localhost:5000`).  
O `Flask-CORS` adiciona os headers necessários para permitir essas chamadas de forma controlada.

---

## 🚀 Como executar com Docker
