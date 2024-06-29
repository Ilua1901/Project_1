# Проект_1

**Проект 1**: Тестирование расписания в разделе "Личные события" в веб-приложении для учителей от Skyeng (Функциональное и API-тестирование)

Что нужно было сделать:
1. Подготовить тест-план
2. Подготовить тестовую документацию
3. Создать коллекцию в Postman
4. Провести тестирование
5. Написать отчет о результатах тестирования

Как решал: 
1. Ознакомился с требованиями, настроил окружение, зашёл во все необходимые аккаунты.
2. Составил тест-план, в котором указал информацию о тестируемом продукте, основные требования, расписание тестовых работ, виды тестирования и тестовую документацию. Для составления тест-плана использовал ``Confluencе``
3. Провёл тестирование требований
4. Сделал декомпозицию тестируемого функционала в ``Miro``
5. Составил smoke-тест в ``Qase.io``
6. Составил приёмочные тест-кейсы в ``Qase.io``, основываясь на требованиях стейкхолдеров
7. Провёл тест-ран приёмочных и smoke-тестов
8. Составил чек-листы функциональных проверок в ``Sitechco``, там же составил чек-лист для регрессионного тестирования
10. В ``Jira`` завёл баг-репорты на найденные баги
11. Занёс всю тестовую документацию в тест-план
12. Изучил документацию API в ``Swagger``
13. Провёл исследовательское тестирование используя ``Chrome devtools``
14. В qase.io создал тест-сьюты и составил API-тест-кейсы
15. Создал рабочее простраство в ``Postman``. Создал коллекцию и 4 группы для запросов, в зависимости от выполняемой ими функции - создание личного события, редактирование, отображение и удаление
16. В колекции создал запросы, соответствующие тест-кейсам в ``Qase.io``
17. Автоматизировал тест-ран в ``Postman``, используя последовательность действий (Создание -> Редактирование -> Отображение -> Удаление) и переменные. Получилось написать 2 тест-кейса, которые можно проверить через API, но невозможно проверить через интерфейс
18. В qase.io провел тест-ран на основе запущенной коллекции в Postman
19. Написал отчет о тестировании, в который приложил тестовую документацию и данные о найденных дефектах, а так же свои рекомендации по результатам тестирования

Ссылка на проект: https://ilua-bug-report.atlassian.net/wiki/spaces/~63f8e150526117e1514d7c5a/pages/950273/1+2


Выводы(Итоги):  
В ходе тестирования были обнаружены несколько некритичных багов, критичных багов не обнаружено.
Тестирование API расписания в разделе "Личные события" в веб-приложении для учителей от Skyeng пройдено успешно. Была создана Postman-коллекция из 4-х групп и 15 тестов API. Запуск коллекции в ``Postman`` удачно пройден, дефектов выявлено не было. Результаты тестирования показали, что продукт готов к релизу.
