# 📚 Sistema de Gestão de Tarefas Acadêmicas — Full Stack

Sistema web completo para gerenciamento de tarefas acadêmicas, desenvolvido com **backend em Django + Django REST Framework** e **frontend em React**, simulando um cenário real de mercado com arquitetura desacoplada (API REST + SPA).

---

## 🎯 Problemática

Estudantes e professores enfrentam dificuldades para:

- Organizar tarefas e prazos  
- Acompanhar atividades concluídas e pendentes  
- Centralizar informações acadêmicas  

Este projeto resolve essas dores através de uma aplicação full stack moderna, segura e escalável.

---

# 🏗️ Arquitetura do Projeto

sistema-gestao-tarefas/
│
├── backend/ → API REST em Django
└── frontend/ → Interface web em React


- 🔗 Comunicação via API REST  
- 🔐 Autenticação JWT  
- ⚛️ Frontend desacoplado  
- 🗄️ Persistência com SQLite (ambiente de desenvolvimento)  

---

# 🖥️ Backend

## 🚀 Tecnologias Utilizadas

- 🐍 Django  
- 🔗 Django REST Framework  
- 🔐 JWT (JSON Web Token)  
- 🗄️ ORM do Django  
- 💾 SQLite  
- 🛡️ Sistema de permissões  
- 🔎 Filtros de consulta  
- 📄 Paginação  
- 📘 Documentação interativa com Swagger  

## 🔧 Funcionalidades

- Autenticação com geração de token JWT  
- CRUD completo de tarefas  
- Controle de acesso por usuário  
- Filtros por status e data  
- Paginação de resultados  
- Documentação interativa para testes  

---

# ⚛️ Frontend

## 🛠️ Tecnologias Utilizadas

- React  
- JavaScript  
- HTML5  
- CSS3  

## 🚀 Funcionalidades

- 🔐 Tela de login integrada com JWT  
- 🔄 Consumo da API Django  
- 📝 CRUD completo de tarefas  
- ⚛️ Gerenciamento de estado com `useState` e `useEffect`  
- 🔗 Arquitetura totalmente desacoplada  

---

# ▶️ Como Executar o Projeto Completo

## 1️⃣ Clonar o repositório

bash
git clone https://github.com/seu-usuario/sistema-gestao-tarefas.git
cd sistema-gestao-tarefas

## 2️⃣ Executar o Backend

cd backend

# Criar ambiente virtual
python -m venv venv

# Ativar ambiente virtual (Windows)
venv\Scripts\activate

# Instalar dependências
pip install -r requirements.txt

# Aplicar migrações
python manage.py migrate

# Executar servidor
python manage.py runserver

Backend disponível em:

http://127.0.0.1:8000/
3️⃣ Executar o Frontend

Em outro terminal:

cd frontend

# Instalar dependências
npm install

# Rodar aplicação
npm run dev

Frontend disponível em:

http://localhost:5173/


🔐 Fluxo de Autenticação

Usuário realiza login

Backend retorna token JWT

Frontend armazena token

Requisições autenticadas enviam token no header:

Authorization: Bearer <token>
📌 Conceitos Demonstrados

Arquitetura desacoplada (API + SPA)

Autenticação stateless com JWT

Controle de permissões por usuário

Organização modular de código

Estrutura preparada para escalar para PostgreSQL

Simulação de ambiente real de mercado

📈 Melhorias Futuras

Deploy em ambiente cloud (Render, Railway ou AWS)

Integração com PostgreSQL

Dockerização

Testes automatizados

Controle de papéis (Professor / Aluno)

Dashboard com métricas

👨‍💻 Autor

Nailton Rodrigues e Kaue Ferreira

Projeto desenvolvido para simular um cenário profissional full stack com integração entre backend Django e frontend React.
