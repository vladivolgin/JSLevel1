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
              
              ! [image](https://user-images.githubusercontent.com/87894035/151814422-b0737850-de4d-4ff5-b2d6-a35137a09a54.png)

        3 Вывести в консоль значения выражений и объяснить почему получились такие значения
              используя комментарии к каждому выражению:
              10 + 10 + "10";
              10 + "10" + 10;
              10 + 10 + +"10"; (обратите внимание на пробелы, пишите также)
              10 / -"";
              10 / +"2,5"; (да здесь запятая, это не опечатка)
              Объяснения пишите в таком формате:
