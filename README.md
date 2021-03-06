# C++ Junior Developer Training Course
88 hours training + 24 hours work project = 120 hrs.

# Ожидания от участников
- Математическая подготовка уровня не ниже полного среднего образования
- Понимание механизмов построения алгоритмов, циклов, ветвления
- Опыт базовой декомпозиции, процедурного программирования
- Понимание алгоритмической сложности, О-нотации
- Опыт работы хотя бы с один языком императивного программирования
- Базовые знания алгоритмов поиска и сортировки, хотя бы пузырёк и прямой обход
- Опыт работы с командной строкой
- Опыт работы с linux
- Опыт разработки на любом скриптовом языке

# 1. Цикл разработки (3 часов / включая 1 часа практики)
1. Обзор возможностей языка (парадигмы, спецификации, стандарт)
1. Первая программа (классический hello world, описание структуры простейшей программы, функция main, вывод в консоль)
1. Компиляция (процесс подготовки объектного файла, модель памяти, единица трансляции)
1. Линковка (сборка приложения, внешние библиотеки, статическая и динамическая линковка)
1. Среда разработки (требования к среде, code style, компоненты)
1. Компиляторы (gcc, mingw, clang, msvc, кросскомпиляция, поддержка языка)
1. Связь с языком С (компиляция из среды c++, обратная поодержка, разработка без ООП)
1. Свременный С++ (мажорные обновления стандарта, связь с развитием других популярных языков)
1. Фреймворки (Qt, OpenCV, OpenMP, boost, POCO, SFML, SDL)

## Практика
1. Hello World (сборка и запуск, смена выводимого сообщения, синтаксические ошибки)

# 2. Инфраструктура разработки и сборки (4/2)
## Git
1. Локальный workflow
1. Ветки и теги
1. Удаленный workflow

## Практика
1. Клонирование репо на github
1. Изменение
1. Публикация

## Cmake
1. Структура проекта (синтаксис, подготовка make, сборка)
1. Базовый workflow

## Практика
1. Сборка Hello World App (подготовка CMakeLists.txt, настройка среды)

# 3. Основы языка (8/2)
1. Синтаксис языка (императивный стиль, зарезервированные слова, блоки, разделители, заголовочные файлы, препроцессор)
1. Переменные и выражения (требования к именованию, унарные и бинарные операции, приоритет операций, сравнения, константы, квалификаторы)
1. Типы данных (целочисленные, с плавающей запятой, символьные, булевы)
1. Ветвление и циклы (базовые поддерживаемые методики организации циклов и ветвлений, break и continue, возможности switch-case, сложные условия)
1. Область видимости и стек вызовов (переменные на стеке, правила доступа, возможные ошибки с двойным именованием)
1. Ссылки и указатели (указатели в памяти, операции над указателями, разыменование, rvalue)

## Практика
1. Реализация консольной RPG в процедурном стиле. Функциональность выбора действий в цикле и состояний в условиях. Диалог с игроком

# 4. Процедурный стиль и структуры (6/2)
1. Функции (синтаксис, параметры, методы передачи значений, возврат значения, квалификаторы, reuse, перегрузка, рекурсия)
1. Массивы (одномерные, многомерные, символьные, динамические, доступ)
1. Структуры, объединения, перечисления (базовые механики)
1. Пространства имён (деление кода на логические модули, повторяемость наименований, доступ, using)

## Практика
1. Продолжение работы над консольной RPG, реализация структур игрока, врагов, инвентаря

# 5. Стандартная библиотека (8/3)
1. Ввод-вывод (консольный ввод-вывод, потоки, манипуляторы, оператор << и >>)
1. Строки (класс работы со строками, встроенные методы, приведение типов)
1. Алгоритмы (find, swap, sort, min, max, fill, понятие предиката, велосипедостроение)
1. Работа с файлами (сишный способ, потоки, чтение и запись, реакция на io ошибки)
1. Библиотека языка С (assert, math, stdio, stdlib, cstring)

## Практика
1. Сохранение и загрузка состояний в консольной RPG через файлы. Хранение описаний предметов и врагов.

# 6. Объектный стиль (4/1)
1. Зачем нужен объектно-ориентированный подход (классическая модель ООП + абстракция, понятие объекта и класса, свойства и методы, организация памяти)
1. Инкапсуляция данных и поведения (модификаторы, квалификаторы, операторы, область видимости и доступ)
1. Наследование и иерархия (перегрузка, виртуальные функции, ctor, dtor, абстракция, нисходящее и восходящее приведение)
1. Повторное использование кода (наследование и делегирование)
1. SOLID принципы дизайна
1. Паттерны проектирования (порождающие, структурные) [GoF]
1. static, extern, inline

## Практика
1. Рефакторинг RPG под использование ООП

