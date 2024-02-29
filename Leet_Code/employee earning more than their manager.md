*PROBLEM* 

<img width="354" alt="image" src="https://github.com/RK1905101/Oracle-SQL/assets/64470404/932a9146-0d7c-43a8-ab98-28f0fd6c16ea">

*SOLUTION*

- _self join or inner join will be used here._ <br>
 _column name is employee_

__select e2.name as employee__  <br>
__from employee e1  join employee e2__  <br>
__on e1.id = e2.managerid__  <br>
__where e1.salary < e2.salary;__  <br>
