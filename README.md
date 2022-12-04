# mtk labs
<блок знакомства с языком flow>

1) Написать фукнцию, преобразующую массив целых чисел в массив строк, например: [1, 2, 3] в ["1", "2", "3"], распечатать этот массив. Использовать функции: map, i2s, strGlue, println.

2) Написать функцию, считающую сумму целых чисел в массиве: [1, 2, 3] в 6. Использовать функции: fold.

3) Написать функцию, fib(n : int) -> [int], вычисляющую n первых чисел фиббоначчи: 0, 1, 1, 2, 3, 5, .... Сделать ее а) рекурсивной б) с хвостовой рекурсией в) с использованием ссылок на массив, сложности O( n ). Использовать: fold, concat, refArrayPush

4) Дан массив целых чисел [n_1,...,n_k] и число m. Найти все пары индексов (i, j) такие, что n_i + n_j == m. Сигнатура функции: inds(a : [int], m : int) -> [Pair<int, int>]. Усложнение: сделать эту функцию сложности O(n log(n)), а не O(n^2). Использовать функции: foldi, makeTree, setTree, lookupTree.

 

<блок знакомства с парсерами и работы с AST>

5)  Реализуйте PEG-парсер для грамматики простых арифметических выражений (целые константы, операции + и *), который порождает дерево синтаксического разбора. Используйте библиотеку lingo. Преобразуйте дерево обратно в строку. Реализуйте калькулятор, вычисляющий значение арифметического выражения. 

6) Реализуйте калькулятор для обратной польской записи (RPN) арифметических выражений. Напишите функции перевода арифметический выражений в RPN и наоборот.

7) Расширьте язык арифметических выражений вычитанием, делением, сменой знака и переменными. Для полученного нового языка алгебраических выражений напишите функцию, которая вычисляет значение выражения при заданных значениях входящих в него переменных, которые могут быть рациональными.

8) Реализуйте функцию дифференцирования алгебраического выражения по заданной переменной. Напишите функцию упрощения, которая удаляет выражения вида 1 + 0 и x * 0.

9) Реализуйте функцию преобразования алгебраического выражения в рациональную функцию (отношение двух многочленов).

10) Реализуйте функцию упрощения рациональной функции по заданному набору тождеств.
