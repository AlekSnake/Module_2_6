# Module_2_6
 Дополнительное практическое задание по модулю*2
Дополнительное практическое задание по модулю: "Основные операторы"



Цель: Применить знания полученные в модуле, решив задачу повышенного уровня сложности



Задание "Слишком древний шифр":

Вы отправились в путешествие на необитаемый остров и конечно же в очередной вылазке в джунгли вы попали в ловушку местному племени (да-да, классика "Индиана Джонса").

К вашему удивлению, в племени были неплохие математики и по совместительству фантазёры.

Вы поняли это, когда после долгих блужданий перед вами появились ворота (выход из ловушки) с двумя каменными вставками для чисел.

В первом поле камни с числом менялись постоянно (от 3 до 20) случайным образом, а второе было всегда пустым.



К вашему счастью рядом с менее успешными и уже неговорящими путешественниками находился папирус, где были написаны правила для решения этого "ребуса". (Как жаль, что они поняли это так поздно :( ).



Во вторую вставку нужно было написать те пары чисел друг за другом, чтобы число из первой вставки было кратно(делилось без остатка) сумме их значений.



Пример кратности(деления без остатка):

1 + 2 = 3 (сумма пары)

9 / 3 = 3 (ровно 3 без остатка)

9 кратно 3 (9 делится на 3 без остатка)





Пример 1:

9 - число из первой вставки

1218273645 - нужный пароль (1 и 2, 1 и 8, 2 и 7, 3 и 6, 4 и 5 - пары; число 9 кратно сумме каждой пары)



Пример 2:

11 - число из первой вставки

11029384756 - нужный пароль (1 и 10, 2 и 9, 3 и 8, 4 и 7, 5 и 6 - пары; число 11 кратно сумме каждой пары)





К сожалению, у вас не так много времени, чтобы подбирать пароль вручную, шипы сверху уже движутся на вас (обожаю клише), тем более числа в первой вставке будут попадаться случайно.



Составьте алгоритм, используя циклы, чтобы в независимости от введённого числа n (от 3 до 20) программа выдавала нужный пароль result, для одного введённого числа.



Что является парой?:

Пары являются уникальными на примере следующего:

7 3 3 5 8

В этой последовательности уникальными парами являются:

Для первой 7: 73 73 75 78

Для второй 3: 33 35 38 (с первой 7 у этой 3 уже есть пара, поэтому её не берём).



Все пароли для чисел от 3 до 20 (для сверки):

3 - 12

4 - 13

5 - 1423

6 - 121524

7 - 162534

8 - 13172635

9 - 1218273645

10 - 141923283746

11 - 11029384756

12 - 12131511124210394857

13 - 112211310495867

14 - 1611325212343114105968

15 - 1214114232133124115106978

16 - 1317115262143531341251161079

17 - 11621531441351261171089

18 - 12151811724272163631545414513612711810

19 - 118217316415514613712811910

20 - 13141911923282183731746416515614713812911



Отдельно по числам, для большего понимания:

3 - 1+2

4 - 1+3

5 - 1+4 2+3

6 - 1+2 1+5 2+4

7 - 1+6 2+5 3+4

8 - 1+3 1+7 2+6 3+5

...

18 - 1+2 1+5 1+8 1+17 2+4 2+7 2+16 3+6 3+15 4+5 4+14 5+13 6+12 7+11 8+10

19 - 1+18 2+17 3+16 4+15 5+14 6+13 7+12 8+11 9+10

20 - 1+3 1+4 1+9 1+19 2+3 2+8 2+18 3+7 3+17 4+6 4+16 5+15 6+14 7+13 8+12 9+11

Примечания:

Можно использовать как цикл for, так и цикл while
Пары чисел подбираются от 1 до 20 для текущего числа.






Успехов!

