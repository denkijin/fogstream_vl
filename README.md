# Задачки для курсов

## Числа

- Дано число n. С начала суток прошло n минут. Определите, сколько часов и минут будут показывать электронные часы в этот момент. Программа должна вывести два числа: количество часов (от 0 до 23) и количество минут (от 0 до 59). Учтите, что число n может быть больше, чем количество минут в сутках.

- Длина Московской кольцевой автомобильной дороги —109 километров. Стартуем с нулевого километра МКАД и едем со скоростью V километров в час. На какой отметке остановимся через T часов? Программа получает на вход значение V и T. Если V>0, то движемся в положительном направлении по МКАД, если же значение V<0, то в отрицательном. Программа должна вывести целое число от 0 до 108 — номер отметки, на которой остановимся.

- В некоторой школе занятия начинаются в 9:00. Продолжительность урока — 45 минут, после 1-го, 3-го, 5-го и т.д. уроков перемена 5 минут, а после 2-го, 4-го, 6-го и т.д. — 15 минут. Дан номер урока (число от 1 до 10). Определите, когда заканчивается указанный урок. Выведите два целых числа: время окончания урока в часах и минутах.

- Процентная ставка по вкладу составляет P процентов годовых, которые прибавляются к сумме вклада. Вклад составляет X рублей Y копеек. Определите размер вклада через год. Программа получает на вход целые числа P, X, Y и должна вывести два числа: величину вклада через год в рублях и копейках. Дробная часть копеек отбрасывается.

- С начала суток прошло H часов, M минут, S секунд (0 ≤ H < 12, 0 ≤ M < 60, 0 ≤ S < 60). По данным числам H, M, S определите угол (в градусах), на который повернулаcь часовая стрелка с начала суток и выведите его в виде действительного числа.

## Строки
- Дана строка, состоящая из слов, разделенных пробелами. Определите, сколько в ней слов.

- Дана строка. Разрежьте ее на две равные части (если длина строки — четная, а если длина строки нечетная, то длина первой части должна быть на один символ больше). Переставьте эти две части местами, результат запишите в новую строку и выведите на экран.

- Дана строка. Если в этой строке буква f встречается только один раз, выведите её индекс. Если она встречается два и более раз, выведите индекс её первого и последнего появления. Если буква f в данной строке не встречается, вывести -1.

- Дана строка. Замените в этой строке все цифры 1 на слово one

- Дана строка. Удалите из нее все символы, чьи индексы делятся на 3.

- Вам задана строка , состоящая из пробелов и латинских букв. Строка называется панграммой, если она содержит каждую из 26 латинских букв хотя бы раз. Определите является ли строка панграммой.
В единственной строке входных данных записана строка . Строка может содержать только пробелы, заглавные и строчные буквы латинского алфавита. Заглавные и строчные буквы считаются одинаковыми.

- Определим слова в хэштеге. Дана строка, начинается с # и содержит набор слов соединенных в одну строку без пробелов. Срока описана в стиле camelCase, то есть первое слово начинается с прописной буквы, а каждое следующее с заглавной. Например: #приветКакДела, #меняЗовутЕгорМнеМногоЛет и тд. Необходимо посчитать количество слов в строке и вывести количество этих слов.

## Списки
- Дан список чисел. Выведите все элементы списка, которые больше предыдущего элемента.

- Дан список чисел. Если в нем есть два соседних элемента одного знака, выведите эти числа. Если соседних элементов одного знака нет — не выводите ничего. Если таких пар соседей несколько — выведите первую пару.

- Дан список чисел. Выведите значение наибольшего элемента в списке, а затем индекс этого элемента в списке. Если наибольших элементов несколько, выведите индекс первого из них.

- Найти все уникальные элементы в списке. Список произвольной длины и может состоять как из чисел, так и строк.

- Программа получает на вход невозрастающую(все элементы списка не упорядочены по возрастанию) последовательность натуральных чисел. После этого вводится число X. Все числа во входных данных натуральные и не превышают 200.
Выведите индекс, где окажется число Х. Если в списке есть элемент с таким значением, то число Х помещается после него.

- Даны имена и средняя успеваемость учеников класса. Необходимо вывести имена одного или нескольких учеников, находящихся на предпоследнем месте по успеваемости.

- Даны два списка произвольной длины каждый. Списки могут содержать как числа, так и строки. Необходимо вывести только те элементы, которые входят как первый список, так и во второй.

## Функции
- Даны четыре действительных числа: x1, y1, x2, y2. Напишите функцию distance(x1, y1, x2, y2), вычисляющая расстояние между точкой (x1,y1) и (x2,y2). Считайте четыре действительных числа и выведите результат работы этой функции.

- Написать функцию is_prime, принимающую 1 аргумент — число от 0 до 1000, и возвращающую True, если оно простое, и False - иначе.

