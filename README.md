## IntSet

Так называемый, IntSet, - это самое обычное множество, элементы которого
являются целыми неотрицательными числами.

Для этой структуры данных характерны методы множеств:

- объединение (union)
```
[1, 2, 3] ∪ [3, 4, 5] -> [1, 2, 3, 4, 5]
```
- пересечение (intersection)
```
[1, 2, 3] ∩ [2, 3, 4] -> [2, 3]
```
- вычитание (minus)
```
[1, 2, 3] - [2, 3, 4] -> [1]
```
- исключающее ИЛИ (difference)
```
[1, 2, 3] \ [2, 3, 4] -> [1, 4]
```

и еще несколько методов, схожих с методами коллекций на Java:

- добавление (add)
- удаление (remove)
- проверка существование элемента (contains)
- проверка на вхождение одного множества в другое (isSubsetOf)

**Вашей задачей** будет реализация такой структуры данных. Вам необходимо
реализовать интерфейс `IntSet` и убедиться, что проходят тесты.

> Всю необходимую информацию по тому, как получать задания и отправлять решения 
можно найти [на этой страние](https://github.com/tcibinan/data-structures-course).