### 1. Напишите функцию для транспонирования матрицы 

### 2. Напишите функцию принимающую на вход только ключевые параметры и возвращающую словарь, где ключ — значение переданного аргумента, а значение — имя аргумента. Если ключ не хешируем, используйте его строковое представление. 

### 3. Возьмите задачу о банкомате из семинара 2. Разбейте её на отдельные операции — функции. Дополнительно сохраняйте все операции поступления и снятия средств в список.

### 4. Напишите функцию, которая принимает на вход строку — абсолютный путь до файла. Функция возвращает кортеж из трёх элементов: путь, имя файла, расширение файла.

### 5. Напишите однострочный генератор словаря, который принимает на вход три списка одинаковой длины: имена str, ставка int, премия str с указанием процентов вида «10.25%». В результате получаем словарь с именем в качестве ключа и суммой премии в качестве значения. Сумма рассчитывается как ставка умноженная на процент премии.

### 6. Создайте функцию генератор чисел Фибоначчи.

### Урок 7. Напишите функцию группового переименования файлов. Она должна:
#### 1. принимать параметр желаемое конечное имя файлов. При переименовании в конце имени добавляется порядковый номер.
#### 2. принимать параметр количество цифр в порядковом номере.
#### 3. принимать параметр расширение исходного файла. Переименование должно работать только для этих файлов внутри каталога.
#### 4. принимать параметр расширение конечного файла.
#### 5. принимать диапазон сохраняемого оригинального имени. Например для диапазона [3, 6] берутся буквы с 3 по 6 из исходного имени файла. К ним прибавляется желаемое конечное имя, если оно передано. Далее счётчик файлов и расширение. 3.Соберите из созданных на уроке и в рамках домашнего задания функций пакет для работы с файлами.

### Урок 8. Напишите функцию, которая получает на вход директорию и рекурсивно обходит её и все вложенные директории. Результаты обхода сохраните в файлы json, csv и pickle.
#### 1. Для дочерних объектов указывайте родительскую директорию.
#### 2. Для каждого объекта укажите файл это или директория.
#### 3. Для файлов сохраните его размер в байтах, а для директорий размер файлов в ней с учётом всех вложенных файлов и директорий.

### Урок 10. Создайте класс-фабрику.
#### 1. Класс принимает тип животного (название одного из созданных классов) и параметры для этого типа.
#### 2. Внутри класса создайте экземпляр на основе переданного типа и верните его из класса-фабрики. 