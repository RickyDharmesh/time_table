# Ex03 Time Table
# Date:29.09.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
  {% load static %}
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIMETABLE</title>
</head>

<body>
    <center>
  
        
        <img src="{% static 'saveetha_image.jpg' %}" width="800px">


        <br>

        <h2>SLOT TIME TABLE - RICKY DHARMESH.P (25016025)</h2>



        <table border="5" height="300px" bgcolor="cyan" width="800px" cellpadding="5" cellspacing="5">


            <tr bgcolor="yellow">
                <th>DAY/TIME</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>

            </tr>


            <tr>
                <td bgcolor="yellow">8-10am</td>
                <td bgcolor="navyblue">FREE SLOT</td>
                <td bgcolor="pink" align=" center">FWAD</td>
                <td bgcolor="navyblue">FREE SLOT</td>
                <td rowspan="2" align="center" bgcolor="   lightyellow ">FCP</td>
                <td align=" center" bgcolor=" light  coral dark ">PS</td>
                <td bgcolor="pink" align=" center">PWAD</td>

            </tr>


            <tr>
                <td bgcolor="yellow">10-12pm</td>
                <td bgcolor="pink" align=" center">FWAD</td>
                <td bgcolor="navyblue">FREE SLOT</td>
                <td bgcolor="lightyellow" align=" center">FCP</td>

                <td bgcolor="navyblue">FREE SLOT</td>
                <td bgcolor="lightyellow" align="center">FCP</td>

            </tr>

            <tr>
                <td bgcolor="yellow">12-1pm</td>

                <td colspan="6" align="center" style="font-size: larger;">L U N C H</td>
            </tr>

            <tr>
                <td bgcolor="yellow">1-3pm</td>
                <td align=" center" bgcolor=" light  coral dark ">PS</td>
                <td bgcolor="pink" align=" center">FWAD</td>
                <td bgcolor="navyblue">FREE SLOT</td>
                <td align=" center" bgcolor=" light  coral dark ">PS</td>
                <td bgcolor="pink" align=" center">FWAD</td>
                <td rowspan="2" align="center" bgcolor=" light  coral dark ">PS</td>


            </tr>

            <tr>
                <td bgcolor="yellow">3-5pm</td>
                <td bgcolor="navyblue">FREE SLOT</td>
                <td align=" center" bgcolor=" light  coral dark ">PS</td>
                <td bgcolor="lightyellow" align=" center">FCP</td>
                <td colspan="2" align=" center" bgcolor="navyblue">FREE SLOT</td>



            </tr>
        </table>


        <br>



        <table border="3" height="170px" width="800px">

            <tr bgcolor="yellow">
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>

            </tr>


            <tr>
                <td bgcolor="light coral dark ">1.</td>
                <td bgcolor=" light  coral dark ">19EN105</td>
                <td bgcolor=" light  coral dark ">Public Speaking (PS)</td>
            </tr>

            <tr>
                <td bgcolor="lightyellow">2.</td>
                <td bgcolor="lightyellow">19AI304</td>
                <td bgcolor="lightyellow">Fundamentals of C Programming (FCP)</td>

            </tr>

            <tr>
                <td bgcolor="pink">3.</td>
                <td bgcolor="pink">19AI414</td>
                <td bgcolor="pink">Fundamentals of Web Application Development (FWAD)</td>

            </tr>



        </table>


    </center>
</body>

</html>
```
# OUTPUT
![alt text](<Screenshot 2025-09-29 212225.png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
