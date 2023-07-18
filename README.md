<h1>Completing an SQL join</h1>

<h2>Description</h2>
In this project, I'll be working on an SQL join which enables us to combine tables containing a shared column. This is super helpful when you need to 'join' information in different tables.<br/> 

<br/>

<h2>Project</h2>

<p align="left">
  <b>1. </b>Let's start off with what we have for 'machines' data.<br/>
  <br/>
<img src="https://i.imgur.com/Bhkfgmz.png" height="80%" width="80%" alt="From Machines"/>
  <br/>
  <br/>
<b>2. </b>Let's perform an 'INNER JOIN' between the machines and employees tables on the device_id column. An inner join, is what the two tables in the clause, have in common.<br/>
        <br/>
    <img src="https://i.imgur.com/LoYv5qA.png" height="40%" width="40%" alt="Inner Join Viz"/>
<br/>
    <img src="https://i.imgur.com/7mr3mz8.png" height="80%" width="80%" alt="Inner Join"/>
<br/>
  <br/>
    <img src="https://i.imgur.com/rF2nf91.png" height="80%" width="80%" alt="Inner Join"/>
<br/>
<br/>
<b>3. </b>Run the SQL query to connect 'machines' and 'employees' tables through a 'RIGHT JOIN'. In a right join, all records from the table referenced <i>after</i> RIGHT JOIN are included in the result. In this query, all records from the <b>'employees'</b> table are included regardless if they have a machine or not.<br/>
  <br/>
    <img src="https://i.imgur.com/TM8ng84.png" height="80%" width="80%" alt="Right Join"/><br/><br/>
      <img src="https://i.imgur.com/8Zx7mSF.png" height="80%" width="80%" alt="Right Join"/><br/>
  <br/>  
  <br/>
<b>4. </b>If we run a 'LEFT JOIN', all the records from the tables referenced <i>before</i> LEFT JOIN will be included in the results. In this case, all records from <i>'machines'</i> table will be included regardless if they have been assigned to an employee.<br/>
 <br/>
    <img src="https://i.imgur.com/gKT3LeP.png" height="80%" width="80%" alt="Left Join"/><br/>
<br/>
  <img src="https://i.imgur.com/bTZLLhu.png" height="80%" width="80%" alt="Left Join"/><br/>
<br/>
  This is a rather quick and deep dive into 'JOIN'. This allows us to combine data from multiple tables from a database. 
  <br/>
    <br/>
      <br/>
  
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
