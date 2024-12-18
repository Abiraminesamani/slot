# Ex03 Time Table
## Date:15.11.2024

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
    <body>
        <img src="logo.png" width="700" height="100">
<table border="2" cellspacing="15" cellpadding="5">
    <caption>SLOT TIME TABLE - ABIRAMI N (24900514)</caption>
    <tr bgcolor="cyan">
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
        </tr>
        <tr>
        <th>8-10</th>
        <th>FREE</th>
        <th>FWAD</th>
        <th>EDM</th>
        <th>HV</th>
        <th>PHY</th>
        <th>ENG</th>
        </tr>
        <tr>
        <th>10-12</th>
        <th>MAT</th>
        <th>PHY</th>
        <th>ENG</th>
        <th>FUN OF C</th>
        <th>FUN OF C</th>
        <th> FREE</th>
        </tr>
        <tr>
        <th>12-1</th>
        <th colspan="6">LUNCH</th>
        </tr>
        <tr>
        <th>1-3</th>
        <th>EDM</th>
        <th>MAT</th>
        <th>MENTOR MEET</th>
        <th>CAREER DEV</th>
        <th>FWAD</th>
        <th>FWAD</th></tr>
        <tr>
        <th>3-5</th>
        <th colspan="6">FREE</th>
        </tr>
    </table>
    <br>
    <table border="2" cellspacing="15" cellspadding="5">
    <tr bgcolor="violet">
        <th>S.NO.</th>
        <th>Course code</th>
        <th>Course Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19MA201</td>
            <td>CALCULUS AND MATRIX ALGEBRA(MAT) </td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EY708</td>
            <td>CAREER DEVELOPMENT SKILLS(CAREER DEV)</td>
            </tr>
        <tr>
            <td>3</td>
            <td>SH3214</td>
            <td>PHYSICS FOR QUANTUM COMPUTING(PHY)</td>
            </tr>
        <tr>
            <td>4</td>
            <td>19EN101</td>
            <td>COMMUNICATIVE ENGLISH(ENG)</td>
            </tr>
        <tr>
            <td>4</td>
            <td>SH7801</td>
            <td>HUMAN VALUES AND PROFESSIONAL ETHICS(HV)</td>
            </tr>
        <tr>
            <td>5</td>
            <td>ECA-M</td>
            <td>SCOFT MENTOR MEET(MENTOR MEET)</td>
            </tr>
        <tr>
            <td>6</td>
            <td>19AI304</td>
            <td>FUNDAMENTAL OF C PROGRAMMING(FUN OF C)</td>
            </tr>
        <tr>
            <td>7</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
            </tr>
        <tr>
            <td>8</td>
            <td>19AI302</td>
            <td>ENGINEERING DESIGN AND MODELLING(EDM)</td>
            </tr>
    </table>
    </body>
    </html>
    
```


## OUTPUT
![alt text](<Screenshot (28).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfull