 Vegetable market

Задача 5. Зеленчукова борса
Градинар продавал реколтата от градината си на зеленчуковата борса. 
Продава зеленчуци за N лева на килограм и плодове за M лева за килограм.
Напишете програма, която да пресмята приходите от реколтата
в евро ( ако приемем, че едно евро е равно на 1.94лв).
Вход
От конзолата се четат 4 числа, по едно на ред:
• Първи ред – Цена за килограм зеленчуци – число с плаваща запетая
• Втори ред – Цена за килограм плодове – число с плаваща запетая
• Трети ред – Общо килограми на зеленчуците – цяло число
• Четвърти ред – Общо килограми на плодовете – цяло число
Ограничения: Всички числа ще са в интервала от 0.00 до 1000.00
Изход
Да се отпечата на конзолата едно число с плаваща запетая: приходите от всички плодове и зеленчуци в
евро.
Примерен вход и изход
Вход Изход Обяснения
0.194
19.4
10
10
101 Зелечуците струват – 0.194лв. * 10кг. = 1.94лв.
Плодовете струват – 19.4лв. * 10кг. = 194лв.
Общо – 195.94лв. = 101евро

1.5
2.5
10
10
20.6185567010309

Подсказка
Реализирайте задачите така, че да имате конзолно MVC приложение:
• Главна програма с клас Program, чиято единствена задача ще е да създаде един обект от клас
SomethingActionController() с оператор new
SomethingActionController something= new SomethingActionController(); ,
Където Something може да бъде заменено с името на класа от оригиналната задача. Т.е. по смисъла
на данните, които се обработват в конкретната задача.
• Клас SomethingActionController(), който управлява обектите Something и Display за да може
приложението да въвежда и извежда необходимите данни.
• Клас Something, в който да съхранявате необходимите за конкретната задача данни
• Клас Display, който се грижи да въвежда и извежда данни, които да предава на класа
Something
