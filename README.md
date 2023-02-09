# week13

Ответы на вопросы:

1. Переменные объявляют через let и const.

2. console.log('Hello World');

3. let name = "Ilya";
   alert( `hello ${1} ` ); //hello 1
   alert( `hello ${"name"}` ); //hello name
   alert( `hello ${name}` ); //hello Ilya

4. let x = 5;  
   let y = 2;  
   let z = x + y;
   console.log(z); // 7

5. Способы подключения JavaScript:

1) внутри тегов <script></script> прямо перед закрывающим </body>
2) подключить через внешний файл:
<script src="путь_к_файлу_скрипта/script.js"></script>
3) инлайн, прямо в строке в конкретном теге

6. typeof str - синтаксис оператора
   typeof(str)- синтаксис функции
   Оператор typeof возвращает тип аргумента. Он работает со скобками или без скобок. Результат одинаковый.

7. function showX(x)
   {
   return x;
   }
   console.log(showX(28)); // 28

8. "" + 1 + 0 //результат выражения: '10'
   "" - 1 + 0 //результат выражения: -1
   true + false //результат выражения: 1
   6 / "3" //результат выражения: 2
   "2" * "3" //результат выражения: 6
   4 + 5 + "px" //результат выражения: '9px'
   "$" + 4 + 5 //результат выражения: '$45'
   "4" - 2 //результат выражения: 2
   "4px" - 2 //результат выражения: NaN
   7 / 0 //результат выражения: Infinity
   " -9 " + 5 //результат выражения: ' -9 5'
   " -9 " - 5 //результат выражения: -14
   null + 1 //результат выражения: 1
   undefined + 1 //результат выражения: NaN
   " \t \n" - 2 //результат выражения: -2

9. x = 5;
   x = 2;
   console.log(x); //2

10. x = 5;
    x -= 2;
    console.log(x); //3
