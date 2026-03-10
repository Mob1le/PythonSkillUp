RoadMap для изучения
Внутри репозитория могут встречаться различные примеры для оттачивания практических навыков для каждого дня. Начиная с Day1 заканчивая с Day5_7

Для опытного программиста лучший путь — это метод «погружения через практику». Поскольку вы уже знаете структуры данных и циклы, вам не нужно учить их заново, достаточно узнать, как они записываются в Python и Bash.
Ниже представлен интенсивный двухнедельный план, разделенный на блоки по 1–2 часа в день.
Неделя 1: Python (Переход с других языков)
Цель: Перестать писать на Python как на Java/C++ и начать использовать его встроенные возможности.

* День 1: Синтаксический «шок» и типы данных.
* Установка среды (venv, pip, PyCharm/VS Code).
   * Значимые отступы (никаких {}).
   * Динамическая типизация и f-строки.
   * Практика: Написать скрипт, который принимает имя пользователя и возраст, и выводит через сколько лет ему будет 100.
* День 2: Коллекции и Pythonic Way.
* Списки, словари, множества и кортежи.
   * List Comprehensions (генераторы списков) — обязательный инструмент.
   * Распаковка аргументов (*args, **kwargs).
   * Практика: Фильтрация списка чисел и преобразование их в квадраты одной строкой кода.
* День 3: Функции и модули.
* Области видимости (LEGB).
   * Импорт стандартных библиотек (math, datetime, random).
   * Декораторы (базовое понимание: как изменить поведение функции, не меняя её код).
* День 4: Системная автоматизация (самое важное для скриптов).
* Работа с файловой системой: модули os, pathlib, shutil.
   * Запуск внешних команд через subprocess.
   * Практика: Скрипт, который сканирует папку и сортирует файлы по расширениям в разные подпапки.
* День 5–7: Работа с данными и API.
* Чтение/запись JSON, CSV.
   * Библиотека requests для HTTP-запросов.
   * Мини-проект: Скрипт, который берет курс валют из публичного API и сохраняет его в Excel/CSV. [1, 2, 3, 4] 

Неделя 2: Bash (Системная магия)
Цель: Научиться управлять Linux-сервером и автоматизировать рутину без Python.

* День 1: Основы и переменные.
* Шебанг #!/bin/bash.
   * Типы кавычек (', ", `) — критически важно понять разницу.
   * Переменные окружения и позиционные параметры ($1, $2, $@).
* День 2: Конвейеры и фильтры.
* Перенаправление потоков: stdin, stdout, stderr (>, >>, 2>).
   * Пайпы (|).
   * Святая троица: grep, sed, awk (на базовом уровне).
   * Практика: Найти в лог-файле все ошибки 404 и посчитать их количество.
* День 3: Логика и условия.
* Конструкции if [ ... ], case.
   * Циклы for и while.
   * Коды завершения команд ($?).
   * Практика: Скрипт-бэкапщик, который проверяет наличие папки и, если она есть, создает ее архив.
* День 4: Функции и продвинутые фишки.
* Функции в Bash (особенности возврата значений).
   * Работа с ключами запуска (использование getopts).
* День 5–7: Реальные задачи DevOps.
* Написание Makefile или скрипта для автоматического деплоя.
   * Мини-проект: Написать Bash-скрипт, который проверяет свободное место на диске и, если его меньше 10%, присылает уведомление (или пишет в системный лог). [5, 6, 7, 8] 

Рекомендуемые ресурсы

   1. Python: Официальный туториал (идеален для профи) и Learn X in Y minutes (Python).
   2. Bash: Интерактивный ресурс roadmap.sh/shell-bash и справочник Advanced Bash-Scripting Guide. [3, 5, 9, 10] 

С какого языка вам комфортнее начать: с Python для обработки данных или с Bash для управления системой?

[1] [https://msk.top-academy.ru](https://msk.top-academy.ru/articles/perekhod-na-python-s-drugogo-yazyka#:~:text=%D0%92%D1%8B%20%D1%83%D0%B6%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%81%D1%82%20%D0%BD%D0%B0%20C++%2C%20Java%20%D0%B8%D0%BB%D0%B8,%D0%BE%D0%BF%D1%8B%D1%82%20%D0%BD%D0%B0%20Python%2C%20%D0%B8%D0%B7%D0%B1%D0%B5%D0%B6%D0%B0%D0%B2%20%D1%82%D0%B8%D0%BF%D0%B8%D1%87%D0%BD%D1%8B%D1%85%20%D0%BE%D1%88%D0%B8%D0%B1%D0%BE%D0%BA%20%D0%BD%D0%BE%D0%B2%D0%B8%D1%87%D0%BA%D0%BE%D0%B2.)
[2] [https://pythonist.ru](https://pythonist.ru/books-on-python-you-should-read-in-2025/)
[3] [https://rivery.io](https://translate.google.com/translate?u=https://rivery.io/blog/free-resources-learn-python/&hl=ru&sl=en&tl=ru&client=sge#:~:text=Python.Org%20%D0%9E%D1%84%D0%B8%D1%86%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9%20%D1%81%D0%B0%D0%B9%D1%82%20Python%20%E2%80%94%20%D0%BE%D0%B4%D0%B8%D0%BD%20%D0%B8%D0%B7,%D1%81%D0%B8%D0%BD%D1%82%D0%B0%D0%BA%D1%81%D0%B8%D1%81%20Python%2C%20%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B8%20%D0%B8%20%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B%20%D0%B5%D0%B3%D0%BE%20%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.)
[4] [https://python.plainenglish.io](https://translate.google.com/translate?u=https://python.plainenglish.io/why-python-is-still-the-best-language-to-start-with-in-2025-98435c72df7e&hl=ru&sl=en&tl=ru&client=sge)
[5] [https://roadmap.sh](https://roadmap.sh/shell-bash)
[6] [https://medium.com](https://medium.com/devops-ai-decoded/10-bash-tricks-every-cloud-engineer-should-learn-in-2026-c5170ddd95d6#:~:text=Bash%20scripting%20is%20essential%20for%20cloud%20engineers,cases%20to%20help%20you%20master%20your%20craft.)
[7] [https://medium.com](https://medium.com/@himanshumahajan138/roadmap-for-learning-bash-scripting-for-devops-7fbb3834808a)
[8] [https://medium.com](https://medium.com/@yashvikothari/why-advanced-bash-scripting-remains-your-production-lifeline-in-2026-f1f9e3e763ec)
[9] [https://www.reddit.com](https://www.reddit.com/r/learnprogramming/comments/nx0ue8/best_python_course_for_those_that_already_know_a/?tl=ru)
[10] [https://www.reddit.com](https://www.reddit.com/r/bash/comments/1ohlkfa/new_shellbash_roadmap_at_roadmapsh/#:~:text=We%27re%20planning%20to%20launch%20a%20brand%20new,want%20to%20overwhelm%20users%20with%20excessive%20content.)
