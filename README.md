# Компьютерная безопасность 10
Программа может создавать пароь по заданным критериям, проверять один пароль на соответсвие или массив (требуется текстовый файл, находящийся в директории программы, где каждый пароль написан на каждой строке)
Для проверки пароля на совпадение с часто используемыми дополнительно используется файл freq.py, без него этой проверки не будет.
Для проверки/создания пароля запрашиваются критерии (использование верхнего регистра, цифр, особых символов и длиня пароля)
Для обработки файла требуется указать названия файла в директории программы (для примера прикреплен файл pwds.txt)
ПРИМЕРЫ ВВОДА.
1. ПРОВЕРКА ОДНОГО ПАРОЛЯ
Ввод:
1
1
1
6
qqq
Вывод:
Пароль не соответствует требованиям:

Длина не соответствует заданной
Нет требуемых символов
2.СОЗДАНИЕ ПАРОЛЯ.
Ввод:
1
1
1
8
Возможный вывод:
2z?0xI2Y

0iTO809@
3.ОБРАБОТКА ФАЙЛА С ПАРОЛЯМИ.
Ввод:
1
0
1
8
pwds.txt
Вывод:
Всего паролей: 2859
Соответствуют требованиям: 43
Не соответствуют требованиям: 2816
