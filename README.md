# UML Диаграммы
1. [Диаграмма активности](#1)
2. [Диаграмма классов](#2)
3. [Диаграмма последовательности](#3)
4. [Диаграмма прецедентов](#4)
5. [Диаграмма развертывания](#5)
6. [Диаграмма состояний](#6)
7. [Поток событий](#7)
### 1. Диаграмма активности<a name="1"></a>
Диаграмма активности представляет собой следующую диаграмму: 

![Диаграмма активности](https://github.com/DmitriyBoss/tritpoDmitriy/blob/master/images/Screenshot_5.png)

### 2. Диаграмма классов<a name="2"></a>
Диаграмма классов представляет собой следующую диаграмму: 

![Диаграмма классов](https://github.com/DmitriyBoss/tritpoDmitriy/blob/master/images/Screenshot_1.png)

### 3. Диаграмма последовательности<a name="3"></a>
Диаграмма последовательности представляет собой следующую диаграмму: 

![Диаграмма последовательности](https://github.com/DmitriyBoss/tritpoDmitriy/blob/master/images/Screenshot_6.png)

### 4. Диаграмма прецедентов<a name="4"></a>
Диаграмма прецедентов представляет собой следующую диаграмму: 

![Диаграмма прецедентов](https://github.com/DmitriyBoss/tritpoDmitriy/blob/master/images/Screenshot_8.png)

### 5. Диаграмма развертывания<a name="5"></a>
Диаграмма развертывания представляет собой следующую диаграмму: 

![Диаграмма развертывания](https://github.com/DmitriyBoss/tritpoDmitriy/blob/master/images/Screenshot_2.png)

### 6. Диаграмма состояний<a name="6"></a>
Диаграмма состояний представляет собой следующую диаграмму: 

![Диаграмма состояний](https://github.com/DmitriyBoss/tritpoDmitriy/blob/master/images/Screenshot_3.png)

### 7. Поток событий<a name="7"></a>
#### 7.1 Глоссарий
| Понятие | Описание |
|:--|:--|
| Пользователь | Человек, использующий приложение |
| Браузер | Интернет-браузер, использующийся по умолчанию |
#### 7.2 Варианты использования
##### 7.2.1 Выбрать страницу

1. Начало основного потока.
2. Пользователь нажимает на кнопку перехода к следующей/предыдущей странице.
3. Если текущая страница не является крайней, запускаем альтернативный поток.
4. Переходим к следующей/предыдущей странице.
5. Завершаем альтернативный поток.
6. Если текущая страница является крайней, выходим из функции.
7. Конец основного потока.

##### 7.2.2 Открыть полную версию новости в браузере

1. Начало основного потока.
2. Пользователь нажимает на заголовок новости/поста.
3. Открывается браузер с выбранной новостью/постом.
4. Конец основного потока.

##### 7.2.3 Перейти на главную страницу сайта-источника

1. Начало основного потока.
2. Пользователь нажимает на кнопку перехода на главную страницу сайта-источника.
3. Открывается браузер с главной страницей выбранного сайта-источника.
4. Конец основного потока.

##### 7.2.4 Выбрать сайт источник для показа новостей/постов

1. Начало основного потока.
2. Пользователь выбирает интересующий его сайт-источник.
3. Обновляется главное окно приложения и пользователю предоставляется набор новостей/постов с выбранного сайта-источника.
4. Конец основного потока.

