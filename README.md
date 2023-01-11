# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title>TIMETABLE</title>
   <style>
    table {
      width: 700px;
      border-spacing: 10px;
      border: 3px solid;
    }

     td, th {
      border: 3px solid;
      padding: 10px;
    }
  </style>
  
</head>
<body>
   
    <img src="/static/images/logo.png" alt="saveethalogo" height="100" width="700">
   <table> 
    <tr>
      <th colspan="6">TIMETABLE</th>
    </tr>
    <tr>
      <th colspan="2" >Reference Number</th>
      <th>22006013</th>
      <th>Name</th>
      <th colspan="2">Kowsalya M</th>
    </tr>
        <tr>
           <td>DAYS</td>
           <td> Reg number: </td>
           <td> 22006013 </td>
           <td>LUNCH</td>
           <td>Name</td>
           <td>Kowsalya M</td>
        </tr>
        <tr>
            <td>Class Hours</td>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
        </tr>
                <tr>
            <td>MONDAY</td>
            <td>-</td>
            <td>19AI414</td>
            <td>ECA-M-AIDS</td>
            <td>19EY701</td>
            <td>-</td>
        </tr>
                 <tr>
            <td>TUESDAY</td>
            <td>19EN616</td>
            <td>19MA220</td>
            <td>-</td>
            <td>19AI414</td>
            <td>-</td>
        </tr>
                 <tr>
            <td>WEDNESDAY</td>
            <td>19MA221</td>
            <td>19AI414</td>
            <td></td>
            <td>-</td>
            <td>19CY205</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td>19EN610</td>
            <td>19MA219</td>
            <td>-</td>
            <td>19MA220</td>
            <td>-</td>
        </tr>
        <tr>
            <td>FRIDAY</td>
            <td>-</td>
            <td>19AI301</td>
            <td>-</td>
            <td>19EN610</td>
            <td >-</td>
        </tr>
    </table>
    <ol>
        <li>SUBJECT CODE - SUBJECT - FACULTY</li>
        <li>19AI414 - Fundamentals of Web App Development - C.Obed Otto</li>
        <li>19CY205 - Principles of Chemistry in Engineering - Shanthi S</li>
        <li>19AI301 - Python Programming - E.T.Jaba Jasphin</li>
        <li>19MA221 - Linear Algebra Laboratory - E.T.Jaba Jasphin</li>
        <li>19MA220 - Maths for Artificial Intelligence - E.T.Jaba Jasphin</li>
        <li>ECA-M-AIDS - Mentor Meet - Gowri Ganesh N S</li>
        <li>19EY701 - Soft Skills - Sneha Priya P</li>
        <li>19EN610 - French Basic - Mariana Jenifer P</li> 
        <li>19EN616 - Yoga and Meditation - Raghuram G</li>
    </ol>
</body>
</html>
```


# OUPUT :
![OUTPUT](./images/timetable.png)

# HTML VALIDATION :
![VALIDATION](./images/validation.png)

# RESULT :
Thus timetable is displayed.
