# Ex03 Time Table
## Date: 18.11.2024

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
    <img src="/static/logo.png" height="100" width="520">
    </center>
    <table bgcolor="#11e9ec" align="center" border="3" cell padding="10">
    <caption><b>SLOT TIME TABLE-HARISH P K (24900066)</b></caption>
 <tr bgcolor="yellow">
      <th>Day/time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
      <th>Saturday</th>
 </tr>
 <tr>
    <td align="center" bgcolor="yellow">8.00-10.00</td>
    <td align="center" >FREE SLOT</td>
    <td align="center">FREE SLOT</td>
    <td>Python</td>
    <td align="center">FREE SLOT</td>
    <td>Japanese</td>
    <td align="center">FREE SLOT</td>
 </tr>
 <tr>
    <td align="center" bgcolor="yellow">10.00-12.00</td>
    <td>Python</td>
    <td>Japanese</td>
    <td>Calculus</td>
    <td> Chemistry</td>
    <td>BEEE</td>
    <td>FWAD</td>
 </tr>
 <tr><td align="center" bgcolor="yellow">12.00-1.00</td><td align="center" COLSPAN="7">LUNCH</td></tr>
 <tr>
    <td align="center" bgcolor="yellow">1.00-3.00</td>
    <td> Chemistry</td>
    <td>FWAD</td>
    <td>Mentor Meet</td>
    <td>FWAD</td>
    <td>Calculus</td>
    <td>Japanese</td>
 </tr>
 <tr>
    <td align="center" bgcolor="yellow">3.00-5.00</td>
    <td align="center" colspan="5">FREE SLOT</td>
    <td>BEEE</td>
 </tr>
    </table>
 <table align="center" border="2" cell padding="10">
   <br>
   <br>
   <tr>
      <th>S.No</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
 </tr>
 <tr>
   <th>1.</th>
   <th>19AI404</th>
   <th>Fundamentals of Web Application Development (FWAD)</th>
</tr>
<tr>
   <th>2.</th>
   <th>19AI301</th>
   <th>Fundamentals of Python Programming</th> 
</tr>
<tr>
      <th>3.</th>
      <th>19MA201</th>
      <th> Calculas and Mtrix Algebra </th>
 </tr>
 <tr>
   <th>4.</th>
   <th>19EE305</th>
   <th>Basic Electrical,Electronics and Measuremunt Engineering (BEEE)</th>
</tr>
<tr>
   <th>5.</th>
   <th>SH5603</th>
   <th>Japanese Language N5</th>
</tr>
<tr>
   <th>6.</th>
   <th>19CY205</th>
   <th>Principles of Chemistry in Engineering (CHE)</th>
</tr>
<tr>
   <th>7.</th>
   <th>ECA-M-SCOFT</th>
   <th>MEntor Meet</th>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-11-18 230649.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
