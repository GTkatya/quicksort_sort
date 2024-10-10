# quicksort_sort
 программа на языке C, реализующая быструю сортировку
1. Функция swap используется для обмена значений двух элементов.
2. Функция partition выбирает последний элемент массива в качестве опорного элемента (pivot), разделяет массив на две части относительно опорного элемента и возвращает индекс опорного элемента после разделения.
3. Функция quickSort реализует рекурсивную быструю сортировку. Она вызывает partition, чтобы разделить массив на две части, и затем рекурсивно вызывает себя для сортировки левой и правой частей.
4. В функции main создается массив arr, его размер вычисляется, выводится исходный массив, вызывается функция quickSort для сортировки, и выводится отсортированный массив.
