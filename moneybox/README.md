<h1>Копилка</h1>
<p>Реализуйте класс MoneyBox, для работы с виртуальной копилкой.</p>
<p>Каждая копилка имеет ограниченную вместимость, которая выражается целым числом – количеством монет, которые можно положить в копилку. Класс должен поддерживать информацию о количестве монет в копилке, предоставлять возможность добавлять монеты в копилку и узнавать, можно ли добавить в копилку ещё какое-то количество монет, не превышая ее вместимость.</p>
<p>Класс должен иметь следующий вид</p>
<pre>
class MoneyBox:
    def __init__(self, capacity):
        # конструктор с аргументом – вместимость копилки
    def can_add(self, v):
        # True, если можно добавить v монет, False иначе
    def add(self, v):
        # положить v монет в копилку
</pre>
<p>При создании копилки, число монет в ней равно 0.</p>
<p>Примечание:</p>
<p>Гарантируется, что метод add(self, v) будет вызываться только если can_add(self, v) – True﻿.</p>