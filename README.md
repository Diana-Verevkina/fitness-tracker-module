# Модуль фитнес-трекера

## Описание
Данная программа представляет из себя модуль для фитнес-трекера, 
написанный с использованием парадигмы ООП.

Этот модуль рассчитывает и отображает результаты тренировки.

## Структура проекта
Класс InfoMessage создает сообщение с результатами тренировки:
"Тип тренировки", "Длительность", "Дистанция", "Ср. скорость", "Потрачено ккал"

Класс Training является родительским классом для классов Running, SportsWalking, Swimming.

## Что делает программа
В функцию main передается набор параметров, характерных для необходимой тренироки, 
после программа производит вычисления и выводит информацию о тренировке. 

### Пример

> Передаем параметры: 

```sh
'SWM': [720, 1, 80, 25, 40]
```

> Получаем:
```sh
Тип тренировки: Swimming;

Длительность: 1.000 ч.; 

Дистанция: 0.994 км; 

Ср. скорость: 1.000 км/ч; 

Потрачено ккал: 336.000.
```

# Запуск файла

Для запуска файла необходимо ввести команду
```sh
 python3 homework.py
```
в терминале, находясь в папке проекта.