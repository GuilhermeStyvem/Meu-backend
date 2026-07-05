⚙️ Como rodar o projeto
Pré-requisitos
Python 3.8+ (Recomendado 3.10+)

Passo a passo
Bash
# 1. Clone o repositório
git clone [https://github.com/GuilhermeStyvem/Meu-backend.git](https://github.com/GuilhermeStyvem/Meu-backend.git)
cd Meu-backend

# 2. Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows

# 3. Instale as dependências
pip install -r requeriments.txt

# 4. Rode a API
uvicorn main:app --reload
Após iniciar, a API estará rodando localmente em http://127.0.0.1:8000.
Você pode testar os endpoints acessando a documentação interativa (Swagger UI) gerada automaticamente pelo FastAPI em:
👉 http://127.0.0.1:8000/docs

🔐 Autenticação (JWT)
O sistema conta com um fluxo de autenticação onde:

O usuário envia credenciais válidas.

A API retorna um Token JWT.

O token deve ser enviado nos cabeçalhos (Authorization: Bearer <token>) para acessar rotas protegidas.

🛠️ Tecnologias utilizadas
FastAPI — Framework web moderno e rápido para construção de APIs em Python

JWT (JSON Web Tokens) — Padrão de mercado para autenticação segura

Pydantic — Validação e tipagem de dados (via schemas.py)

Uvicorn — Servidor ASGI ultrarrápido para rodar a aplicação
"""

Escrevendo no arquivo .txt
file_path = "README_Meu_Backend.txt"
with open(file_path, "w", encoding="utf-8") as file:
file.write(content)

print(f"Arquivo gerado: {file_path}")

Aqui está o conteúdo do README em um ficheiro de texto, conforme pediste!

O teu ficheiro TXT está pronto
[file-tag: code-generated-file-0-1783215273500599518]

Se precisares de mais alguma alteração ou ajuste, é só avisar.
