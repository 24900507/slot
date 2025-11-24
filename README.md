# EX 03 Time Table
## Date: 23.11.25
## Developed by : AKASH G
## Register No. : 212224100004
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

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Slot Time Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    h2 {
      text-align: center;
      margin-bottom: 10px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 30px;
    }
    th, td {
      border: 1px solid rgb(0, 0, 0);
      padding: 8px;
      text-align: center;
    }
    th {
      background-color: #e6dddd;
    }
    .lunch {
      text-align: center;
      font-weight: bold;
    }
  </style>
</head>
<body>
<center>
            <img src="logo.png" width="500">
        </center>

  <h2> III SEM TIME TABLE - AKASH G (212224100004)</h2>

  <!-- Timetable -->
  <table>
    <tr>
      <th>Day/Time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
      <th>Saturday</th>
    </tr>
    <tr>
      <td>8-10</td>
      <td>PLA</td>
      <td>PLA</td>
      <td>   </td>
      <td>PMC</td>
      <td>QA-I</td>
      <td>   </td>
    </tr>
    <tr>
      <td>10-12</td>
      <td>OS</td>
      <td>  </td>
      <td>PLA</td>
      <td>Web</td>
      <td>PLA</td>
      <td>   </td>
    </tr>
    <tr>
      <td>12-1</td>
      <td colspan="6" class="lunch">L U N C H</td>
    </tr>
    <tr>
      <td>1-3</td>
      <td>HRM</td>
      <td>HRM</td>
      <td>MENTOR</td>
      <td>OS</td>
      <td>PMC</td>
      <td>   </td>
    </tr>
    <tr>
      <td>3-5</td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
    </tr>
  </table>

  <!-- Subject Codes -->
  <table>
    <tr>
      <th>S.No.</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr>
      <td>1</td>
      <td>19AI414</td>
      <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
      <td>2</td>
      <td>19CS405</td>
      <td>Operating System</td>
    </tr>
    <tr>
      <td>3</td>
      <td>19AI301C</td>
      <td>Python and Linear Algebra </td>
    </tr>
    <tr>
      <td>4</td>
      <td>19EE309</td>
      <td>Programming Microcontrollers</td>
    </tr>
    <tr>
      <td>5</td>
      <td>19MS156</td>
      <td>Human Resource Management and Team Building</td>
    </tr>
    <tr>
      <td>6</td>
      <td>19EY701</td>
      <td>Quantitative Ability (QA-I)</td>
    </tr>
  </table>
</body>
</html>
```

## OUTPUT :

<img width="1440" height="900" alt="Screenshot 2025-11-23 at 5 08 13 PM" src="https://github.com/user-attachments/assets/74a95edd-53ea-4d5f-ad26-3fe12cfc058d" />


## RESULT :
The program for creating slot timetable using basic HTML tags is executed successfully.
