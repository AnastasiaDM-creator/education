# Описание интерфейса IType
Интерфейс предназначен для работы с методами класса [Type](https://github.com/saramampco/oop/blob/master/docs/Client.md)

## Реализация интерфейса

* **add**(Type: Type): String – функция, добавляющая тип курса в базу данных;
* **del**( ID: Int): String –  функция, удаляющая  тип курса из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Type: Type): String – функция, редактирующая данные о типе курса;
* **getCourses**(ID:Int ): List< Course > –  функция, получающая список курсов с данным типом;
* **openTemplate**(ID: Int): String –  функция, открывающая шаблон договора с таким типом;
* **createTemplate**(ID: Int): String – функция, открывающая форму, в которой выбирается шаблон договора с таким типом;
* **findAll**(  editDate:	DateTime, delDate:	DateTime, ID: Int, Name: String, Lessonsot: Int, Lessonsdo: Int, Costot: Double,  Costdo: Double, CountMonth: Int,  sorting : String, ASKorDESK : String,  count : Int, page : Int): List< Type > – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с входными параметрами ID, Name – наименование типа курса, Lessonsot – количество занятий за весь курс начальная граница, Lessonsdo – количество занятий за весь курс нижняя  граница, Costot – начальная цена за обучение по этому типу курса, Costdo – конечная цена за обучение по этому типу курса, sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию,  count – количество.  