<h1>Класс исключения</h1>
<p>Реализуйте класс PositiveList, отнаследовав его от класса list, для хранения положительных целых чисел.</p>
<p>Также реализуйте новое исключение NonPositiveError.</p>
<p>В классе PositiveList переопределите метод append(self, x) таким образом, чтобы при попытке добавить неположительное целое число бросалось исключение NonPositiveError и число не добавлялось, а при попытке добавить положительное целое число, число добавлялось бы как в стандартный list.</p>
<p>В данной задаче гарантируется, что в качестве аргумента x метода append всегда будет передаваться целое число.</p>
<p>Примечание:</p>
<p>Положительными считаются числа, строго большие нуля.</p>