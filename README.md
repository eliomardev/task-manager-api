# 🚀 Task Manager Full Stack

Um sistema completo de gerenciamento de tarefas desenvolvido com Python (FastAPI), PostgreSQL e JavaScript, totalmente hospedado na nuvem com tecnologias gratuitas.

## ✨ **Funcionalidades**

### 🔧 **Backend (API Python FastAPI)**
- ✅ **CRUD completo** de tarefas (Create, Read, Update, Delete)
- ✅ **Autenticação** via tokens JWT (opcional)
- ✅ **Validação de dados** com Pydantic
- ✅ **CORS configurado** para frontend
- ✅ **Documentação automática** com Swagger UI
- ✅ **Conectado a banco PostgreSQL** na nuvem

### 🎨 **Frontend (HTML/CSS/JS)**
- ✅ **Interface moderna e responsiva**
- ✅ **Adicionar novas tarefas** com título e descrição
- ✅ **Listar todas as tarefas** com status visual
- ✅ **Marcar/desmarcar** tarefas como concluídas
- ✅ **Editar tarefas** existentes em modal
- ✅ **Excluir tarefas** com confirmação
- ✅ **Status do sistema** em tempo real
- ✅ **Design responsivo** para mobile e desktop

### 🗄️ **Banco de Dados**
- ✅ **PostgreSQL** hospedado no Neon.tech
- ✅ **Tabela de tarefas** com campos: id, título, descrição, status, data
- ✅ **Persistência de dados** entre sessões
- ✅ **Backup automático** pela plataforma

## 🛠️ **Tecnologias Utilizadas**

### **Backend**
- ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) **FastAPI** - Framework web moderno
- ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) **PostgreSQL** - Banco de dados relacional
- **SQLAlchemy** - ORM para Python
- **Databases** - Async database support
- **Pydantic** - Validação de dados

### **Frontend**
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) **HTML5** - Estrutura da página
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) **CSS3** - Estilização moderna
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) **JavaScript** - Interatividade
- **Font Awesome** - Ícones

### **DevOps & Cloud**
- ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) **Docker** - Containerização
- ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white) **GitHub** - Versionamento
- ![Render](https://img.shields.io/badge/Render-46E3B7?logo=render&logoColor=black) **Render.com** - Hospedagem da API (free tier)
- ![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white) **Vercel** - Hospedagem do frontend
- **Neon.tech** - PostgreSQL gratuito na nuvem

## 🎯 **O Que Este Projeto Demonstra**

1. **Arquitetura Full Stack** completa
2. **Integração entre frontend, backend e banco de dados**
3. **Deploy em múltiplos serviços cloud gratuitos**
4. **Containerização com Docker**
5. **API RESTful bem estruturada**
6. **Frontend responsivo sem frameworks**
7. **CI/CD básico com deploys automáticos**

## 📁 **Estrutura do Projeto**

task-manager-fullstack/
├── backend/ # API Python FastAPI
│ ├── main.py # Endpoints da API
│ ├── database.py # Conexão com PostgreSQL
│ ├── requirements.txt # Dependências Python
│ └── Dockerfile # Containerização
├── frontend/ # Interface web
│ ├── index.html # Estrutura HTML
│ ├── style.css # Estilos CSS
│ ├── script.js # Lógica JavaScript
│ └── assets/ # Imagens/ícones
├── docker-compose.yml # Orquestração Docker
└── README.md # Esta documentação
