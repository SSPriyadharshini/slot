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
<body>
<center>
<img src="/static/logo.png"height+"100" width="540">
</center>
<br>
<table alihn="center width="540" cellspacing="2" cellpading="4" border="5" bgcolor-"black">
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="centre">
<th bgcolor="yellow">8-10</th>
<td>FREE SLOT</td>
<td>PYTHON PROGRAMMING</td>
<td>FUNDAMENTALES OF WEB APPLICATION DEVELOPMENT</td>
<td>CALCUS AND MATRIX ALGEBRA</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr align="centre">
<th bgcolor="yellow">10-12</th>
<td>PRINCIPLE OF CHEMISTRY IN ENGINEERING</td>
<td>CALCUS AND MATRIX ALGEBRA</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALES OF WEB APPLICATION DEVELOPMENT</td>
<td>PHYSICS FOR QUANTUM COMPUTING</td>
</tr>
<tr align="center">
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>COMMUNICATIVE ENGLISH</td>
<td>PRINCIPLE OF CHEMISTRY IN ENGINEERING</td>
<td>FREE SLOT</td>
<td>SOFT SKILLS</td>
<td>FUNDAMENTALES OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>PHYSICS FOR QUANTUM COMPUTING</td>
<td>FREE SLOT</td>
<td>PYTHON PROGRAMMING</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
</table>
<tr>
<table align"center" cellspacing="2" cellpading="4" border="2">
<tr align="center">
<th>S.NO.</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td align="center">Fundamentales of web apllication Development(FWAD)</td>
</tr>
<br>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19PH214</td>
<td align="center">Physics for quantum computing(PHY)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EN101</td>
<td align="center">Communicative English(ENG)</td>
</tr>
<br>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td align="center">Principle of Chemistry in engineering(CHY)</td>
</tr>
<br>
<td align="center">5.</td>
<td align="center">19AI301</td>
<td align="center">Python Programming(PY)</td>
</tr>
<br>
<td align="center">6.</td>
<td align="center">19MA201</td>
<td align="center">Calcus and matrix alegbra(MAT)</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19EY701</td>
<td align="center">Soft Skills(SS)</td>
</tr>
</table>
</body>
</html>
```
## OUTPUT


![Alt text](<Screenshot (4).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
