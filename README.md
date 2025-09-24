📌 CRUD Flask - Gerenciamento de Tarefas

Um CRUD simples de tarefas usando Flask, SQLAlchemy e Marshmallow, organizado em módulos para facilitar manutenção e crescimento.

📂 Estrutura do Projeto
meu-crud/
│
├── app.py              # inicialização da aplicação Flask
├── extensions.py       # inicialização das extensões (SQLAlchemy, etc)
├── models.py           # modelos do banco de dados
├── routes.py           # rotas da API (CRUD)
├── schemas.py          # validação e serialização (Marshmallow)
├── tasks.db            # banco SQLite (gerado automaticamente)
│
├── templates/
│   └── index.html      # página inicial (frontend simples)
│
└── static/
    └── style.css       # estilos da interface

🚀 Como Rodar o Projeto
1. Clone o repositório
git clone https://github.com/seu-usuario/meu-crud.git
cd meu-crud

2. Crie e ative um ambiente virtual
python -m venv venv
# Ativar no Windows (PowerShell)
venv\Scripts\activate
# Ativar no Linux/Mac
source venv/bin/activate

3. Instale as dependências
pip install flask flask-sqlalchemy flask-cors marshmallow

4. Rode a aplicação
python app.py


O servidor Flask iniciará em:
👉 http://127.0.0.1:5000

📌 Endpoints da API
Método	Rota	Descrição
GET	/tasks	Lista todas as tarefas
GET	/tasks/<id>	Busca uma tarefa pelo ID
POST	/tasks	Cria uma nova tarefa
PUT	/tasks/<id>	Atualiza uma tarefa existente
DELETE	/tasks/<id>	Deleta uma tarefa
📍 Exemplo de JSON para criação de tarefa (POST /tasks)
{
  "title": "Estudar Flask",
  "description": "Aprender a criar APIs com Flask",
  "done": false
}

🎨 Frontend simples

Você pode abrir http://127.0.0.1:5000
 no navegador para visualizar uma interface simples em HTML/CSS.

🔧 Tecnologias usadas

Flask
 - Framework web

Flask-SQLAlchemy
 - ORM para banco de dados

Marshmallow
 - Validação/serialização

Flask-CORS
 - Suporte a requisições de outros domínios

📜 Licença

Este projeto é open-source e pode ser usado livremente para estudos.# crud-to-do
A short project made for practice
