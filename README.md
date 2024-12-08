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
'''
<<html>
<head>
<title>slot Timetable</title>    
</head>    
<body>
<center>
<img src="/static/image.png"height="100"width="540">
</center>
<br>
<table align="center"width="540" cellspacing="2" cellpadding="4"border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - DHARSHINI.R (24006560)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>    
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>    
<td>FREE SLOT</td>
<td>ENVIRONMENTAL SCIENCE AND SUSTAINABILITY</td>
<td>FREE SLOT</td>
<td>CALCUS AND MATRIX ALGEBRA</td>
<td>FREE SLOT</td>
<td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>

</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>    
<td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th> 
<td>CALCUS AND MATRIX ALGEBRA</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>MENTOR MEETING</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>CAREER DEVELOPMENT</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>   
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th> 
<td>FREE SLOT</td> 
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>  
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. NO.</th>  
<th>subject Code</th>
<th>subject Name</th>  
</tr>   
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION(FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>    
<td>FUNDAMENTALS OF C PROGRAMMING(C PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">SH4801</td>    
<td>ENVIRONMENTAL SCIENCE AND SUSTAINABILITY(EVS)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">SH3214</td>
<td>PHYSICS FOR QUANTUM COMPUTATION(PHY)</td>    
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA201</td>
<td>CALCUS AND MATRIX ALGEBRA(MAT)</td>    
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY708</td>
<td>CAREER DEVELOPMENT</td>    
</tr>
<tr>
    <td align="center">7.</td>
    <td align="center">19AI303</td>
    <td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>    
    </tr>
</table>
</body>
</html>
'''

## OUTPUT
![screenshot48](https://github.com/user-attachments/assets/4fea15e0-7b33-46b3-a5f7-5606d4e0306d)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
