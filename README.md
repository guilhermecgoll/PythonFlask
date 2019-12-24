# PythonFlask

Projeto direcionado para implementações e testes em Python com o framework Flask.

## 1 - Criar o ambiente virtual

Crie um ambiente virtual através do comando abaixo:
```
python -m venv .venv
```

Em seguida, ative o mesmo:
```
.\.venv\Scripts\activate
```

## 2 - Instalação das dependências

Executar o comando abaixo no terminal:
```
pip install flask
```
Este comando se encarregará de instalar as dependências necessárias para executar os projetos

## 3 - Iniciando um app

Primeiramente é necessário criar uma variável de ambiente com o nome do arquivo apontado como "principal" da aplicação. Exemplo:
```
set FLASK_APP=hello.py
```

O comando abaixo permite que a aplicação seja executada em modo DEBUG:
```
FLASK_ENV=development
```

Em seguida, para executar a aplicação:
```
flask run
```