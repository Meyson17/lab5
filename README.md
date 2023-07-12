<p></p>

<h2 align="center">ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ПРОФЕССИОНАЛЬНОГО ОБРАЗОВАНИЯ <br> «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ» <br> КАФЕДРА ИНФОРМАТИКИ </h2>
<p align="center">Лабораторная работа №5 <br>
по курсу «Web-технологии, языки и средства создания web-приложений» 

<p align="center"><b>"Java Script"</b><p>
<p align="right"><b>Выполнил: </b> студент 231 группы Рыжков Владимир</p>
<p  align="right"><b>Принял: </b> Соболев Е. И., старший преподователь</p>
<br>
<br>
<br>
<p align="center">Южно-Сахалинск <br> СахГУ <br> 2023</p>
<h2> Введение </h2>
<p>Лабораторные работы по дисциплине «Web-технологии, языки и средства создания web-приложений» предназначены для освоения полученных теоретических знаний на практике. Перед началом первой лабораторной работы были поставлены цели: <br>
<ol>
  <li>Овладеть навыками работы с языком гипертекстовой разметки HTML, в частности научиться основам Java Script, создавать простые скрипты для решения задач.
</ol>
В соответствии с данными целями необходимо решить следующие задачи:
<ol>
   <li> Написать скрипты для решения данных задач.
   </ol>
Для реализации данной работы будет использоваться Visual Studio Code. Выполнение кода будет происходить в браузере Microsoft Edge.
</p>
<h2>Решение задач</h2>
<p>В первой части были выполнены 23 коротких задачи: </p>
<code>

   <p>задание 1</p>
   
<script>
let str='hdfgv';
document.write(str[0]+','+str[1]+','+str[4]);
</script>

<p>задание 2</p>
<script>
let secondHous=60*60;
document.write('в часу '+secondHous+ ' секунд');
</script>

<p>задание 3 </p>

<script>
var num=1;
num+=12;
num-=14;
num*=5;
num/=7;
num++;
num--;
alert(num);
</script>

<p>задание 4 </p>

<script>
var num=3;
alert(num);
</script>

<p>задание 5</p>

<script>
var a=10, b=2;
document.write(a+b);
document.write(a-b);
document.write(a*b);
document.write(a/b);
</script>

<p>задание 6</p>

<script>
var c=15, d=2;
resut=c+d;
document.write(resut);
</script>

<p>задание 7</p>

<script>
var c=5, a=10, b=2;
resut=c+a+b;
document.write(resut);
</script>

<p>задание 8</p>

<script>
var a=17, b=10;
c=a+b;
d=7;
result=c+d;
document.write(result);
</script>

<p>задание 9</p>

<script>
let secondHous=60*60;
let secondSut=secondHous*24;
let secondManth=secondSut*31;
document.write('в часу '+secondHous+ ' секунд'+' в сутках '+secondSut+ ' секунд'+' в месяце '+secondManth+ ' секунд');
</script>

<p>задание 10</p>

<script>
let hour=12;
let minute=50;
let second=37;
document.write(hour+':'+minute+':'+second);
</script>

<p>задание 11</p>

<script>
var a=17
result=a*a;
document.write(result);
</script>

<p>задание 12</p>

<script>
document.write(  [1, 2, 3, 4, 5, 6, 7,8,9,10].filter(n => n % 2 == 0).reduce( (sum, n) => sum + n**0.5, 0 ));
</script>

<p>задание 13<p>
  
<script>
var apple = 1.15, orange = 2.30
result= apple + orange;
document.write(result);
</script>

<p>задание 14<p>
  
<script>
var x=5;
alert(x++);
</script>

<p>задание 15<p>
  
<script>
var result = []+false-null+true;
document.write(result);
</script>

<p>задание 16</p>

<script>
let y=1;
let x=y=2;
console.log(x);
</script>

<p>задание 17<p>
  
<script>
var result = []+1+2;
document.write(result);
</script>

<p>задание 18<p>

<script>
a6=5%3;
a7=3%5;
a8=5+'3';
a9='5'+3;
a10=75+'kg'
document.write(a6);
document.write(a7);
document.write(a8);
document.write(a9);
document.write(a10);
</script>

<p>задание 19<p>
  
<script>
const heigth =23;
const width =10;
const s= heigth * width;
document.write(s);
</script>

<p>задание 20<p>
  
<script>
const heigthC =23;
const dC =10;
const v= Math.PI*Math.pow(dC/2,2)*heigthC;
document.write(v);
</script>

<p>задание 21<p>
  
<script>
let s = 2e6, p=10, years=5;
let pereki = (s*(p/100)*years);
document.write('сумма переплат '+ pereki +' руб');
</script>

<p>задание 22<p>
  
<script>
let str="привет", num=123, flag=true, txt="true";
document.write(typeof str =='string');//true
document.write(typeof num =='number');//true
document.write(typeof flag =='boolean');//true
document.write(typeof txt =='string');//true
</script>

<p>задание 23<p>
  
<script>
const num = 5;
result = num*-1;
document.write(result);
</script>
</code>
<p>Во второй части были выполнены задачи с ресурса codewars.com:</p>
https://www.codewars.com/users/Meyson172/completed_solutions
<h2>Вывод</h2>
<p>В ходе лабораторной работы были изучены элементы языка Java script, а так же рассмотрены способы задания переменных, операций над ними, была проведена работа с циклами и функциями. Результатом лабораторной работы являются полностью решенные задачи.</p>