# 7. Релизация объектного стиля в С++ (10/3)
1. Структура классов и объекты (организация памяти объекта, представление, защита данных, синтаксис)
1. Свойства и методы (описание и определение, предварительное объявление, ctor, dtor)
1. Модификаторы и квалификаторы (область видимости и доступ, const, mutable, ограничение доступа)
1. Перегрузка (сигнатуры, операторы)
1. Наследование и иерархия (правила наследования, порядок доступа, абстракция, виртуальные функции)
1. static, extern, inline (всего понемногу)

## Практика
1. Рефакторинг RPG с использованием наследования класса врагов. Изменяемость поведения. 

# 8. Шаблоны (4/2)
1. Обобщённое программирование (синтаксический сахар, обобщённые выражения, абстрагирование от типов данных)
1. Шаблоны функций (обобщённые функции для математических операций)
1. Шаблоны классов (классы с независимым значением аргумента, комплексные числа, перегрузка шаблонами)
1. Обзор STL

# Практика
1. Реализация взаимодействия объектов RPG через шаблонную функцию.

# 9. Контейнеры (8/2)
1. Вектор, массив, deque (случайный доступ, организация памяти)
1. list (последовательный доступ, динамическая память)
1. Map и multimap (ассоциативные списки, способы хранения, коллизии)
1. Queue и unordered_queue (очереди FIFO)
1. Set и multiset (множества, уникальность)
1. Stack (очереди LIFO)
1. Итераторы (обход контейнеров, сложность, правила выбора контейнеров)

## Практика
1. Миссии и задания в RPG, история действий

# 10. Дополнительные возможности (8/3)
1. Приведение типов (STD функции приведения, проблемы и реакция на ошибки, cast-операции, проблемы double, проблемы строк)
1. Работа с памятью (динамическая память, структуры, прямой доступ, выравнивание, куча)
1. RAII и умные указатели (адаптеры и автоматическое управление выделяемыми ресурсами)
1. Работа с сетью (библиотека curl, доступ к внешний ресурсам, ожидание данных, протоколы)

## Практика
1. Публикация статистики игры на внешний сайт, запрос статистики и вывод в игре

# 11. Исключения (6/2)
1. Классификация исключений (логические ошибки, ошибки времени выполнения, bad_cast)
1. Структура исключений (синтаксис, ключевые слова, правила вызова)
1. assert (простейший анализ поведения программы)
1. Реакция на исключения (способы обработки исключений, передача параметров, передача исключения, раскрутка стека)
1. Методики построения классов с исключениями (возврат результатов операций, поведение деструкторов)
1. Разработка собственного исключения (исключение с кодом)
1. Неопределённое поведение (понятие undefined behaviour, core dump)
1. Использование дебаггера (режимы компиляции, логирование, основы работы с дебаггером)
1. Методики тестирования ПО (юнит тестирование, мок тестирование, стресстесты, регрессионные тесты, ручные тесты)

## Практика
1. Рефакторинг RPG. Использование исключений для обработки логики завершения игры или неверных действий игрока

# 12. Unit testing with Upp11 (5/2)
1. Задачи модульных тестов (правила пнаписание, направленность, независимость, самоконтроль, TDD)
1. Структура теста (работа с upp11)
1. Оценка результатов (анализ поведения, исключения в тестах, тесты ради тестов)

## Практика
1. Покрытие RPG приложения модульными автотестами

# 13. Многопоточное программирование (8/3)
1. Основы многопоточной разработки и разделяемые данные (спецификация и поведение ядра, виды многопоточности, модель памяти)
1. Потоки (процессы и потоки, параллельное исполнение, независимость от задержек)
1. Гонка за ресурсами (разделяемый доступ, порча данных)
1. Примитивы синхронизации (мьютексы и спинлоки, атомарные типы)
1. CAS операции (atomic_flag, способ атомарной обработки данных)
1. Критическая секция (выделение критических ресурсов, ограничение разделяемых данных)
1. Грануляция критической секции (избыточность, сериализация данных, ожидание и нееффективность потоков)
1. Безопасность доступа к контейнерам (работа с итераторами, модификация, разделяемый доступ на чтение)
1. Дедлоки (разрешение блокировок, scoped_lock, recursive_mutex)

## Практика
1. RPG как клиент-сервеное приложение со множеством игроков

# 14. Расширенные возможности* (8/3)
1. Регулярные выражения (только std, никакой теории)
1. RTTI (методы интроспекции, динамическое приведение типов)
1. Лямбда функции (синтаксический сахар, запекание)
1. Библиотека boost (основные возможности: математика, сеть, адаптеры)
1. Списки инициализаций (синтаксический сахар, правила приведения, tuple, initializer_list)
1. Автовывод типов (вывод значений, итераторы, вывод возвращаемых значений функций, универсальные ссылки)
1. Вложенные пространства имён
1. Аллокаторы (кастомная работа с памятью)

## Практика
1. Битвы между игроками в консольной RPG

# 15. Рабочий проект (24/24)
