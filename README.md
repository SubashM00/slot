# Ex03 Time Table
## Date:31.11.2023

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
<title> Time Table </title>
</head>

<body>

<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>

<table align="center" width="800" cellspacing="3" cellpadding="14" border="2" bgcolor="black">
<caption> <b> SLOT TIME TABLE - SUBASH.M (23014070) </b> </caption>

<tr align="center">
<th bgcolor="violet"> Day / Time </th>
<th bgcolor="violet"> 8 - 10 </th>
<th bgcolor="violet"> 10 - 12 </th>
<th bgcolor="violet"> 12 - 1 </th>
<th bgcolor="violet"> 1 - 3 </th>
<th bgcolor="violet"> 3 - 5 </th>
</th>

<tr align="center">
<th bgcolor="violet"> Monday </th>
<td colspan="2" align="center" bgcolor="white"> Free slot </td>
<td rowspan="5" bgcolor="white"> Lunch </td>
<td bgcolor="white"> Calculus Matrix and Algebra </td>
<td bgcolor="white"> Physics for quantum computing </td>
</tr>


<tr align="center">
<th bgcolor="violet"> Tuesday </th>
<td bgcolor="white"> Free Slot </td>
<td bgcolor="white"> Calculus Matrix and Algebra </td>
<td bgcolor="white"> Free slot </td>
<td bgcolor="white"> Free slot </td>
</tr>

<tr align="center">
<th bgcolor="violet"> Wednesday </th>
<td bgcolor="white"> Fundamentals of Web Application Development </td>
<td bgcolor="white"> Engineering Design and Modelling </td>
<td bgcolor="white"> Fundamentals of C programming </td>
<td bgcolor="white"> Soft Skills </td>
</tr>

<tr align="center">
<th bgcolor="violet"> Thursday </th>
<td bgcolor="white"> Fundamentals of C programming </td>
<td bgcolor="white"> Fundamentals of Web Application Development </td>
<td bgcolor="white"> Communicative English </td>
<td bgcolor="white"> Free Slot </td>
</tr>

<tr align="center">
<th bgcolor="violet"> Friday </th>
<td bgcolor="white"> Free Slot </td>
<td bgcolor="white"> Physics for quantum computing </td>
<td bgcolor="white"> Fundamentals of Web Application Development </td>
<td bgcolor="white"> Free Slot </td>
</tr>
</table>
<br>
<br>

<table align="center" cellspacing="3" cellpadding="15" border="2" bgcolor="black">

<tr align="center">
<th bgcolor="violet"> S.No. </th>
<th bgcolor="violet"> Subject Code </th>
<th bgcolor="violet"> Subject Name </th>
</tr>

<tr>
<th align="center" bgcolor="white"> 1. </th>
<td align="center" bgcolor="white"> 19AI414 </td>
<td bgcolor="white"> Fundamentals of Web Application Development </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 2. </th>
<td align="center" bgcolor="white"> 19AI304 </td>
<td bgcolor="white"> Fundamentals of C programming </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 3. </th>
<td align="center" bgcolor="white"> 19PH214 </td>
<td bgcolor="white"> Physics for quantum computing </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 4. </th>
<td align="center" bgcolor="white"> 19MA201 </td>
<td bgcolor="white"> Calculus Matrix and Algebra </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 5. </th>
<td align="center" bgcolor="white"> 19EN101 </td>
<td bgcolor="white"> Communicative English </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 6. </th>
<td align="center" bgcolor="white"> 19EY701 </td>
<td bgcolor="white"> Soft Skill </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 7. </th>
<td align="center" bgcolor="white"> 19AI302 </td>
<td bgcolor="white"> Engineering Design and Modelling </td>
</tr>

</table>
</body>
</html>

```

## OUTPUT

![Alt text](<Screenshot (8).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
