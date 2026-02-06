# Ex02 Time Table
## Date:

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
## Developed by : Hubert Raj.I
## Register Number : 25018951
<html>
<head> 
    <title>Slot Time Table - kalaimaran.I(25005710)</title>
</head>
<body>
    <IMG SRC="logo.png"HEIGHT="150"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - kalaimaran.I</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>FWAD</td>
            <td>ML</td>
            <td>FWAD</td>
            <td>Free Slot</td>
            <td>Free Slot</td>
            <td>FWAD</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>Free Slot</td>
            <td>FWAD</td>
            <td>ML</td>
            <td> free slot</td>
            <td>Free slot</td>
            <td>FWAD</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=6 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>ML</td>
            <td>ML</td>
            <td>MENTOR</td>
            <td>Free Slot</td>
            <td>ML</td>
            <td>Free Slot</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>Free Slot</td>
            <td>Free Slot</td>
            <td>Free Slot</td>
            <td>Free Slot</td>
            <td>Free slot</td>
            <td>Free Slot</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI410</td>
            <td>Introduction To Machine Learning</td>
        </tr>
        </tr>
    </table>
</body>
</html>


## OUTPUT
<img width="967" height="732" alt="image" src="https://github.com/user-attachments/assets/cda871b8-2ee7-496d-8be6-49b2cf03f628" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
