
# Итоговая проверочная работа.

## Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

### Алгоритм решения:
1. Делаем перебор значений из исходного массива
2. Проверяем каждое значение из массива на соответствие условию: `длина строки меньше или равна трём`
3. Если строка удовлетворяет условию кладем значение в новый массив
4. Повторяем пункты `2` и `3` до тех пор пока не достигнем конца исходного массива
5. Возвращаем новый заполненый массив как результат

### Блок-схема алгоритма:
![Диаграмма](diagramm\Diagram.drawio.png)

### Программа:
Для запуска программы перейдите в папку `task` и запустите команду через терминал:
```
dotnet run 
```
Далее введите значения через пробел, например:
```
Введите значения через пробел: 254 world sun 3 hello
```
Пример вывода программы:
```
[254, world, sun, 3, hello] -> [254, sun, 3]
```