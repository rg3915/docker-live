# docker-live

Live de introdução ao Docker com @gomex

## Este projeto foi feito com:

* [Python 3.8.2](https://www.python.org/)
* [Django 2.2.16](https://www.djangoproject.com/)

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

```
git clone https://github.com/rg3915/docker-live.git
cd docker-live
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```

Rodando a aplicação

```
python manage.py runserver
```