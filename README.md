# Техническое задание №2
## Как собрать проект?
### 1) Скачать файлы из папки src и вставить их в папку src в вашем IntellijIdea.
### 2) Скачать папку JavaTests, поместив ее на диск F:\.
### После выполнения этих шагов, проект собран, можно приступать к выполнению. 
## Как запустить проект и тесты к нему?
### 1) Запускаете код Main.java, в консоль вводите абсолютный путь к файлу, на котором хотите испытать программу.
### 2) Для запуска тестов необходимо просто открыть UserServiceTest.java и нажать на кномку исполнения программы(пути на необходимые файлы с тестами уже вставлены в код).
## Что программа из себя представляет?
### 1) Ввод и вывод данных 
#### На вход подается текстовый файл, который может содержать целые числа, разделенные пробелом. На выходе появлются минимальное число из файла, максимальное число из файла, сума всех чисел в файле и произведение всех чисел в файле.
### 2) Считывание файла
#### Считываем файл с помощью методов из библиотеки FileReader и записываем его в массив, получая массив всех чисел файла.
### 3) Функция _min
#### Ищет минимальное число среди всех чисел входного файла путем быстрой сортировки массива и взятия первого числа.
### 4) Функция _max
#### Ищет максимальное число среди всех чисел входного файла путем быстрой сортировки массива и взятия последнего числа.
### 5) Функция _sum
#### Счётчик пробегает последовательно по всем числам файла, складывая их.
### 6) Функция _mult
#### Счётчик пробегает последовательно по всем числам файла, умножая их. По достижении 56-ой операции умножения, счетчик записывает свое значение в итоговый результат, при этом снова становясь равным единице. Это сделано для ускорения работы программы(т.к. ей сложно умножать большие числа)
### 7) Функция quicksort
#### Представляет собой обычный quicksort, который нужен для вычисления минимума и максимума чисел путем сортировки массива с ними.
## График зависимости времени исполнения функции _mult от количества чисел в файле.
![](Измерение продолжительности выполнения операции умножения при увеличении чисел в файле.png)
