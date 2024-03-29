## Курсовой проект по модулю «Автоматизация тестирования» для профессии «Инженер по тестированию»
Дипломное задание позволяет закрепить знания и навыки по автоматизации тестирования мобильных приложений.

### **Предварительные условия**
**1.** Установить и открыть Android Studio:

Установочный файл: [по ссылке](https://developer.android.com/studio)

Инструкция по установке: [по ссылке](https://github.com/netology-code/guides/blob/master/android/android_studio/instruction1.md)

**2.** Установить приложение "Мобильный хоспис" на мобильное устройство.
   Данные для авторизации:
- В поле "Логин" ввести: **login2**
- В поле "Пароль" ввести: **password2**

### **Описание приложения**
Приложение предоставляет функционал по работе с единым информационным пространством для мед.работников и включает в себя:

* Информацию о заявках и функционал для работы с ними.
* Новостную сводку хосписа.
* Тематические цитаты.

### **Запуск тестов**
**1.** Склонировать [репозиторий](https://github.com/irikras/DiplomaProject.git) `git clone`;

**2.** Подключить устройство для тестирования, либо запустить эмулятор;

**3.** Перейти в папку `fmh-android`;

**4.** Открыть консоль и запустить тесты командой `./gradlew connectedAndroidTest`.

### **Подготовка отчета Allure**
* Для получения результатов тестирования получить отчеты командой:
  ``` 
  adb exec-out run-as ru.iteco.fmhandroid sh -c "cd /data/data/ru.iteco.fmhandroid/files && tar cf - allure-results" > allure-results.tar
  ```  

* Распаковать отчеты и сохранить их в allure-results.rar.    
  

### **Документация**

[План автоматизации тестирования](https://github.com/irikras/DiplomaProject/blob/master/Plan.md)

[Чек-лист](https://github.com/irikras/DiplomaProject/blob/master/Check.xlsx)

[Тест-кейсы](https://github.com/irikras/DiplomaProject/blob/master/Cases.xlsx)

[Отчёт по итогам тестирования](https://github.com/irikras/DiplomaProject/blob/master/Result.md)

