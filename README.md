# Ex03 Time Table
## Date:31.10.2023

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<head>
<title>Slot Timetable</title>
</head>
<center>
<img src="logo.png" height="100" width="500">
</center>
<body >
<hr>
<table align="center" width="500" cellspacing="2" cellpadding="4"
border="5" bgcolor="yellow">
<caption><b>SLOT TIME TABLE - ROHITH V(23012490)</b>
</caption>
<tr align="center">
<th bgcolor="white">Day/Time</th>
<th bgcolor="white">Monday</th>
<th bgcolor="white">Tuesday</th>
<th bgcolor="white">Wednesday</th>
<th bgcolor="white">Thursday</th>
<th bgcolor="white">Friday</th>
</tr>
<tr align="center">
<th bgcolor="white">8-10</th>
<td>English</td>
<td>English</td>
<td>Web</td>
<td></td>
<td></td>
</tr>
<tr align="center">
<th bgcolor="white">10-12</th>
<td></td>
<td>CAL</td>
<td></td>
<td>Web</td>
<td>CAL</td>

</tr>
<tr align="center">
<th bgcolor="white">12-1</th>
<td colspan="5">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="white">1-3</th>
<td>PHY</td>
<td></td>
<td>CA</td>
<td>C-PROG</td>
<td>Web</td>
</tr>
<tr align="center">
<th bgcolor="white">3-5</th>
<td></td>
<td>SOFTSKILLS</td>
<td>CA</td>
<td>PHY</td>
<td></td>
</tr>
</table>
<br>
<br>
<table align="center" width="500" cellspacing="2" cellpadding="4" border="5"
>
<tr align="center">
<th>S.No</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td>1</td>
<td>19AI414</td>
<td>Fundamentals Of Web Development(Web)</td>
</tr>
<tr>
<td>2</td>
<td>19MA201</td>
<td>Calculus and matrix algebra(CAL)</td>
</tr>
<tr>
<td>3</td>
<td>19EN101</td>
<td>Communicate English(eng)</td>
</tr>
<tr>
<td>4</td>
<td>19PH214</td>
<td>Physics for quantum computing(Phy)</td>
</tr>
<tr>
<td>5</td>
<td>19EY701</td>
<td>Soft Skills</td>
</tr>
<tr>
<td>6</td>
<td>19CS305</td>
<td>Computer Architecture(CA)</td>
</tr>
<tr>
<td>7</td>
<td>19AI304</td>
<td>C-Programming(C-Prog)</td>
</tr>
</table>
</body>
</html>
```
### OUTPUT:
![Alt text](<Screenshot 2023-11-15 132117.png>)

## RESULT:
The program for creating slot timetable using basic HTML tags is executed successfully.
