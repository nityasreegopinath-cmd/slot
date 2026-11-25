# Ex02 Time Table
## Date: 25.11.2026 

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
<head>
    <title>Slot Time Table</title>
</head>
<body>

    <center>
        <img src='logo.png' width="600px" height="80px">
        <p><b>SLOT TIME TABLE - G NITYA SREE (26012026)</b></p>
        <table border="3" cellspacing="3" cellpadding="8" bgcolor="cyan">
            <tr bgcolor="yellow">
                <th>Day/Time</th>
                <th>8-9:30</th>
                <th>9:45-11:15</th>
                <th>11:30-1</th>
                <th>1:15-2:45</th>
                <th>3-4:30</th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">MONDAY</th>
                <td>DE</td>
                <td>FWAD</td>
                <td>LUNCH</td>
                <td colspan="2">FREE SLOT</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">TUESDAY</th>
                <td>FREE SLOT</td>
                <td>CDS</td>
                <td>LUNCH</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">WEDNESDAY</th>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>LUNCH</td>
                <td>FREE SLOT</td>
                <td>PY</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">THURSDAY</th>
                <td>ENG</td>
                <td>SNMD</td>
                <td>LUNCH</td>
                <td>JAP</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">FRIDAY</th>
                <td>SNMD</td>
                <td>FREE SLOT</td>
                <td>LUNCH</td>
                <td>JAP</td>
                <td>PY</td>
            </tr>
             <tr align="center">
                <th bgcolor="yellow">SATURDAY</th>
                <td>FREE SLOT</td>
                <td>DE</td>
                <td>LUNCH</td>
                <td>ENG</td>
                <td>PY</td>
            </tr>
        </table>

        <br>

        <table border="2" cellspacing="3" cellpadding="6">
            <tr>
                <th>S. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19EE404</td>
                <td>DIGITAL ELECTRONICS (DE)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI301</td>
                <td>PYTHON PROGRAMMING (PY)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">SH2211</td>
                <td>STATISTICS AND NUMERICAL METHODS (SNMD)</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">SH6708</td>
                <td>CAREER DEVELOPMENT SKILLS (CDS)</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">SH1011</td>
                <td>COMMUNICATIVE ENGLISH (ENG)</td>
            </tr>
            <tr>
                <td align="center">7.</td>
                <td align="center">SH5624</td>
                <td>JAPANESE (JAP)</td>
        </table>
    </center>

</body>
</html>

```
## OUTPUT


![alt text](image-1.png)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
