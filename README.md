# Composition
«Композиция и зависимость объектов. Mockito при создании автотестов»


Добавить фильм в ленту (класс фильма напишите сами по аналогии с лекции).
Выдать последние 10 добавленных фильмов* (фильмы выдаются в обратном порядке, т.е. первым в массиве результатов будет тот, который был добавлен последним).
Примечание*: если фильмов меньше 10, то выдаёте столько, сколько есть.

Сделайте так, чтобы по умолчанию выводилось последние 10 добавленных фильмов, но при создании менеджера можно было указать другое число, 
чтобы, например, выдавать 5 (а не 10). Т.е. у вас у менеджера должно быть два конструктора: один без параметров, выставляющий лимит менеджера в 10, 
а другой с параметром, берущий значение лимита для менеджера из параметра конструктора.
