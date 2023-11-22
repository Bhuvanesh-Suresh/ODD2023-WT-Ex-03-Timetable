# Ex-05-Timetable
### Name: S.R.Bhuvanesh
### Reference Number: 23013380
## AIM:
To Write a html webpage page to display your timetable.

## ALGORITHM:
### STEP 1
Create a Django Admin user Interface.
### STEP 2
Create a simple table using table tag
### STEP 3
Add header row using the tag
### STEP 4
Add your timetable
### STEP 5
Execute the program

## CODE:

```
<!DOCTYPE html>
<html>

<head>
    <style>
        .h1{
            font-style: italic;
            color: red;
        }
        .day{
            color: purple;
        }
        .d{
            color: blue;
        }
        .d1{
            color: darkblue;
        }
        .dc{
            color: gold;
            font-style: italic;
        }
        .fb{
            color: darkred;
        }
    </style>
</head>

<body>
    <div class='h1'>
        <h1>TIME TABLE</h1>
    </div>
    <table border="5" cellspacing="0" align="center">
        <!--<caption>Timetable</caption>-->
        <tr>
            <td colspan='3' align="centre" height="50" width="100">
              <div class="fb">
              <h2>Name: Bhuvanesh.S.R</h2>
              </div>
            </td>
            <td colspan='3' align="centre" height="50" width="100">
                <div class="fb">
                <h2>Reference No:23013380</h2>
                </div>
            </td>
        </tr>
        <tr>
            <td align="center" height="50" width="100"><br>
                <div class='day' <b><strong>Day/Period</strong></b></br>
                </div>
            </td>
            <td align="center" height="50" width="100">
                <div class='d' <b>I<br>8.00-10:00</b>
                </div>
            </td>
            <td align="center" height="50" width="100">
                <div class='d' <b>II<br>10:00-12:00</b>
                </div>
            </td>
            <td align="center" height="50" width="100">
                <div class='d1'>
                    <b>Break hour<br>12:00-1:00</b>
                </div>
            </td>
            <td align="center" height="50" width="100">
                <div class='d' <b>III<br>1:00-3:00</b>
                </div>
            </td>
            <td align="center" height="50" width="100">
                <div class='d'>
                    <b>IV<br>3:00-5:00</b>
                </div>
            </td>
        </tr>
        <tr>
            <td align="center" height="50">
                <div class='dc'>
                    <b>Monday</b>
                </div>
            </td>
            <td align="center" height="50">Python and Linear Algebra(19AI301C)(EEE 5F LH 02)</td>
            <td align="center" height="50">Communicative English(19EN101)(RB 2F ENGLISH LAB 3)</td>
            <td align="center" height="50">
                <h2>L<br>U<br>N<br>C<br>H</h2>
            </td>
            <td align="center" height="50">FREE HOUR</td>
            <td align="center" height="50">FREE HOUR</td>
        </tr>
        <tr>
            <td align="center" height="50">
                <div class='dc'>
                    <b>Tuesday</b>
                </div>
            </td>
            <td align="center" height="50">Principles of Chemistry in Engineering(19CY205)(RB 3F LH 19)
            </td>
            <td align="center" height="50">FREE HOUR</td>
            <td align="center" height="50">
                <h2>L<br>U<br>N<br>C<br>H</h2>
            </td>
            <td align="center" height="50">Python and Linear Algebra(19AI301C)(CSE 3F LH 02)</td>
            <td align="center" height="50">Engineering Mechanics and Product Development(19AI303)(EEE 3F LH 01)</td>
        </tr>
        <tr>
            <td align="center" height="50">
                <div class='dc'>
                    <b>Wednesday</b>
                </div>
            </td>
            <td align="center" height="50">Engineering Mechanics and Product Development(19AI303)(EEE 2F LH 01)</td>
            <td align="center" height="50">Fundamentals of Web Application Development(19AI414)(EEE 3F LH 01)</td>
            <td align="center" height="50">
                <h2>L<br>U<br>N<br>C<br>H</h2>
            </td>
            <td align="center" height="50">Python and Linear Algebra(19AI301C)(CSE 3F LH 02)</td>
            <td align="center" height="50">FREE HOUR
            </td>
        </tr>
        <tr>
            <td align="center" height="50">
                <div class='dc'>
                    <b>Thursday</b>
                </div>
            </td>
            <td align="center" height="50">Fundamentals of Web Application Development(19AI414)(CSE 3F LH 01)</td>
            <td align="center" height="50">FREE HOUR</td>
            <td align="center" height="50">
                <h2>LUNCH</h2><br><strong>and</strong>
                <h3>MENTOR MEET</h3>
            <td align="center" height="50">Communicative English(19EN101)(RB 2F LH 01)</td>
            <td align="center" height="50">FREE HOUR</td>
        </tr>

        <tr>
            <td align="center" height="50">
                <div class='dc'>
                    <b>Friday</b>
                </div>
            </td>
            <td align="center" height="50">Principles of Chemistry in Engineering(19CY205)(RB 2F CHEMISTRY LAB 2)</td>
            <td align="center" height="50">Fundamentals of Web Application Development(19AI414)(EEE 3F LH 01)</td>
            <td align="center" height="50">
                <h2>L<br>U<br>N<br>C<br>H</h2>
            <td align="center" height="50">Python and Linear Algebra(19AI301C)(CSE 3F LH 02)</td>
            <td align="center" height="50">FREE HOUR</td>
        </tr>
        <tr>
            <td align="center" height="50">
                <div class='dc'>
                    <b>Saturday</b>
                </div>
            </td>
            <td colspan="5" align="center" height="50">TO BE ASSIGNED</td>
            </td>
        </tr>
    </table>
</body>

</html>

```

## OUPUT:
![timetable](https://github.com/Bhuvanesh-Suresh/ODD2023-WT-Ex-03-Timetable/assets/145742661/cce2f76a-20ee-41fe-9ef2-3971893642a5)

## Result:
Thus the program to write a html webpage page to display your timetable is successfully executed.
