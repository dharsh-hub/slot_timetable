# Ex03 Time Table
## Date:19/11/24

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
        <title>schedule</title>
    </head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>
    <table border="3" cellpadding="10" align="center"><br><br>
        <caption><b> SLOT TIME TABLE - DHARSHINI S (24900238)</b></caption>
        <TR align="center">
            <TH >DAYS/TIME</TH>
            <TH >8-10</TH>
            <TH >10-12</TH>
            <TH >12-1</TH>
            <TH >1-3</TH>
        </TR>
        <TR align="center">
            <TD >MONDAY</TD>
            <TD></TD><TD>WEB</TD><TD>LUNCH</TD><TD></TD>
        </TR>
        <TR align="center">
            <TD>TUESDAY</TD><TD>COMMUNI</TD><TD>DIGITAL ELEC.</TD><TD>LUNCH</TD><TD>STATISTICS</TD>        </TR>
        <TR align="center">
            <TD>WEDNESDAY</TD><TD>STATISTICS</TD><TD>WEB</TD><TD>LUNCH</TD><TD>MENTOR MEETING</TD>
        </TR>
        <TR align="center">
            <TD>THURSDAY</TD><TD>QUANTUM COMP.</TD><TD></TD><TD>LUNCH</TD><TD></TD>
        </TR>
        <TR align="center">
            <TD>FRIDAY</TD><TD>COMMUNI.</TD><TD>DIGITAL ELEC.</TD><TD>LUNCH</TD><TD>CAREER DEVELOP</TD>       </TR>
        <TR align="center">
            <TD>SATURDAY</TD><TD></TD><TD>QUANTUM COMP.</TD><TD>LUNCH</TD><TD>WEB</TD>
        </TR>
    </table>

</body>

</html>

```

## OUTPUT
![alt text](<Screenshot 2024-11-19 203958.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
