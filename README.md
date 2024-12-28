## Описание проекта
Данный проект был сделан в рамках программы предстажировки "ML caselab" от компании Гринатом. Итоговая задача заключалась в создании модели машинного обучения, которая была бы способна по фотографии документа определить bounding box'ы различных элементов в нём, а также сказать, к каким именно классам относятся эти элементы.

Элементы, которые может определить итоговая модель:
* header и footer - верхний и нижний колонтитул соответственно
* paragraph - параграф текста
* title - заголовок
* marked_list и numbered_list - маркированный и нумерованный список соответственно
* formula - формула
* picture - картинка
* picture_signature - подпись к картинке
* table - таблица
* table_signature - подпись к таблице
* footnote - сноска

Проделанную над проектом работу можно разбить на несколько этапов:
1. Понимание задачи 
2. Создание скриптов для генерации обучающей и тестовой выборки
3. Выбор нескольких моделей
4. Обучение выбранных моделей с использованием различных техник
5. Проведение тестов и выбор лучшей модели
6. Создание приложения для более удобного использования полученной модели

## Навигация
- [app](https://github.com/Tesla0s/Document-layout-project/tree/main/app) - код сервиса

- [data](https://github.com/Tesla0s/Document-layout-project/tree/main/data) - примеры сгенерированных данных

- [notebooks](https://github.com/Tesla0s/Document-layout-project/tree/main/notebooks) - ноутбуки, использовавшиеся для обучения моделей

- [scripts](https://github.com/Tesla0s/Document-layout-project/tree/main/scripts) - скрипты для генерации датасета и инференса на тестовых данных

- [test_from_telegram](https://github.com/Tesla0s/Document-layout-project/tree/main/test_from_telegram) - обработанные изображения и разметка тестового файла, полученного в телеграме

- [metrics_on_test_datasets](https://github.com/Tesla0s/Document-layout-project/tree/main/metrics_on_test_datasets) - результаты работы модели на тестовых датасетах нашей и других групп

