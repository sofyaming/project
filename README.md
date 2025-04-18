# Калькулятор расходов на Python
Простое приложение для учета личных финансов и контроля расходов.

## Установка (Windows/Linux/macOS)
Перед установкой убедитесь, что у вас установлен Python 3.7+ и pip.

1. Клонирование репозитория:
   
```git clone https://github.com/sofyaming/project.git```

2. Переход в директорию проекта:

```cd project```

3. Создание виртуального окружения:

```python -m venv venv```

4. Активация виртуального окружения:

    - Windows:
      ```venv\Scripts\activate```
    - Linux/macOS:
      ```source venv/bin/activate```

5. Установка зависимостей

```pip install -r requirements.txt```

6. Запуск приложения

```python main.py```

## Зависимости
Основные зависимости:
   - Python 3.7+
   - tkinter (обычно входит в стандартную поставку Python)
   - sqlite3 (встроенная библиотека)

## Технические особенности
   - Использует SQLite для хранения данных
   - Графический интерфейс на Tkinter
   - Автоматическое создание базы данных при первом запуске
   - Поддержка русского языка в интерфейсе

## Возможности
   - Добавление новых расходов
   - Просмотр истории расходов
   - Поиск по категориям
   - Редактирование и удаление записей
   - Простой и интуитивный интерфейс
## Использование
1. Для добавления расхода заполните поля:
   - Название (например, "Продукты")
   - Стоимость (например, "1500")
   - Комментарий (необязательно)
2. Используйте кнопки управления:
   - "Посмотреть все" - показать все расходы
   - "Поиск" - найти расходы по названию
   - "Добавить" - сохранить новый расход
   - "Обновить" - изменить выбранный расход
   - "Удалить" - удалить выбранный расход

## Описание коммитов
| Название | Описание                                                        |
|----------|-----------------------------------------------------------------|
| feat	   | Добавление нового функционала                                   |
| fix	     | Исправление ошибок                                              |
| style	   | Правки по кодстайлу (табы, отступы, точки, запятые и т.д.)      |
