# Introduction to DS

Это не очень сложный курс по машинному обучению с математикой и питоном. Он состоит из двух частей: введение в DS и ML для маркетинга. Вторая часть только для маркетологов. [Она в отдельном репозитории.](https://github.com/FUlyankin/ML_for_marketing)


* Материалы для каждого семинара лежат в папках `./sem*`
* В папке для каждой недели лежат файлы с семинаров, которые нужно изучить
* В каждой папке есть свой небольшой README с дополнительными материалами, которые желательно посмотреть
* Если вы хотите скачать из репозитория конкретную папку, просто вставьте ссылку на неё [в сервис для скачки.](https://minhaskamal.github.io/DownGit/#/home) Кнопка "скачать" есть в README к каждой неделе.
* Wiki-страница курса
* [Таблица с оценками](https://docs.google.com/spreadsheets/d/1nIoy3AaZrnjKZDwpXIU4ZPSUFXFnWPJn5kvZqoaZTBo/edit?usp=sharing)

* Любые вопросы можно задать в чат с технической поддержкой. Найдите нужный и вступите в него:

[![TG1](https://img.shields.io/badge/Telegram-BMM--chat-blue)]( ) [![TG2](https://img.shields.io/badge/Telegram-UB--chat-blue)]( ) [![TG3](https://img.shields.io/badge/Telegram-канал%20с%20объявлениями-blue)](https://bit.ly/2xQpHNZ)


## Перед стартом курса:

- 📦 __Установите себе на компьютер anaconda.__ Это среда, в которой мы будем работать.  
  - как установить:
  [Windows](https://github.com/FUlyankin/Intro_to_DS/blob/master/pdfs/install_conda_windows.pdf)
  [macOS](https://github.com/FUlyankin/Intro_to_DS/blob/master/pdfs/Anaconda%20installation%20guide_MacOS.pdf)
  - как открыть 1ый семинар:
  [Windows](https://github.com/FUlyankin/Intro_to_DS/blob/master/pdfs/download_and_open_sem01_windows.pdf)
  [macOS](https://github.com/FUlyankin/Intro_to_DS/blob/master/pdfs/Jupyter%20Notebook%20guide_MacOS.pdf)  
- 📦 Заведите себе anytask. Туда мы будем сдавать домашние работы.
- 📦 Часть домашних заданий сдаётся в систему Яндекс.Контест. На почты вам будут разосланы логины и пароли от неё.
  - [как зайти в контест и решить тестовое соревнование](https://github.com/FUlyankin/Intro_to_DS/blob/master/pdfs/test_contest.pdf)
  - [ссылка на тестовое соревнование](https://official.contest.yandex.ru/contest/17883/enter)
- 📦 Вторая часть заданий будет сдаваться в [anytask.](anytask.org) После первой лекции мы попросим в нём зарегистрироваться и ввести инвайт для своей группы: 

> Тут будут инвайты


## Домашние задания

Дедлайны по домашкам указаны либо в яндекс.контест либо в anytask. Для каждой домашки есть анонимная анкета, в которой вы можете высказать своё мнение о ней.

| домашка                         |    анонимка       |    решение    |  стоимость |
|:-------------------------------:|:-----------------:|:-------------:|:----------:|
|   Введение в python             |  анонимка по дз1  |               |    10      |
|   Работа в pandas               |  анонимка по дз2  |               |    10      |
|   Описательные статистики       |  анонимка по дз3  |               |    10      |
|   Визуализация                  |  анонимка по дз4  |               |    20      |
|   Регрессия                     |  анонимка по дз5  |               |    20      |
|   Классификация                 |  анонимка по дз6  |               |    10      |
|   АБ-тестирование               |  анонимка по дз7  |               |    10      |
|   Групповой кекс                |  анонимка по дз8  |               |    10      |


## Лекции

[Найти](https://drive.google.com/drive/folders/1zdmzkIQ2TyS2_DnYz2gWXoFEjuzKrLBu?usp=sharing) все доступные лекции без смс и регистрации


## Большой план маленьких побед

_Онлайн часть:_ Вводимся в python на Datacamp. __Зачем:__ когда начинаешь учить новый язык, возникает языковой барьер. В онлайн-модуле вам предстоит через боль и страдания преодолеть этот языковой барьер. Двойной языковой барьер. Курсы будут на английском. Не зря же вы его учите...

- [__sem01__](./sem01) решаем в python задачки и убеждаемся, что мы уже много умеем, но многому ещё нужно научиться.
- [__sem02__](./sem02) знакомимся с pandas, работаем с таблицами.
- [__sem03__](./sem03_stat) продолжаем работать с pandas. Решаем задачки на описательные статистики.
- [__sem04__](./sem04_visual) строим в python свой первый визуал.
- [__sem05__](./sem05_regression) знакомимся со своей первой моделью машинного обучения: линейной регрессией, разбираемся как она работает, говорим про деревья и случайный лес.
- [__sem06__](./sem06_regression) оцениваем свою первую регрессию.
- __sem07__ На этом семинаре нас ожидает контрольная работа. Надо будет за полтора часа решить несколько простых задачек в питоне.
- [__sem08__](./sem08_classif_metr) разбираемся с классификацией и метриками для неё.
- [__sem09__](./sem09_classif_algo) разбираемся с алгоритмами классификации: KNN, случайный лес.
- [__sem10__](./sem10_classif) гоняем алгоритмы классификации на компьютере.
- [__sem11__](./sem11_AB) разбираемся что такое AB-тест и как проверяют гипотезы.
- [__sem12__](./sem12_AB) проводим AB на компьютере, разбираемся что такое бутстреп.

__Задумка:__  ввелись в python, а затем прошлись по всем составным частям ML-пайплайна от работы с данными до обучения моделей и AB-тестов.

## Самый важный раздел

Оценка ставится по формуле:

```
Накоп = 0.1*DC + 0.2*СР + 0.2*КР + 0.5*ДЗ

Итог = max(0.3*ЭКЗ + 0.7*Накоп, 0.5*ЭКЗ + 0.5*Накоп)
```

- [ ] DC - ваша оценка за онлайн-часть
- [ ] СР - средняя оценка, полученная за самостоятельные работы. Учитывается три лучшие работы из четырёх. В новых реалиях самостоялки проводятся в Яндекс.Контест в строго лимитированное время.
- [ ] КР - ваша оценка за контрольную работу, она проводится в Яндекс.Контест
- [ ] ДЗ - итоговая оценка, полученная за 8 домашних работ. Часть работ будет проверяться в Яндекс.Контест. Часть сдаётся в anytask.
- [ ] ЭКЗ - оценка, полученная за экзамен.


## Контрибьюторы и создатели

- [Беднарский Роман](https://github.com/Bromanskiy): лекции, notebooks
- [Теванян Элен](https://github.com/elentevanyan): лекции, семинары, notebooks
- [Степанюк Ира](https://github.com/idStep): семинары, notebooks
- [Кутынина Катя](https://github.com/EkaterinaKut): семинары, notebooks
- [Ахматнуров Марат](https://github.com/maratakhm): семинары, notebooks
- [Попенова Полина](https://github.com/polyhex-sqr): семинары, notebooks
- [Ульянкин Пилиф](https://github.com/FUlyankin): семинары, notebooks
- [Максимовская Настя](https://github.com/AnastasiyaMax): семинары, notebooks
- [Ярослав Старухин](https://github.com/star-yar): notebooks


## Лицензия

Весь контент, созданный для этого курса распространяются на правах лицензии [Creative Commons Attribution-Share Alike 4.0.](https://creativecommons.org/licenses/by-sa/4.0/deed.ru) Материалы публикуются как общественное достояние.
