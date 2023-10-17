# Kotlin-3
Код к занятию Kotlin-3

Внимание! Все этапы презентации лежат в отдельных коммитах по шагам.
Можно выкладывать коммиты один за другим, чтобы идти от простого к сложному.
Подробности в записи и в презентации.

# Домашнее задание


## 1. Функция с обязательными и необязательными позиционными параметрами
Напишите функцию, которая будет принимать:

- два обязательных аргумента типа `Int`
- неограниченное число дополнительных аргументов типа `Int`

Функция должна возвращать сумму первого, второго и дополнительных аргументов.
Если в функцию передано меньше двух аргументов, программа не должна собираться (ошибка компиляции).

## 2. Функция с необязательным параметром и позиционными параметрами
Напишите функцию, которая будет принимать:

- неограниченное количество строк `String`
- необязательный параметр типа `Char`

Функция должна возвращать объединение строк.

- по умолчанию, строки объединяется пробелом
- если передан `Char` параметр, то объединение делается этим символом

## 3. Тестовая функция для пункта №2
Напишите функцию-тест для первого пункта. Проверьте следующие условия для строк `str1` и `str2` и `str3`:

- Если `Char` не передан, ваша функция должна вернуть: `str1 str2 str3`
- Если `Char` задан как `,`, ваша функция должна вернуть: `str1,str2,str3`

## 4. Функция, измеряющая время выполнения другой функции

Напишите функцию, которая бы принимала другую функцию в качестве параметра.
Ваша функция должна запустить функцию, переданную в аргументе, и вернуть время ее выполнения.

Примечание: используйте что-то долгое (например, длинный цикл с печатью) в качестве тестовой функции. Иначе, вы можете
не заметить, сколько времени прошло
