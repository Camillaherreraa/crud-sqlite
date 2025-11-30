# CRUD SQLite – Ionic + Angular + Capacitor

Este projeto implementa um CRUD completo (Criar, Listar, Editar e Excluir) utilizando **SQLite**, **Ionic**, **Angular** e **Capacitor**.  
O objetivo é demonstrar a utilização do plugin **@capacitor-community/sqlite** para armazenamento local em dispositivos móveis.

Este repositório foi criado para atender aos requisitos da atividade solicitada, contendo:
- CRUD funcional com SQLite
- README.md
- TODO.md
- LICENSE (Creative Commons)
- Projeto Ionic completo na pasta raiz

---

## 🚀 Tecnologias utilizadas
- **Ionic Framework**
- **Angular**
- **Capacitor**
- **@capacitor-community/sqlite**
- **Typescript**

---

## 📱 Funcionalidades
- Criar novos usuários (nome e email)
- Listar usuários cadastrados
- Editar usuários
- Excluir usuários
- Banco de dados SQLite REAL em dispositivos móveis

> ⚠ No navegador (`ionic serve`), o SQLite não funciona nativamente.  
> Nessa plataforma, o projeto usa um *fallback em memória* apenas para fins de teste e visualização.  
> Em dispositivos Android/iOS o banco SQLite real é utilizado automaticamente.

---

## 📦 Estrutura do projeto
Os principais arquivos e diretórios são:

crud-sqlite/
│
├── src/
│ ├── app/
│ │ ├── home/
│ │ ├── pages/users/
│ │ ├── services/sqlite-service.ts
│ │ └── app-routing.module.ts
│ └── ...
│
├── README.md
├── TODO.md
├── LICENSE
└── package.json

## Como rodar o projeto

### 1️Instalar dependências
```bash
npm install

Rodar no navegador (modo desenvolvimento)
ionic serve

Esse modo usa armazenamento em memória.

3️Build para rodar em dispositivo
ionic build
npx cap sync

