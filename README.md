# Ex03 Time Table
## Date:24-11-2024

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
    <title>Timetable</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }
        th, td {
            border: 1px solid black;
            text-align: center;
            padding: 10px;
        }
        th {
            background-color: white;
        }
    </style>
</head>
<body>
    <img src="logo.png" width="1000" height="150">
    <h1>Weekly Timetable</h1>
    <h1>Tharunish vasan.T(24001333)</h1>
    <table>
        <tr>
            <th>Day</th>
            <th>8:00 - 10:00</th>
            <th>10:00 - 12:00</th>
            <th>12:00 - 1:00</th>
            <th>1:00 - 3:00</th>
            <th>3:00 - 5:00</th>
        </tr>
        <tr>
            <td>Monday</td>
            <td>Free period</td>
            <td>Communicative English</td>
            <td>Lunch</td>
            <td>Basic electronics,electronics and measurement enigneering</td>
            <td>Free period</td>
        </tr>
        <tr>
            <td>Tuesday</td>
            <td>fundamentals of web application</td>
            <td>Free period</td>
            <td>Lunch</td>
            <td>Python</td>
            <td>Free period</td>
        </tr>
        <tr>
            <td>Wednesday</td>
            <td>Python</td>
            <td>Free period</td>
            <td>Lunch</td>
            <td>Mentor Meeting</td>
            <td>Free period</td>
        </tr>
        <tr>
            <td>Thursday</td>
            <td>Communicative English</td>
            <td>Python and linear algebra</td>
            <td>Lunch</td>
            <td>Basic electronics,electronics and measurement enigneering</td>
            <td>FP</td>
        </tr>
        <tr>
            <td>Friday</td>
            <td>Free period</td>
            <td>CDS</td>
            <td>Lunch</td>
            <td>fundamentals of web application</td>
            <td>Yoga</td>
        </tr>
        <tr>
            <td>Saturday</td>
            <td>Free period</td>
            <td>fundamentals of web application</td>
            <td>Lunch</td>
            <td>Python and linear algebra</td>
            <td>Free period</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Course Code</th>
            <th>Subject</th>
        </tr>
        <tr>
            <td>19EN101</td>
            <td>Communicative English</td>
        </tr>
        <tr>
            <td>19EE301</td>
            <td>Basic Electrical, Electronics, and Measurement Engineering</td>
        </tr>
        <tr>
            <td>19AF414</td>
            <td>Fundamentals of Web Application Development</td>
        </tr>
        <tr>
            <td>19EY708</td>
            <td>Career Development</td>
        </tr>
        <tr>
            <td>SH5616</td>
            <td>Yoga</td>
        </tr>
        <tr>
            <td>19AT301C</td>
            <td>Python and Linear Algebra</td>
        </tr>
    </table>
</body>
</html>


```
## OUTPUT
![alt text](<Screenshot 2024-12-10 092816.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
