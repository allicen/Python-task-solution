<h1>Средние оценки</h1>
<p>Имеется файл с данными по успеваемости абитуриентов. Он представляет из себя набор строк, где в каждой строке записана следующая информация:</p>
<p>Фамилия;Оценка_по_математике;Оценка_по_физике;Оценка_по_русскому_языку</p>
<p>Поля внутри строки разделены точкой с запятой, оценки — целые числа.</p>
<p>Напишите программу, которая считывает файл с подобной структурой и для каждого абитуриента выводит его среднюю оценку по этим трём предметам на отдельной строке, соответствующей этому абитуриенту.</p>
<p>Также в конце файла, на отдельной строке, через пробел запишите средние баллы по математике, физике и русскому языку по всем абитуриентам.</p>
<p>В качестве ответа на задание прикрепите полученный файл со средними оценками.</p>
<p>Примечание. Для разбиения строки на части по символу ';' можно использовать метод split следующим образом:</p>
<pre>
print('First;Second-1 Second-2;Third'.split(';'))
# ['First', 'Second-1 Second-2', 'Third']
</pre>
<p><strong>Sample Input:</strong></p>
<pre>
Петров;85;92;78
Сидоров;100;88;94
Иванов;58;72;85
</pre>
<p><strong>Sample Output:</strong></p>
<pre>
85.0
94.0
71.666666667
81.0 84.0 85.666666667
</pre>