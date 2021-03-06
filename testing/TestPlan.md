# План Тестирования
## Содержание
1. [Введение](#introduction)
2. [Объект тестирования](#testingobject)
3. [Риски](#risks)
4. [Аспекты тестировани](#testingaspects)
5. [Подходы к тестированию](#testingapproaches)
6. [Предоставление результатов](#results)
7. [Выводы](#conclusion)

## 1. Введение <a name="introduction"></a>
Данный документ описывает план тестирования разрабатываемого программного продукта - "Управление складами". Он предназначен для команды тестировщиков. Цель тестирования: проверить соответствие приложения требованиям и выявить ошибки, допущенные при реализации данного приложения.
## 2. Объект тестирования <a name="testingobject"></a>
В процессе тестирования предполагается проверить работоспособность приложения. В качестве объектов тестирования можно выделить основные функциональные требования, а также требования к удобству использования.  
Атрибуты качества:
1. Функциональность:  
* функциональная полнота;  
* функциональная корректность;  
* функциональная целесообразность.  

2. Удобство использования:  
* эстетика пользовательского интерфейса;  
* простота пользовательского интерфейса;  
* защита от ошибок пользователя.  

## 3. Риски <a name="risks"></a>
Низкая скорость подключения к интернету или отсутствие интернет-соединения.

## 4. Аспекты тестирования <a name="testingaspects"></a>
В ходе тестирования планируется проверить реализацию основных функций приложения, провести позитивные и негативные тесты, а также проверить нефункциональные требования. К основным функциям можно отнести следующие пункты:
*Просмотр всех складов
* поиск складов;
* Добавление склада;
* удаление склада;
* ответ на заявки.
#### Функциональные требования:

##### Просмотр списка всех книг
Этот вариант использования небходимо протестировать на:
1. Корректное отображение информации: наличие таблицы с информацией о складах;
2. Реакцию приложения на нажатие кнопки "user";
3. Реакцию приложения на нажатие на ссылку "Back to user page".
##### Поиск Склада
Этот вариант использования небходимо протестировать на:
1. Корректное отображение информации: наличие таблицы с информацией о найденных складах;
2. Реакцию приложения на нажатие кнопки "склад";
3. Реакцию приложения на нажатие на ссылку "Back to user page".
4. Отображение сообщения в случае, если данный склад не найден.
##### Добавление склада
Этот вариант использования небходимо протестировать на:
1. Корректное отображение форм для ввода информации о новом складе;
2. Появление соответсвующеего склада в списке всех складов;
3. Появление склада в списке складов, если его там раньше не было.
##### Удаление склада
Этот вариант использования небходимо протестировать на:
1. Отсутсвие склада в списке всех складов после нажатия кнопки "delete";
2. Отображение сообщения о том, что удаление невозможно, если склад основной.
##### Ответ на заявки
Этот вариант использования небходимо протестировать на:
1. Корректное отображение информации о заявках пользователей;
2. Реакция приложения при нажатии кнопки "accept";
3. Реакция приложения при нажатии кнопки "reject";  

Функции регистрации и входа в приложение не выносятся на тестирование, так как они являются побочными функциями приложения.

#### Нефункциональные требования:

1. все функциональные элементы пользовательского интерфейса имеют названия, описывающие действие, которое произойдет при выборе элемента;

## 5. Подходы к тестированию <a name="testingapproaches"></a>
Для тестирования приложения необходимо вручную проверить каждый аспект тестирования.

## 6. Предоставление результатов <a name="results"></a>
Результаты тестирования представлены в документе "Представление результатов".

## 7. Выводы <a name="conclusion"></a>
Данный тестовый план позволяет протестировать основной функционал приложения. Успешное прохождение всех тестов не гарантирует полной работоспособности на всех платформах и архитектурах, однако позволяет полагать, что данное программное обеспечение работает корректно.
