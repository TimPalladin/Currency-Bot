# Course Bot

**Простой, но в тоже время полностью функциональный телеграм-бот, который выводит курсы валют с сайта Банка России** 

### Возможности
- Имеет начальные подсказки при запуске
- Весь список действий доступен по команде /help

### Технологии
- Python
- aiogram 3
- BeautifulSoup + requests

### Как запустить

```bash
git clone https://github.com/TimPalladin/project-name.git
cd project-name

# Установка токена
В config.py в ковычках вместо 'Ваш тг токен' вставить свой токен из Bot Father телеграм.

# Установка зависимостей
pip install -r requirements.txt

# Запуск
python main.py
