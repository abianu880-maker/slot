# Ex03 Time Table
## Date:27.09.2025

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
<body align="center">
    <img src="/static/logo.png" height="100" width="540"
</center>
<br>
<table align="center" width="540" cellpadding="4" border="5" bgcolor="pink">
<caption><b>SLOT TIME TABLE-ABILASHA R (25015770)</b></caption>
<tr align="center">
<th bgcolor="grey">Day/Time</th>
<th bgcolor="grey">Monday</th>
<th bgcolor="grey">Tuesday</th>
<th bgcolor="grey">Wednesday</th>
<th bgcolor="grey">Thursday</th>
<th bgcolor="grey">Friday</th>
<th bgcolor="grey">saturday</th>
</tr>
<tr align="center">
<th bgcolor="pink">8-10</th>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF C PROGRAMING</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="violet">10-12</th>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF C PROGRAMING</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr>
<th bgcolor="green">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="red">1-3</th>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF C PROGRAMING</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="blue">3-5</th>    
<td>FUNDAMENTALS OF C PROGRAMING</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF C PROGRAMING</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr>
    <th>S.No</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19A1414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF (C PROGRAMMING)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EN101</td>
<td>COMMUNICATE ENGLISH</td>
</tr>
</table>
</body>
</html>
``` 

## OUTPUT
![alt text](<Screenshot (25).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
