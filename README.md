
## Projeto DIO Vivo

Desenvolvendo uma API com FastAPI, Python e Docker.
Modelo do projeto seguindo o modelo do MER dentro do projeto

Não foi utilizado o MakeFile pois foi desenvolvido em Windows

## para rodar o projeto:

uvicorn workout_api.main:app --reload


## para gerar o alembic:
alembic revision  --autogenerate -m "comentarios"
alembic upgrade head
