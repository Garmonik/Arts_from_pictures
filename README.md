# Arts from pictures #

## Данный проект создан для преобразования фотографий в арты в разных стилях. ##

### ascii_apt_black.py ###

Первая программа была самой основной и из нее пошли все остальные. Для реализации были использованы библиотеки pygame и opencv. Основная суть заключается в том, что нужно переести фотографию в черно-белую, а затем внести ее в многомерный массив. Далее необходимо разбелить все пиксели по цветам и вставить один из следующих символов, '.-*+=o%S@W#', для того чтобы получить арт нарисованный с помощью ASCII символов.

### ascii_apt_color.py ###

Вторая программа была логическим продожением первой. Суть в том, что теперь мы кроме ASCII символов добавили еще и цвет для них, что привело нас к итоговому формату арта.

### pixel_art.py ###

Третья программа была уже логическим продолжением первых двух. Здесь отказываемся от ASCII символов и просто делим фото на пиксели, которые кладем в массив и далее проводим обработку по цвету, что в итоге приводит к итогу.

### matrix_apt.py ###

Четвертая программа копирует глаза Нео из фильма Матрица. Для этого необходимо было создать полотно, на котором постоянно будут бегать сверху-вниз японские символы (алфовит катакана). А далее нужно было использую фото провести обработку аналогичную программам __ascii_apt_color.py__ и __pixel_art.py__.

## Пример ##

### Исходное изображение ###

![Исходное изображение](https://github.com/Garmonik/Arts_from_pictures/blob/main/img/test1.jpg)

### ASCII_black изображение ###

![ASCII_black](https://github.com/Garmonik/Arts_from_pictures/blob/main/res/ascii_apt_black.png)

### ASCII_color изображение ###

![ASCII_color](https://github.com/Garmonik/Arts_from_pictures/blob/main/res/ascii_apt_color.png)

### PIXEL изображение ###

![PIXEL](https://github.com/Garmonik/Arts_from_pictures/blob/main/res/pixel_apt.png)

### MATRIX изображение ###

![MATRIX](https://github.com/Garmonik/Arts_from_pictures/blob/main/res/matrix_apt.png)
