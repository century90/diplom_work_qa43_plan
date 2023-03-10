# 1. Перечень автоматизируемых сценариев

*Тест-кейс:*

https://docs.google.com/spreadsheets/d/1uT9Zh8qf9XxzhLivMZWqoFON-3kZSk4eCXkTkYDOkhY/edit?usp=sharing


# 2. Перечень используемых инструментов с обоснованием выбора

1) Для автоматизации тестов используется программа IntelliJ IDEA Community Edition 2022.2.1, язык Java, т.к. само приложение написано на данном языке
1) Для автотестов использоваться будет библиотека Junit
1) Поддержка СУБД осуществляется через Docker
1) Автотесты будут написаны с помощью библиотеки Selenid
1) В качестве системы репортинга предпочту работать Allure, т.к. эти системы проще в использовании, чем Report Portal (не требуется запуск дополнительных контейнеров), и более показательна, чем Gradle
1) Для хранения автотестов и настроек окружения используется Git и GitHub

# 3. Перечень и описание возможных рисков при автоматизации

1) Риск появления проблем с настройкой приложения и необходимых БД
1) Риск появления проблем с правильной идентификацией полей ввода
1) Риск неработающего заявленного функционала приложения

# 4. Интервальная оценка с учётом рисков в часах

1) Подготовка окружения, развертывание БД - 16 часов
1) Написание автотестов, тестирование и отладка автотестов - 36 часов
1) Формирование и анализ отчетов - 4 часа

# 5. План сдачи работ: когда будут готовы автотесты, результаты их прогона

1) Планирование автоматизации тестирования - до 14.12.2022
1) Настройка окружения, написание и отладка автотестов, тестирование - до 28.12.2022
1) Подготовка отчетных документов - до 30.12.2022
1) Доработка и исправление замечаний - до 08.01.2023