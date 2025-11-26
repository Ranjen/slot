# Ex02 Time Table
## Date:26-11-2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <body>
        <a href="https://saveetha.ac.in/" title="Saveetha Engineering College"><img src="logo.png" width="1000" height="150"></a>
        <br>
        <br>
        
        <table bgcolor="gold" border="2" cellspacing="2" cellpadding="8">
            <caption><b>SLOT TIME TABLE - RANJEN MUNUSWAMY K B (25010574)</b></caption>
            <tr bgcolor="orange" align="center">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="orange">8am - 10am</th>
                <td  colspan="2">CE</td>
                <td>FWAD</td>
                <td>PP</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
            </tr>
            <tr align="center">
                <th bgcolor="orange">10am - 12pm</th>
                <td colspan="3">FWAD</td>
                <td colspan="2">FREE SLOT</td>
                <td>CE</td>
            </tr>
            <tr align="center">
                <th bgcolor="orange">12pm - 1pm</th>
                <td colspan="6">L U N C H</td>
            </tr>
            <tr align="center">
                <th bgcolor="orange">1pm - 3pm</th>
                <td>PP</td>
                <td>FREE SLOT</td>
                <td>MM</td>
                <td>CE</td>
                <td>FREE SLOT</td>
                <td>PP</td>
            </tr>
            <tr align="center">
                <th bgcolor="orange">3pm - 5pm</th>
                <td>PP</td>
                <td colspan="3">FREE SLOT</td>
                <td>PP</td>
                <td>FREE SLOT</td>
            </tr>
        </table>
        <br>
        <br>
        <table border="2" cellspacing="2" cellpadding="10">
            <tr align="centre">
                <th>S. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr align="center">
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr align="center">
                <td>2.</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr align="center">
                <td>3.</td>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
            <tr align="center">
                <td>4.</td>
                <td>ECA-M</td>
                <td>Mentor Meeting</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-11-26 231524.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
