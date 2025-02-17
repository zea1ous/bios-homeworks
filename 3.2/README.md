# Домашнее задание к занятию 3.2. Коллекции: кортеж и множество. Циклы for, while, repeat-while. Continue и break

Необходимо выполнить и предоставить на проверку следующие задачи. Все задачи можно выполнить и сдать в одном файле .playground.

## Задача 1
**Работа с кортежами**

Вы работаете над приложением "Информация о вас и ваших друзей". Ваша задача создать список людей с минимальной информацией о них и объединить одно из полей для создания общего значения.

#### Алгоритм выполнения
1. Создайте кортеж с тремя параметрами: ваш любимый фильм, ваше любимое число и ваше любимое блюдо. Все элементы кортежа должны быть именованы.
2. Одним выражением запишите каждый элемент кортежа в три константы.
3. Создайте второй кортеж, аналогичный первому по параметрам, но описывающий другого человека (с другими значениями).
4. Обменяйте значения в кортежах между собой (с использованием дополнительного промежуточного кортежа).
5. Создайте новый кортеж, элементами которого будут любимое число из первого кортежа, любимое число из второго кортежа и разница любимых чисел первого и второго кортежей.

## Задача 2
Вы продолжаете разрабатывать информационное приложение. Сейчас вам необходимо создать больше людей в вашем приложении (например, 5). И удалить людей, чье любимое число больше 13.

#### Алгоритм выполнения
1. Создайте еще как минимум трех человек с информацией.
2. Сложите все эти объекты в массив (пусть у двух любимое число будет больше 13, а у других трех меньше).
3. Выберите подходящий для задачи цикл и оператор управления выходом из этого цикла.
4. Удалите из массива неудовлетворяющие условию элементы.


## Задача 3
Вы разрабатываете приложение "Шахматы". Вашей задачей будет создать фигуру на игровом поле. 

#### Алгоритм выполнения

1. Создайте псевдоним Chessman для типа словаря `[String: (alpha:Character, num: Int)?]`. Данный тип описывает шахматную фигуру на игровом поле. 

В ключе словаря должно храниться имя фигуры, например «Белый король», а в значении — кортеж, указывающий на координаты фигуры на игровом поле. Если вместо кортежа находится nil, это означает, что фигура убита (не имеет координат на игровом поле).

2. Создайте переменный словарь Chessmans типа Chessman и добавьте в него три произвольные фигуры, одна из которых не должна иметь координат.

3. Создайте конструкцию `if-else`, которая проверяет, убита ли переданная ей фигура (элемент словаря Chessmans), и выводит на консоль информацию либо о координатах фигуры, либо о ее отсутствии на игровом поле.

**Подсказка**
    Для получения координат переданной фигуры используйте опциональное связывание.
    ```
    // chessmans.value - опциональное значение
    if let info = chessmans.value {
        // Действие
    }
    ```

## Задача 4 * (Необязательная задача)

Вам необходимо доработать программу из **Задания 3** таким образом, чтобы она автоматически анализировала не одну переданную ей фигуру, а все фигуры, хранящиеся в переменной Chessmans.

______________________

Решение сохраните в формате .playgrond. Готовый файл .playground заархивируйте и загрузите в личном кабинете в формате .zip.

Все задачи обязательны к выполнению для получения зачета, кроме задач со звездочкой. Присылать на проверку можно каждую задачу по отдельности или все задачи вместе. Во время проверки по частям ваша домашняя работа будет со статусом "На доработке".

Любые вопросы по решению задач задавайте в чате Slack (ссылку вы найдете в письме на вашей эл. почте).
