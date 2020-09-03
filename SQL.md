<h1>Creating a table</h1><br>
(We will be working with a table called emp)<br><br>
<b>create table emp(eno int, ename varchar(120), job varchar(120), deptno int, salary int);</b><br>
int and varchar are the data types which we have to give in SQL and eno, ename, job, deptno,salary are the columns of the table.<br>
The (120) after varchar represents the number of bytes of data allowed to be stored in that row (As varchar datatype in this case). Don't worry about this byte guessing thing. Professionals are paid huge loads of money to just guess the appropriate number of byte to store (Heard this in a tutorial, Don't quote me. Point is, Chill lol)<br>

<b>Tip:</b> I got confused a lot as to if columns were the vertical section or the horizontal ones. In the end I came up with a simple short form to help me with this.<br>
<b>VC-HR</b> where VC= Vertical-Columns (Columns are vertical) and HR= Horizontal-Columns.<br>
<br>
<br>
<h1>Actually Inserting A Value In The Empty Table We Made:</h1><br>
<b>insert into emp(eno, ename, job, deptno, salary) values (1, 'a','manager', 21, 1000),(2, 'b', 'clerk', 22,2000), (3,'c','janitor',23,3000), (4, 'd','intern',24, 4000);</b>
<br>
Here in "insert into emp(eno.." You can replace the table names to which ever tables you want to fill the values with. Change the values section accordingly<br>
<br><br>
<h1>Some special functions and syntax we can use:</h1><br>
<b>1. count(): </b> It..Counts. lol. Try it.<br>
select count(*) from emp; --> Outputs the total number of rows.<br>
<b>2. having like: </b><br>
<i>Notes in progress..</i>
