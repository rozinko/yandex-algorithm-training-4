# E. Удаление медиан

Задана последовательность чисел ai длиной n. Из него необходимо последовательно удалять медианы.

Медиана в этой задаче определяются следующим образом:

* Если количество чисел в последовательности нечетно, то медиана — число, стоящее точно в середине упорядоченной по возрастанию последовательности.
* Если количество чисел в последовательности чётно, то медианой последовательности является:
  * Меньшее из двух стоящих посередине чисел упорядоченной по возрастанию последовательности, если два средних различны.
  * Любое из двух стоящих посередине чисел упорядоченной по возрастанию последовательности, если два средних равны.

Определите в каком порядке будут удалены элементы последовательности.

## Формат ввода

В первой строке дано одно натуральное число n — количество элементов последовательности (1 ≤ n ≤ 10^5).

Во второй строке содержатся n натуральных чисел ai​ — элементы последовательности (1 ≤ ai ≤ 10^9).

## Формат вывода

Выведите n чисел — порядок удаления чисел из последовательности.

## Пример 1

### Ввод

```plain
3
19 3 8
```

### Вывод

```plain
8 3 19
```

## Пример 2

### Ввод

```plain
4
1 2 4 2
```

### Вывод

```plain
2 2 1 4
```
