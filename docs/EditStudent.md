# Редактирование данных об ученике
![](././img/dgr.seqEdit.png "редактирование данных об ученике")

Диаграмма описывает процесс редактирование данных ученика. Пользователь нажимает на форме с таблицей учеников кнопку “Изменить”. Вызывается форма редактирования данных об ученике, где вызывается функция Student(ID: Int). В классе «Student» происходит запрос на получение полей ученика с заданным ID. Затем пользователь изменяет данные об ученике. Происходит присвоение данных полям класса, после чего вызывается функция Edit(). Выполняется запрос на редактирование ученика в БД. При успешном обновлении данных выводится сообщение, что данные об ученике изменены.