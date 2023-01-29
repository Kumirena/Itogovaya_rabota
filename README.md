 Itogovaya_rabota
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа.
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.
При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.* 

Алгоритм решения:

1. Объявляем исходный массив, задаем его размерность и наполняем его значениями (по условию задачи),  
объявляем второй массив, равный длине исходного.
2. Проверяем каждый элемент массива на соответствие условию: длина строки меньше либо равна 3 символа.
3. Если условие соблюдается, отправляем элемент во второй массив.
4. Если условие не соблюдается, то переменная count увеличивается на 1 и возвращается в цикл for (где i увеличивается на 1), и снова проверяется соответствие условию.
5. Перебор элементов продолжается до конца длины массива.
6. Возвращаем новый массив, как результат.

## Блок-схема алгоритма:
![] ()