# Cryptography-02-ECPoint
 
Скрипт який виконує завдання: tasks.py

- [ ] BasePointGGet (не зробив, не можу зрозуміти що він має повернути)
- [x] ECPointGen - виконується при ініціалізації класу
- [x] IsOnCurveCheck - метод класу, який повертає True або False. True в випадку коли точка належить еліптичній кривій, False в випадку коли точка не належить еліптичній кривій
- [x] AddECPoints - окрема функція яка повертає об'єкт класу ECPoint. Обчислення виконуєтья згідно до формули з презентації
- [x] DoubleECPoints - метод класу ECPoint, який повертає подвоєну точку. Обчислення виконуєтья згідно до формули з презентації
- [x] ScalarMult - метод класу ECPoint, який повертає нову об'єкт класу ECPoint нової точки. Обчислення виконуєтья згідно до формули з презентації
- [x] ECPointToString - метод класу ECPoint, який повертає стрічку "[x, y]", де `x` - належить осі абсцис, а `y` - належить осі ординат
- [x] PrintECPoint - метод класу ECPoint, який нічого не повертая, викликає функцію print() для виведення результату методу ECPointToString() класу ECPoint

Запускати tasks.py з консолі, для того, щоб можна було ввести наступні значення:

- a - для рівняння еліптичної кривої
- b - для рівняння еліптичної кривої

Скрипт tasks.py виконує всі завдання зазначені в документі