# JSLevel1
В этом репозитории собраны задания, предложенные на курсе ![image](https://user-images.githubusercontent.com/87894035/151812209-e8457968-fd43-4d1e-bceb-07cac0335db6.png) по изучению основ JavaScript. 






# 1.Основы языка JavaScript. 
        1 Задать температуру в градусах по Цельсию. Вывести в alert соответствующую температуру в
         градусах по Фаренгейту. Подсказка: расчёт идёт по формуле:
                Tf = (9 / 5) * Tc + 32;
             где Tf – температура по Фаренгейту, Tc – температура по Цельсию
            
            Основной код программы :
          
                <!DOCTYPE html>
                <html lang="en">
                <head>
                    <meta charset="UTF-8">
                    <title>Document</title>
                </head>
                <body>
                    <script>
                    'use strict';
                    let Tcelsius = 23;
                    let Tfahrenheit = (9/5)* Tcelsius + 32;
                    alert (Tfahrenheit);  
                    </script>
                </body>
                </html> 

            



        2 Объявить две переменные: admin и name. Записать в name строку "Василий". Скопировать
              значение из name в admin. Вывести в консоль переменную admin (должно вывести "Василий").
              
              Основной код работы :
              
                        <!DOCTYPE html>
                        <html lang="en">
                        <head>
                            <meta charset="UTF-8">
                            <title>Document</title>
                        </head>
                        <body>
                            <script>
                               'use strict';
                               let name = 'Василий';
                               let admin = name;
                                console.log(admin);
                            </script>
                        </body>
                        </html>

        3 Вывести в консоль значения выражений и объяснить почему получились такие значения
              используя комментарии к каждому выражению:
              10 + 10 + "10";
              10 + "10" + 10;
              10 + 10 + +"10"; (обратите внимание на пробелы, пишите также)
              10 / -"";
              10 / +"2,5"; (да здесь запятая, это не опечатка)
              
              Основной код программы:
              
              <!DOCTYPE html>
                <html lang="en">
                <head>
                    <meta charset="UTF-8">
                    <title>Document</title>
                </head>
                <body>
                    <script>
                        'use strict';
                         let result1 = 10 + 10 + "10";
                         //первые два элемента складываются как числа и т.к. третий элемент является строкой сумма первых двух элементов преобразуется в строг. две строки конкатенируются в "2010"
                         let result2 = 10 + "10" + 10;
                         //все элементы преобразуются в строки. результат: "101010"
                         let result3 =  10 + 10 + +"10"; 
                         //третий элемент при помощи унарного плюса преобразуется в число. результат: "30"
                         let result4 = 10 / -"";
                         //в результате преобразования унарным минусом пустой строки получается отрицательный минус. при делении числа на отрицательный ноль результат равен "-Infinity"
                         let result5 = 10 / +"2,5"; 
                         //ошибка преобразования в число (не совсем понял почему). результат NaN
                    </script>
                </body>
                </html>
            

