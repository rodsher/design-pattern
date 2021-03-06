# Шаблоны проектирования

Documentation for classic design patterns

## Как были созданы шаблоны проектирования?

В 70-х годах двадцатого века архитектор Кристорфер Александр составил набор шаблонов проектирования. Идея шаблонов проектирования из области архитектуры нашла свой отклик в области разработки софта. В 1987 году Кент Бэк и Вард Каннингем взяли идеи Кристорфера Александра и разработали шаблоны применительно к разработке программного обеспечения для разработки графических оболочек на языке Smalltalk. Параллельно в 1988 году Эрих Гамма начал писать докторскую работу при Цюрихском университете об общей переносимости этой методики на разработку cофта. Вместе с этим в 1989-1991 годах Джеймс Коплин разрабатывал идиомы для языка программирования C++. В 1991 году Джеймс Коплин опубликовал книгу "Advanced C++ Idioms".

В 1991 году Эрих Гамма переезжает из Цюриха в США. Совместно с Ричардом Хелмом, Ральфом Джонсоном и Джоном Влиссидсом он публикует книгу "Design Patterns - Elements of Reusable Object-Oriented Software". В книгу попадают 23 шаблона проектирования. Книга обретает известность и становится причиной роста популярности шаблонов проектирования. Команда авторово книги становится известна как "Gang of Four".

## Что такое шаблоны проектирования?

> Каждый паттерн описывает некую повторяющуюся проблему и ключ к ее разгадке, причем таким образом, что ключом можно пользоваться при решении самых разнообразных задач. Кристофер Александр

**Шаблон проектирования** - это _эффективный_ способ решения _характерной задачи_ проектирования.

Паттерны проектирования необходимо обдумывать перед внедрением в свой проект. Адаптировать паттерн под решение характерной задачи применительно к предметной области. Копировать готовый паттерн из книги или интернета в исходный код собственных программ не рекомендуется.

Польза паттернов:
- Решают класс абстрактных проблем
- Унифицируют терминологию
- Позволяют заново использовать удачные решения

Недостатки паттернов:
- Консервативные громоздкие решения
- Повышают критическую сложность систем, если использовать большое количество шаблонов
- Увеличивают разрыв между опытными и начинающими разработчиками

## ООП

**Объектно-ориентированное программирование** - парадигма программирования, в которой основной концепцией является понятие объекта, отождествляя его с объектом предметной области.

Основные концепции:
- Система состоит из объектов
- Объекты некоторым образом взаимодействуют между собой
- Каждый объект характеризуются собственным состоянием и поведением

Принципы объектно-ориентированного программирования:
- Инкапсуляция
- Наследование
- Полиморфизм

**Инкапсуляция** - это принцип, согласно которому любая часть системы должны рассматриваться как черный ящик. Пользователь класса или подсистемы должен видеть только интерфейс и список декларируемых свойств и методов. Принцип инкапсуляции позволяет минимизировать число связей между классами и подсистемами, упростить независимую реализацию и модификацию классов и подсистем.

**Наследование** - это принцип, согласно которому возможно порождать один класс от другого с сохранением всех свойств и методов суперкласса. Дочерний класс расширяется новыми свойствами и методами. Принцип наследования призван отобразить такое свойство реального мира, как иерархичность.

**Полиморфизм** - это принцип, согласно которому семейство различных механизмов позволяет использовать один и тот же участок программы с различными типами в разных контекстах. Дочерние классы могут изменять реализацию метода суперкласса, сохраняя его сигнатуру. Принцип полиморфизма позволяет обрабатывать объекты дочерних классов как однотипные объекты, хотя реализация методов у них может различаться.

## UML

**UML** - язык графического описания для объектного моделирования в области разработки программного обеспечения. UML от английского Unified Modeling Language. 
UML является языком широкого профиля. UML открытый стандарт, использующий графические обозначения для создания абстрактной модели системы. Такая абстрактая модель системы называется UML моделью.

Задачи UML:
- Проектирование
- Реверс-инжиниринг
- Извлечение текстовой информации из моделей

## Шаблоны GRASP

## Шаблоны GoF

## Рефакторинг

## Использованные источники

- [Курс по шаблонам разработки](https://www.youtube.com/watch?v=S-RjiMAxHio&list=PLmqFxxywkatStbd9hdzVOS1hZa9dc56k4)
- [Полиморфизм простыми словами](https://medium.com/devschacht/polymorphism-207d9f9cd78)
- [UML для бизнес-моделирования: зачем нужны диаграммы процессов](https://evergreens.com.ua/ru/articles/uml-diagrams.html)
