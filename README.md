```sh
# настройка окружения
python3.10 -m venv venv
source venv/bin/activate
python -m pip install --upgrade pip
python -m pytest tests/test_api.py
```

```sh
# запуск тестов
python -m pytest tests/test_api.py
```