
# Игра "Угадай число"

Этот проект содержит реализацию игры "Угадай число", где цель состоит в том, чтобы предсказать случайно выбранное число за наименьшее количество попыток. Включает различные стратегии для угадывания числа, от случайных догадок до более сложных алгоритмов, которые корректируют догадку в зависимости от того, выше или ниже фактическое число по сравнению с текущей догадкой.

## Описание

В ноутбуке представлены следующие функции:

- `random_predict`: Делает случайную догадку и проверяет, соответствует ли она целевому числу.
- `game_core_v2`: Начинает с случайного числа, а затем постепенно корректирует догадку на основе того, выше или ниже актуальное число.
- `game_core_v3`: Использует подход бинарного поиска для угадывания числа, что значительно сокращает количество попыток, необходимых для нахождения правильного числа.
- `score_game`: Оценивает эффективность алгоритма угадывания за 10000 итераций, чтобы определить среднее количество попыток, необходимых для правильного угадывания.

Дополнительно, есть вариант алгоритма, который взаимодействует с пользователем, запрашивая обратную связь для динамической корректировки диапазона угадывания.

## Установка

Для работы с этим проектом вам понадобится Python и пакеты, перечисленные в `requirements.txt`.

1. Клонируйте этот репозиторий на свою локальную машину.
2. Убедитесь, что у вас установлен Python.
3. Установите необходимые пакеты, используя:

```bash
pip install -r requirements.txt
```

## Использование

Запустите ноутбук Jupyter `baseline.ipynb`, чтобы увидеть алгоритмы в действии. Вы можете экспериментировать с кодом, чтобы увидеть, как различные стратегии показывают себя с точки зрения эффективности угадывания чисел.
