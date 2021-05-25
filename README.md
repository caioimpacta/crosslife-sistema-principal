# Crosslife Sistema Principal
Sistema principal para fazer o gerenciamento da academia crosslife de suzano. 
Onde construimos uma REST API com Flask e usamos as seguintes ferramentas
* Flask
* dynaconf
* CORS
* flask_restful
* flask_sqlalchemy
* flask_marshmallow
* marshmallow_sqlalchemy
* flask-jwt-extended

## Preparando o ambiente
```
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Rodando o projeto
```
FLASK_APP = "crosslife/app.py"
FLASK_ENV=Development
flask run
```
