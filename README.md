# Ex03 Time Table
## Date:15.11.2024

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
<html >
    <head>
        <title>Timetable </title>
    </head>
    <body >
        <img src="logo.png" width="50%">
        <br>
        <br>
        <table border="3">
            <caption><b>Slot Time Table (Ameen Basha - 2490027)</b></caption>
            <tr  bgcolor="cyan" cellspacing="5" cellpadding="10">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>WEdnesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th  bgcolor="cyan">8-10</th>
                <td>Free </td>
                <td>FWAD</td>
                <td>Free</td>
                <td>EDM</td>
                <td>Free</td>
                <td>EDM</td>
            </tr>
            <tr>
                <th  bgcolor="cyan">10-12</th>
                <td>English</td>
                <td>Maths</td>
                <td>C Prog</td>
                <td>Soft skill</td>
                <td>C Prog</td>
                <td>Math</td>
            </tr>
            <tr>
                <th  bgcolor="cyan">12-1</th>
                <td colspan="6" align="center">LUNCH BREAK</td>
            </tr>

            <tr>
                <th  bgcolor="cyan">1-3</th>
                <td>Chemistry</td>
                <td>English</td>
                <td>Meeting</td>
                <td>Chemistry</td>
                <td>FWAD</td>
                <td>FWAD</td>
            </tr>
            <tr>
                <th  bgcolor="cyan">3-5</th>
                <td colspan="6" align="center">FREE SLOT</td>

        </table>    

    </body>
</html>
<br>
<hr>
<br>

<html>
    <head>
        <title>courses</title>
    </head>
    <body>
        <table border="3" >
        <caption><b>My courses</b></caption>

            <tr bgcolor=" cyan">
                <th>S.NO</th>
                <th>Course Code</th>
                <th>Course Name</th>
            </tr>
            <tr>
                <th bgcolor="cyan">1</th>
                <td >19A13414</td>
                <td>Fundamentals of web application development (FWAD)</td>
            </tr>
            <tr>
                <th bgcolor="cyan">2</th>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra</td>
            </tr>
            <tr>
                <th bgcolor="cyan">3</th>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <th bgcolor="cyan">4</th>
                <td>19CY205</td>
                <td>Principle of Chemistry in Engineeing </td>
            </tr>
            <tr>
                <th bgcolor="cyan">5</th>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <th bgcolor="cyan">6</th>
                <td>ECA-M-SCOFT</td>
                <td>Mentor Meet</td>
            </tr>
            <tr>
                <th bgcolor="cyan">7</th>
                <td>19AI302</td>
                <td>Engineering Design and Modeling(EDM)</td>
            </tr>
            <tr>
                <th bgcolor="cyan">8</th>
                <td>19EY708</td>
                <td>Carrer development skill(Soft skill)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (31).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
