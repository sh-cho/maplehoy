## maplehoy / server

### Installation

```shell
brew install poetry
poetry install
```
Install [poetry](https://github.com/python-poetry/poetry) and setup virtualenv once, via poetry

```shell
poetry run pre-commit install
```

### Run

#### local
```shell
poetry run uvicorn main:app --reload
```
