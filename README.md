<h1 align="center"> 🚀 Meu Backend - API com FastAPI & JWT </h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/JWT-Security-black?style=flat&logo=json-web-tokens" alt="JWT">
</p>

<br>

> 💡 **Sobre o projeto:** Um backend robusto e modularizado construído em Python, focado em segurança e alta performance com autenticação via tokens JWT.

---

## 🎯 Funcionalidades

- 🔒 **Autenticação Segura:** Geração e validação de tokens JWT.
- ⚡ **Alta Performance:** Construído com FastAPI e Uvicorn.
- 🗂️ **Modularidade:** Código organizado por responsabilidades (rotas, modelos, schemas).
- 📖 **Documentação Automática:** Swagger UI integrado nativamente.

## 📁 Arquitetura do Projeto

```text
Meu-backend/
├── main.py             # Ponto de entrada da API
├── auth.py             # Lógica de autenticação e tokens JWT
├── database.py         # Conexão e configuração do banco de dados
├── models.py           # Modelos de banco de dados
├── schemas.py          # Schemas do Pydantic (validação de dados)
├── routers.py          # Endpoints da aplicação
└── requeriments.txt    # Dependências do projeto


🚀 Como Executar
1️⃣ Pré-requisitos
Certifique-se de ter o Python 3.8+ instalado na sua máquina.

2️⃣ Passo a passo
Clone o repositório e acesse a pasta:

Bash
git clone [https://github.com/GuilhermeStyvem/Meu-backend.git](https://github.com/GuilhermeStyvem/Meu-backend.git)
cd Meu-backend
Crie e ative o ambiente virtual:

Bash
# No Windows
python -m venv venv
venv\Scripts\activate

# No Linux/Mac
python -m venv venv
source venv/bin/activate
Instale as dependências:

Bash
pip install -r requeriments.txt
Inicie o servidor local:

Bash
uvicorn main:app --reload
3️⃣ Testando a API
Com o servidor rodando, acesse a documentação interativa pelo seu navegador:
👉 http://127.0.0.1:8000/docs

🛠️ Stack de Tecnologias
FastAPI - Framework web moderno e rápido.

Pydantic - Validação estrutural de dados.

Uvicorn - Servidor ASGI ultrarrápido.

PyJWT - Padrão de mercado para tokens.
