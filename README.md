# Ex03 Time Table
## Date:04/04/2024

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
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
    <style>
        
    </style>
</head>
<body>
    <center><img src="saveetha_logo.png" width="70%"></center>
    <br>
    <center><b>SLOT TIME TABLE-JAYALAKSHMI M(212221040066)</b></center>
    <table align="center" width="1200" height="80" border="2" bgcolor="Lavender" cellspacing="5" cellpadding="5">
        <thead>
            <tr bgcolor="pink">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
        </thead>
        <tbody>
            <tr align="center">
                <td bgcolor="pink">8-10</td>
                <td bgcolor="blanchedalmond">MAD</td>
                <td bgcolor="aquamarine">FWAD</td>
                <td bgcolor="cadetblue">MERN</td>
                <td bgcolor="blanchedalmond">MAD</td>
                <td bgcolor="cadetblue">MERN</td>
                <td bgcolor="coral">FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="pink">10-12</td>
                <td bgcolor="burlywood">AI</td>
                <td bgcolor="cadetblue">MERN</td>
                <td bgcolor="coral">FREE SLOT</td>
                <td bgcolor="chocolate">EES</td>
                <td bgcolor="coral">FREE SLOT</td>
                <td bgcolor="burlywood">AI</td>
            </tr>
            <tr align="center" style="background-color:darkseagreen;">
                <td bgcolor="pink">12-1</td>
                <td>LUNCH</td>
                <td bgcolor="darkgray">MM</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
            </tr>
            <tr align="center">
                <td bgcolor="pink">1-3</td>
                <td bgcolor="coral">FREE SLOT</td>
                <td bgcolor="cornflowerblue">IPR</td>
                <td bgcolor="aquamarine">FWAD</td>
                <td bgcolor="cadetblue">MERN</td>
                <td bgcolor="coral">FREE SLOT</td>
                <td bgcolor="darkgoldenrod">AQLR</td>
            </tr>
            <tr align="center">
                <td bgcolor="pink">3-5</td>
                <td bgcolor="cadetblue">MERN</td>
                <td bgcolor="coral">FREE SLOT</td>
                <td bgcolor="cornflowerblue">IPR</td>
                <td bgcolor="coral">FREE SLOT</td>
                <td bgcolor="aquamarine">FWAD</td>
                <td bgcolor="coral">FREE SLOT</td>
            </tr>
        </tbody>
    </table>
    <br>
    <table align="center" width="800" height="80" border="5" cellspacing="10" cellpadding="10">
        <thead>
            <tr align="center" style="background-color:crimson">
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
        </thead>
        <tbody>
            <tr align="center">
                <td bgcolor="darkkhaki">1.</td>
                <td bgcolor="aquamarine">19A1414</td>
                <td bgcolor="aquamarine">Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr align="center">
                <td bgcolor="darkkhaki">2.</td>
                <td bgcolor="cadetblue">19AI512C</td>
                <td bgcolor="cadetblue">MERN Full Stack (MERN)</td>
            </tr>
            <tr align="center">
                <td bgcolor="darkkhaki">3.</td>
                <td bgcolor="burlywood">19CS413</td>
                <td bgcolor="burlywood">Artificial Intelligence (AI)</td>
            </tr>
            <tr align="center"> 
                <td bgcolor="darkkhaki">4.</td>
                <td bgcolor="blanchedalmond">19CS414</td>
                <td bgcolor="blanchedalmond">Mobile Application Development (MAD)</td>
            </tr>
            <tr align="center">
                <td bgcolor="darkkhaki">5.</td>
                <td bgcolor="darkgoldenrod">19EY704</td>
                <td bgcolor="darkgoldenrod">Advanced Quantitative and Logical Reasoning (AQLR)</td>
            </tr>
            <tr align="center">
                <td bgcolor="darkkhaki">6.</td>
                <td bgcolor="chocolate">19EY705</td>
                <td bgcolor="chocolate">Employment Enhancement Skills (EES)</td>
            </tr>
            <tr align="center">
                <td bgcolor="darkkhaki">7.</td>
                <td bgcolor="cornflowerblue">19ME531</td>
                <td bgcolor="cornflowerblue">Intellectual Property Rights</td>
            </tr>
            <tr align="center">
                <td bgcolor="darkkhaki">8.</td>
                <td bgcolor="darkgray">ECA-M</td>
                <td bgcolor="darkgray">Mentor Meet</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
## OUTPUT

![alt text](<Screenshot (147).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
