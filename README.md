# Projeto CaquiCanela E-commerce

Este repositório contém o código-fonte completo do **CaquiCanela**, um e-commerce de roupas femininas desenvolvido como parte do projeto de extensão do curso de Análise e Desenvolvimento de Sistemas da Católica SC.  
O sistema foi criado para atender às necessidades da empresa **CaquiCanela**, que trabalha com revenda de roupas femininas, oferecendo uma plataforma moderna, intuitiva e segura para suas clientes.

# Telas

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ba324081-cc99-4016-8e92-cfaf154b1e34" />
<img width="1920" height="1080" alt="image2" src="https://github.com/user-attachments/assets/0566659a-eca2-4da6-add8-f0a957eb2e9b" />
<img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/c3c06e8c-6a6d-4f60-8a56-31f934eefcb6" />
<img width="1920" height="1080" alt="4" src="https://github.com/user-attachments/assets/fdfa4bc0-86e0-4fa6-aac1-e6f466700f55" />
<img width="1920" height="1080" alt="5" src="https://github.com/user-attachments/assets/3bf99f97-ba95-4bcf-a78a-c009da356ec4" />
<img width="1920" height="1080" alt="6" src="https://github.com/user-attachments/assets/1f87b0f3-a0c6-4309-80b2-b8e0c6766555" />
<img width="1920" height="1080" alt="7" src="https://github.com/user-attachments/assets/9588e7a3-b874-4db7-b857-698f2e24299d" />

---

## Estrutura do Projeto

Este é um **monorepo** que contém as duas aplicações separadas:

```
/
├── /backend/       (Servidor Node.js + Express + Sequelize)
└── /frontend/      (Cliente React + Vite + Tailwind CSS)
└── README.md       (Você está aqui)
```

### Tecnologias Utilizadas

**Backend**
- Node.js  
- Express  
- Sequelize (ORM)  
- MySQL  
- JWT + Bcrypt  
- Dotenv  

**Frontend**
- React  
- Vite  
- Tailwind CSS  
- Axios  
- React Router DOM  

---

## Como Rodar o Projeto Localmente

Você precisará ter o **Node.js (v18 ou superior)** e o **MySQL** instalados.

Para rodar o projeto completo, abra **dois terminais separados** — um para o backend e outro para o frontend.

---

### 1. Rodando o Backend (API)

No primeiro terminal:

```bash
# 1. Navegue até a pasta do backend
cd backend

# 2. Instale as dependências (apenas na primeira vez)
npm install

# 3. Inicie o servidor
npm start
```

O backend estará disponível em **http://localhost:3000**

---

### 2. Rodando o Frontend (Loja)

No segundo terminal:

```bash
# 1. Navegue até a pasta do frontend
cd frontend

# 2. Instale as dependências (apenas na primeira vez)
npm install

# 3. Inicie o cliente React
npm run dev
```

O frontend estará disponível em **http://localhost:5173**  
(o Vite pode escolher outra porta, verifique no terminal).

O frontend se conecta automaticamente à API em **http://localhost:3000**.

