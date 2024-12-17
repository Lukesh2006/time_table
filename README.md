# Ex03 Time Table
# Date:17.12.24
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM:


````
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>time table</title>
</head>
        <body>
            <center><img src="saveetha logo.jpg" height="120" width="600"></center>
            <center><h3>SLOT TIMETABLE-LUKESH (24901128)</h3></center>
            <style>
               
                table{
                    border-collapse:collapse;
                }
            </style>
            <center><table border="10"width="800"height="300">
                <tr>
                    <th bgcolor="orange">day/time</th>
                    <th bgcolor="orange">Monday</th>
                    <th bgcolor="orange">Tuesday</th>
                    <th bgcolor="orange">Wednesday</th>
                    <th bgcolor="orange">Thursday</th>
                    <th bgcolor="orange">Fridayday</th>
                   <th bgcolor="orange">Saturday</th>
                </tr>
                <tr>
                    <th bgcolor="orange">8-10</th>
                    <th align="center"bgcolor="yellow">FREE SLOT</th>
                    <th bgcolor="yellow">Environmental science</th>
                    <th align="center"bgcolor="yellow">FREE SLOT</th>
                    <th align="center"bgcolor="yellow">FREE SLOT</th>
                    <th align="center"bgcolor="yellow">FREE SLOT</th>
                    <th align="center"bgcolor="yellow">FREE SLOT</th>
                    
                    
                    </tr>
                <tr>
                    <th bgcolor="orange">10-12</th>
                    <th bgcolor="yellow">Web development</th>
                    <th bgcolor="yellow">Physics</th>
                    <th bgcolor="yellow">C programming</th>
                    <th bgcolor="yellow">Communicative english</th>
                    <th bgcolor="yellow">C programming</th>
                    <th bgcolor="yellow">Probality and queueing models</th>
                </tr>
                <tr>
                    <th bgcolor="orange">12-01</th>
                    <th colspan="6" bgcolor="green">Lunch</th>
                    
                                      
                </tr>
                <tr>
                    <th bgcolor="orange">01-03</th>
                    <th bgcolor="yellow">B.eee</th>
                    <th bgcolor="yellow">Communicative english</th>
                    <th bgcolor="yellow">Mentor meet</th>
                    <th bgcolor="yellow">Web development</th>
                    <th bgcolor="yellow">Probability and queueing models</th>
                    <th bgcolor="yellow">Physics</th>
                </tr>
                <tr>
                    <th bgcolor="orange">03-05</th>
                    <th align="center"bgcolor="yellow">FREE SLOT</th>
                    <th align="center"bgcolor="yellow">FREE SLOT</th>
                    <th bgcolor="yellow">B.eee</th>
                    <th align="center"bgcolor="yellow">FREE SLOT</th>
                    <th bgcolor="yellow">Career developmemt</th>
                    <th bgcolor="yellow">Web developmemt</th>
                </tr>
            </table></center>
            <br>
            <center><table border="3" width="600">
                <tr>
                    <td>S.no</td>
                    <td>Subject code</td>
                    <td>Subject name</td>
                </tr>
                <tr>
                    <td>01</td>
                    <td>19AI304</td>
                    <td>C programming</td>
                </tr>
                <tr>
                    <td>02</td>
                    <td>19AI414</td>
                    <td>Web development</td>
                </tr>
                <tr>
                    <td>03</td>
                    <td>19EE305</td>
                    <td>B.eee</td>
                </tr>
                <tr>
                    <td>04</td>
                    <td>19EN101</td>
                    <td>Communicative english</td>
                </tr>
                <tr>
                    <td>05</td>
                    <td>19EY708</td>
                    <td>Career developmemt</td>
                </tr>
                <tr>
                    <td>06</td>
                    <td>19MA222</td>
                    <td>Probability and queueing models</td>
                </tr>
                <tr>
                    <td>07</td>
                    <td>SH3214</td>
                    <td>Physics</td>
                </tr>
                <tr>
                    <td>08</td>
                    <td>SH3214</td>
                    <td>Environmrntal science</td>
                </tr>
            </table></center>
        </body>
    
</html>

````


# OUTPUT:

![time2](https://github.com/user-attachments/assets/cb9db410-8a14-44b3-ba05-f642fef99349)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
