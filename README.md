# Ex03 Time Table
## Date:

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
<<html>
<head>
<title>slot Timetable</title>    
</head>
<body>
<center>
<img src="./logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="brown">
<caption><b>SLOT TIME TABLE - Iyalarasu.C (23014041)</b></caption>
<tr align="center">
<th bgcolor="red">Day/Time</th>
<th bgcolor="green">Monday</th>
<th bgcolor="green">Tuesday</th>
<th bgcolor="green">Wednesday</th>
<th bgcolor="green">Thursday</th>
<th bgcolor="green">Friday</th>
</tr>
<tr align="center">
<th bgcolor="pink">8-10</th>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>EINGINEERING DESIGN AND MODELLING</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
</tr>
<tr align="center">
<th bgcolor="pink">10-12</th>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="pink">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="pink">1-3</th>
<td>PHYSICS FOR QUANTUM COMPUTING</td>
<td>EINGINEERING DESIGN AND MODELLING</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr align="center">
<th bgcolor="pink">3-5</th>
<td>FREE SLOT</td>
<td>SOFT SKILLS</td>
<td>FREE SLOT</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
<td>PHYSICS FOR QUANTUM COMPUTING</td>
</tr>
</table>
<br>
<table align="center" cellspacing="5" cellpadding="2" border="2"bgcolor="bluse">
<tr align="center">
<th>s. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19PH214</td>
<td>PHYSICS FOR QUANTUM COMPUTING (PQC)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING(C PROGRAME)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA201</td>
<td>MATRIX AND CALCULUS ALGEBRA (MAT)</th>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY701</td>
<td>SOFT SKILLS (SS)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI302</td>
<td>EINGINEERING DESIGN AND MODELLING</td>
</tr>
</table>
</body>
</html>





## OUTPUT
![image](https://github.com/ALLAMSESANK/slot/assets/147120920/77db974a-2fed-46c8-8cf6-56e19f6a291b)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
