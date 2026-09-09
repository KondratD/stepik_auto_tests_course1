Создание виртуальное окружение:
cd /home/user_name/repositories_name

python3 -m venv venv
source venv/bin/activate

pip install selenium pytest
pytest test_items.py