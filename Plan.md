## План по проверке и автоматизации приложения «В хосписе».

### Введение
**Цель создания плана** - описание процесса автоматизации тестирования мобильного приложения "В хосписе";

**Объект тестирования** - мобильное приложение "В хосписе";

**Уровни тестирования:**
* Модульное тестирование -  проверка отдельно модулей "Авторизация", "Главная", "Заявки", "Новости", "О приложении", "Создание заявки", "Создание новости","Фильтровать новости";
* Интеграционное тестирование - проверка корректности взаимодействия нескольких модулей, объединенных в единое целое (переход со страницы "Авторизация" на главную страницу, с главной страницы на страницы "Заявки", "Новости", "О приложении", переход со страниц в разделы, создание, удаление, редактирование, поиск новостей и заявок, создание и редактирование коментариев).

**Виды тестирования:**
* Функциональное тестирование - проверить функциональность на соответствие требованиям;
* Тестирование интерфейса - проверить требования к пользовательскому интерфейсу.

### Процесс тестирования:
1. Ручное тестирование мобильного приложения "В Хосписе";
2. Составление чек-листа для проверки приложения;
3. Составление тест-кейсов для проверки приложения;
4. Автоматизация проверки тест-кейсов по чек-листу;
5. Создание отчета о тестировании.

### Перечень автоматизируемых сценариев:
- Тестирование функциональности входа/выхода из профиля (экран авторизации);
- Тестирование функционала переходов на страницы и в разделы;
- Тестирование функционала развертывания/сворачивания блоков и выпадающих списков;
- Тестирование функционала заполнении форм в разделах "Новости", "Заявки";
- Тестирование функционала создания/отмены действий удаления и редактирования новостей, заявок и коментариев;
- Тестирование функционала фильтрации новостей и заявок;
- Тестирование функцианала вкладки "Тематические цитаты";
- Тестирование функционала вкладки "О приложении".

### Перечень используемых инструментов с обоснованием выбора:
* **Android Studio** - программа для работы с кодом;
* **Java** - язык программирования для автоматизации;
* **JUnit 5** - фреймворк для модульного тестирования ПО на языке Java;
* **Espresso** - нативный фреймворк для тестирования;
* **Gradle** - система автоматической сборки для упрощения работы с Java;
* **Layout inspector** - программа для поиска идентификаторов;
* **Git** - система контроля версий;
* **GitHub** - хранение тестов;
* **GitHub Action** - CI для непрерывной интеграции;
* **Allure** - популярный инструмент построения отчётов, упрощающий их анализ.

### Перечень и описание возможных рисков при автоматизации:
* Возможность изменения структуры приложения (разделы, кнопки);
* Возможность появления сложностей с поиском элементов на странице;
* Возможность появления всевозможных багов.

### Критерии качества:
- Проект собирается, тесты запускаются без дополнительных манипуляций
- Проект работает на Android API 29
- В проекте есть ui-тесты
- Понятные названия тестов, методов и элементов
- Нет явных изъянов в архитектуре, корректный code style

### Интервальная оценка с учётом рисков (в часах):
* Исследование приложения - 2 часа;
* Создание чек-листа - 4 часа;
* Написание тест-кейсов - 10 часа;
* Написание автотестов - 60 часов;
* Отладка автотестов - 10 часов;
* Подготовка отчетности - 4 часа.

Необходимое время на написание тестов, тестирование и подготовки отчетности составляет 90 часов, с учетом рисков - 100 часов.

### План сдачи работ (когда будут автотесты, результаты их прогона и отчёт по автоматизации):
* Составление плана тестирования, чек-листа, тест-кейсов - до 09.07.2022г.
* Настройка окружения, написание и отладка автотестов - до 18.08.2022г.
* Подготовке отчётных документов по итогам автоматизированного тестирования - до 20.08.2022г.
* Подготовке отчётных документов по итогам тестирования - до 22.08.2022г.