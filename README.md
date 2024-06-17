Baseado em: https://fastapidozero.dunossauro.com/01/

- O que instalar no Window?
-- Python
-- Pyenv: Shim gerenciador de dependencias do windows
-- Poetry: gerenciar os pacotes e seu ambiente virtual 

-- poetry shell : Ativa o ambiente virtual de um projeto com poetry
-- fastapi dev fast_zero/app.py: usando o fastapi e seu metodo para inicializar o app

http[protocolo]://127.0.0.1[endereco]:8000[porta]
-- Uvicorn: Servidor para disponibilizar o fastapi

poetry add --group dev pytest pytest-cov taskipy ruff httpx

Para os testes:
--  Arrange, Act, Assert (AAA)