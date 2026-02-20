<center><h2>Experiment 6</h2></center>

<h4>Queries:</h4>

### 1. Display empno, ename, deptno from employee table. Instead of display department numbers display the related department name (Use decode function). 
~~~sql
SELECT e.empno, e.ename, e.deptno, d.dname
 FROM employee e
 JOIN department d
 ON e.deptno = d.deptno;
 ~~~
