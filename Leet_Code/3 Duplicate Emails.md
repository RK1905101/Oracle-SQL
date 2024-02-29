*PROBLEM* 

<img width="296" alt="image" src="https://github.com/RK1905101/Oracle-SQL/assets/64470404/20e57922-d4d6-4e5b-a688-9ebb8f4442fa">


*SOLUTION*


__select email as Email__ <br>
__from person__ <br>
__where email is not null__ <br>
__group by email__ <br>
__having count (email) > 1__ <br>

*RESULT*


<img width="443" alt="image" src="https://github.com/RK1905101/Oracle-SQL/assets/64470404/ee1433d1-0288-4f7d-851e-65779c2a3791">