- Дан список результатов попыток одного спортсмена для некоторого соревнования. Написать функцию, которая считает сколько за сессию был установлен новый рекорд, т.е. текущее значение превышает значение максимального.
Например. Имеем список результатов.:
```python
scores = [10, 5, 20, 20, 4, 5, 2, 25, 1].
```
В данном случае ответ: 2.

- Написать функцию avaranger, которая принимает 1 аргумент - любое число и возвращается среднее арифметическое значение, на основании текущего числа и предыдущих, которые были введены ранее.

Например
```python
>>> avaranger(10) # Среднее арифметическое 10

>>> 10

>>> avaranger(11) # Среднее арифметическое 10 и 11

>>> 10.5

>>> avaranger(12) # Среднее арифметическое 10, 11 и 12

>>> 11
```

- Реализовать функцию-валидатор почтовых адресов. Принимает строку, которая содержит адрес электронной почты. Возвращает True, если адрес валидный, иначе возвращает False.

Валидным адресом называется такой, который удовлетворяет следующим условиям:

1. Имеет формат username@websitename.extension

2. username может содержать только латинские буквы, целые числа, нижние подчеркивания и тире

3. websitename содержит только латинские буквы и целые числа

4. Максимальная длина extension 3 символа.

- Реализовать функцию map, принимающей два аргумента: список и произвольную арифметическую функцию.
Функция map должна возвращать новый список, элементы которого являются результатом функции func.

Например

Определим функцию func(x), которая возвращает квадрат аргумента:
```python
def func(x):
    return x**2
Где-то выше определили функцию map и передали ей список и ссылку на функцию:
```python
>>> map([1, 2, 3], func)
```
В результате получаем:
```python
>>> [1, 4, 9]
```
## Файлы
- Дан файл с расписанием занятий на неделю. Помимо названия предмета в нем также указано лекция это, или практическое занятие, или лабораторная работа. В одной строке может быть указаны только один предмет с информацией о нем. Посчитать, сколько за неделю проходит практических занятий, лекций и лабораторных работ.

Пример файла:

Понедельник

Физика (лекц.)

Физика (лаб.)

Алгебра (практ.)

Вторник

Геометрия (лекц.)

Физика (практ.)

Физика (лаб.)

Физкультура (практ.)

...

- В одном файле в каждой строке записаны координаты пар точек. Каждая координата отделена от другой пробелом. Например, строка вида 3 6 -2 4 означает, что координаты первой точки (3;6), второй - (-2;4). Во второй файл требуется построчно записать наибольшее и наименьшее расстояние между точками.

- Дан файл. Определите сколько в нем букв (латинского алфавита), слов, строк. Выведите три найденных числа в формате, приведенном в примере.
Пример входного файла:
```
Beautiful is better than ugly.

Explicit is better than implicit.
 
Simple is better than complex.
 
Complex is better than complicated.
```
Пример выходного файла:
```
Input file contains:

108 letters

20 words

4 lines
```

- Дан файл, содержащий сведения о книгах:

1. фамилия автора

2. название

3. год издания

4. цена книги
Распечатать записи с заданным годом издания, упорядоченные по алфавиту, а если таковых нет, то выдать соответствующее сообщение;

- Дан файл содержащий произвольный текст. Необходимо проверить сколько раз в тексте повторяется введеное слово или фраза и вывести в файл.

- В файле содержится текстовая строка. Определить частоту повторяемости каждой буквы в тексте и вывести ее.

- Cоздать типизированный файл записей со сведениями о телефонах абонентов; каждая запись имеет поля: фамилия абонента, год установки телефона, номер телефона. По заданной фамилии абонента выдать номера его телефонов. Определить количество установленных телефонов с N-го года.


## ООП

- Создать класс Fraction, который должен иметь два поля: числитель a и знаменатель b. Оба поля должны быть типа int. Реализовать методы: сокращение дробей, сравнение, сложение и умножение.

- Составить описание класса многочленов от одной переменной, задаваемых сте­пенью многочлена и массивом коэффициентов. Предусмотреть методы для вы­числения значения многочлена для заданного аргумента, операции сложения, вычитания и умножения многочленов с получением нового объекта-многочлена, вывод на экран описания многочлена.

- Создать абстрактный класс Figure с методами вычисления площади и периметра, а также методом, выводящим информацию о фигуре на экран. Создать производные классы: Rectangle (прямоугольник), Circle (круг), Triangle (треугольник) со своими методами вычисления площади и периметра.

- Создать класс для хранения комплексных чисел. Реализовать операции над комплексными числами: сложение, вычитание, умножение, деление, сопряжение, возведение в степень, извлечение корня. Предусмотреть возможность изменения формы записи комплексного числа: алгебраическая форма, тригонометрическая форма, экспоненциальная форма.

- Создайте структуру с именем student, содержащую поля: фамилия и инициалы, номер группы, успеваемость (массив из пяти элементов). Создать массив из десяти элементов такого типа, упорядочить записи по возрастанию среднего балла. Добавить возможность вывода фамилий и номеров групп студентов, имеющих оценки, равные только 4 или 5.


