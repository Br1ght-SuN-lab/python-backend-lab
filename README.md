# python-backend-lab

Домашние работы по курсу «Backend-разработка на Python» (НИС, НИУ ВШЭ, БПИ254).

Каждая домашка — отдельная директория в корне репозитория.

| ДЗ | Директория | Описание |
|----|------------|----------|
| 1 | `hw1-python-practice/` | Практика на Python: модели и утилиты, юнит-тесты |

## Запуск тестов

Linux / macOS — из директории домашки:

```shell
make setup
make test
```

Windows — там же, вручную (Makefile курса рассчитан на `venv/bin`):

```shell
python -m venv venv
venv\Scripts\pip install -r requirements.txt
venv\Scripts\pytest
```
