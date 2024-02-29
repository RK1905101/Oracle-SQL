*PROBLEM* 

<img width="451" alt="image" src="https://github.com/RK1905101/Oracle-SQL/assets/64470404/56c2b080-34ba-43c2-9002-6f9be5ac0413">

 
*SOLUTION*

_/* Write your PL/SQL query statement below */_

_--select * from person;_ <br>
_--select * from address;_

__select firstname, lastname, city, state from person p__ <br>
__left join address a__ <br>
__on p.personid = a.personid__ <br>


*RESULT*

<img width="377" alt="image" src="https://github.com/RK1905101/Oracle-SQL/assets/64470404/a4e825ae-1475-4193-9bff-a2acef3285c1">
