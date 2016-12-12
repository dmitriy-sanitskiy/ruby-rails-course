Описание предметной области
===========================
Библиотека
----------
####Объекты:
книги, библиотекарь, зарегистрированный читатель, незарегистрированный читатель
####Данные объекты имеют следующие атрибуты:
книги(автор книги, название, год издания, является ли новым изданием)
библиотекарь(ФИО)
зарегистрированный читатель(ФИО, номер читательского билета, адрес и телефон читателя)
незарегистрированный читатель(Имя)
####Основные функции каждого объекта
#####Книги могут:
* выдаваться
* прииниматься

#####Библиотекарь может:
* выдавать книгу в читальный зала зарегистрированным и незарегистрированным читателям
* выдавать книгу на дом лишь тем кто зарегистрирован
* принимать новые книги
* регистрировать читателей

#####Зарегистрированный читатель может:
* взять книгу на дом
* взять книгу почитать в читальном зале
* вернуть книгу
* отдать собственную книгу в бибилотеку

#####Не зарегистрированный читатель может:
* взять книгу почитать в читальном зале
* вернуть книгу
* зарегистрироваться в библиотеке
* отдать собственную книгу в библиотеку

####Связь между объектами
* Книги имеют связь лишь с библиотекарем
* Библиотекарь связан с книгами и всеми читателями
* Зарегистрированные читатели связаны только с библиотекарем
* Незарегистрированные читатели связаны только с библиотекарем