# Task Manager

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)

Учебный консольный менеджер задач, разработанный в рамках практических работ по дисциплине «Программная инженерия».

## Стек технологий

- Python 3.11
- pytest
- argparse
- Git
- GitHub

## Установка

```bash
git clone <URL_РЕПОЗИТОРИЯ>
cd task-manager

python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
```

## Использование

После реализации CLI приложение можно будет запускать следующими командами:

```bash
python src/main.py add "Название задачи"
python src/main.py list
```

## Структура проекта

```text
task-manager/
├── src/                 # исходный код
├── tests/               # автоматические тесты
├── docs/                # документация
├── .gitignore
├── .tool-versions       # версия Python для asdf
├── LICENSE
├── README.md
└── requirements.txt
```

## Лицензия

Проект распространяется под лицензией MIT.
