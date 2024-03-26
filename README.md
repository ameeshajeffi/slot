# Ex03 Time Table
## Date:26/03/2024

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
        <img src="/static/logo.png" height="100"width="500">
    </center>
    <br>
    <table align="center" width="500" cellspacing="3" cellpadding="2" border="2" bgcolor="yellow">
        <caption><b>SLOT TIMETABLE - AMEESHA JEFFI J(212223220007)</b></caption>
        <tr align="center">
            <th bgcolor="lightpurple">Day/Time</th>
            <th bgcolor="lightpurple">Monday</th>
            <th bgcolor="lightpurple">Tuesday</th>
            <th bgcolor="lightpurple">Wednesday</th>
            <th bgcolor="lightpurple">Thursday</th>
            <th bgcolor="lightpurple">Friday</th>
            <th bgcolor="lightpurple">SATURDAY</th>
        </tr>
        <tr align="center">
            <th bgcolor="lightpurple">8-10</th>
            <td bgcolor="lightblue">DIGITAL ELECTRONICS</td>
            <td bgcolor="lightblue">INTRODUCTION TO MACHINE LEARNING</td>
            <td bgcolor="lightblue">ADVANCED C PROGRAMING</td>
            <td bgcolor="lightblue">FREE SLOT</td>
            <td bgcolor="lightblue">FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT </td>
            <td bgcolor="lightblue">INTRODUCTION TO MACHINE LEARNING</td>
        </tr>
        <tr align="centre">
            <th bgcolor="lightpurple">10-12</th>
            <td bgcolor="lightblue">CALCULUS AND MATRIX ALGEBRA</td>
            <td bgcolor="lightblue">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
            <td bgcolor="lightblue">FREE SLOT</td>
            <td bgcolor="lightblue">FREE SLOT</td>
            <td bgcolor="lightblue">CALCULUS AND MATRIX ALGEBRA</td>
            <td bgcolor="lightblue">OPERATING SYSTEM</td>
        </tr>
        <tr>
            <th bgcolor="lightpurple">12-1</th>
            <td colspan="6" align="center">L U N C H    B R E A K</td>
        </tr>
        <tr align="centre">
            <th bgcolor="lightpurple">1-3</th>
            <td bgcolor="lightblue">FREE SLOT</td>
            <td bgcolor="lightblue">FREE SLOT</td>
            <td bgcolor="lightblue">ADVANCED C PROGRAMING</td>
            <td bgcolor="lightblue">FREE SLOT</td>
            <td bgcolor="lightblue">DIGITAL ELECTRONICS</td>
            <td bgcolor="lightblue">FREE SLOT</td>
        </tr>
        <tr align="centre">
            <th bgcolor="lightpurple">3-5</th>
            <td bgcolor="lightblue">OPERATING SYSTEM</td>
            <td bgcolor="lightblue">FREE SLOT</td>
            <td bgcolor="lightblue">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
            <td bgcolor="lightblue">FREE SLOT</td>
            <td bgcolor="lightblue">FREE SLOT</td>
            <td bgcolor="lightblue">FREE SLOT</td>
        </tr>
    </table>
    <br>
    <table align="center" cellspacing="2" cellpadding="2" border="2">
        <tr align="center">
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr> 
        <tr>
            <td align="center">1.</td>
            <td align="center"><b><font color = pink>19AI414</font></b></td>
            <td><b><font color = pink>FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT(FWAD)</font color></b></td>
        </tr>
        <tr>
            <td align="center">2.</td>
            <td align="center">19CS405</td>
            <td>OPERATING SYSTEM(OS)</td>
        </tr>
        <tr>
            <td align="center">3.</td>
            <td align="center">19AI410</td>
            <td>INTRODUCTION TO MACHINE LEARNING(ML)</td>
        </tr>
        <tr>
            <td align="center">4.</td>
            <td align="center">19MA201</td>
            <td>CALCULUS TO MATRIX ALGEBRA(CMA)</td>
        </tr>
        <tr>
            <td align="center">5.</td>
            <td align="center">19EE404</td>
            <td>DIGITAL ELECTRONICS(DE)</td>
        </tr>
        <tr>
            <td align="center">6.</td>
            <td align="center">19AI305</td>
            <td>ADVANCED C PROGRAMING(C)</td>
        </tr>
        <tr>
            <td align="center">7.</td>
            <td align="center">19EY702</td>
            <td>CREATIVE SKILLS (cs)</td>
        </tr>
    </table>
</body>
</html>
```
## OUTPUT
![Screenshot 2024-03-26 140514](https://github.com/ameeshajeffi/slot/assets/150773598/4635d383-b336-4366-93ad-683c73f71fdc)

![Screenshot 2024-03-26 140528](https://github.com/ameeshajeffi/slot/assets/150773598/5944ff9c-a0ca-44dc-8ef8-1762c238206d)

![Screenshot 2024-03-26 140545](https://github.com/ameeshajeffi/slot/assets/150773598/f69cf4a1-1fcb-43c4-900f-73c7d1a73629)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
