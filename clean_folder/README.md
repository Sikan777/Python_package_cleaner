Опис
├── clean_folder
│    ├── clean_folder
│    │   ├── clean.py
│    │   └── __init__.py
│    └── setup.py


Вимоги
Перед використанням цього скрипта, вам потрібно мати наступні залежності:

Python версії 3.11.3
Модуль shutil
Модуль pathlib
Модуль re
Модуль sys
Використання
Встановіть залежності, які потрібні для цього проекту.
Використовуйте у терміналі командний рядок (бажано cmd) , щоб викликати скрипт і передати йому шлях до папки, яку потрібно сортувати. Наприклад: python main.py E:\musor1
Скрипт автоматично створить папки для сортування і розпочне сортування файлів.
Додаткова інформація
Цей проект є результатом домашнього завдання модуля 7 та може містити обмежену функціональність та може бути покращений в недалекому майбутньому.
Пакет встановлюється в систему командою pip install -e . (або python setup.py install, потрібні права адміністратора).
Після установки в системі з'являється пакет clean_folder.
Коли пакет встановлений в системі, скрипт можна викликати у будь-якому місці з консолі командою clean-folder
Консольний скрипт обробляє аргументи командного рядка точно так, як і Python-скрипт.