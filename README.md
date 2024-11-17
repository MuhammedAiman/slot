# Ex03 Time Table
## Date:18/11/2024

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
<html>
    <head>
    </head>
  <body>
    <center>
        <img src="logo.png" width="780" height="100"> 
        </center>
        <br>
        <body style="background-color: blanchedalmond;"><h1 align="center"> Muhammed Aiman's Slot Table</h1><hr>
        <table align="center" BORDER="4" width="750" bgcolor="white" cellspacing="5" cellpadding="5">
            <TR align="center" bgcolor="cyan"> 
                <TH>CLASSES</TH><TH>MONDAY</TH><TH>TUESDAY</TH><TH>WEDNESDAY</TH><TH>THURSDAY</TH><TH>FRIDAY</TH><TH>SATURDAY</TH>
            </TR>  
            <TR> <TH bgcolor="gold">CLASS1</TH>
                <TH bgcolor="beige">-</TH>
                <TH bgcolor="beige">-</TH>
                <TH bgcolor="lightgreen">DIGI ELEC</TH>
                <TH bgcolor="orange">HUMAN VALS</TH>
                <TH bgcolor="gray">PROBABILITY</TH>
                <TH bgcolor="beige">-</TH>
            </TR> 
            <TR>
                <TH bgcolor="gold">CLASS2</TH>
                <TH bgcolor="purple">WEBAPP</TH>
                <TH bgcolor="pink">EDM</TH>
                <TH bgcolor="purple">WEBAPP</TH>
                <TH bgcolor="beige">-</TH>
                <TH bgcolor="red">PHYSICS</TH>
                <TH bgcolor="gray">PROBABILITY</TH>
            </TR>
            <TR>
                <TH bgcolor="gold">CLASS3</TH>
                <TH bgcolor="beige">-</TH>
                <TH bgcolor="lightgreen">DIGI ELEC</TH>
                <TH bgcolor="olive">MENTOR MEET</TH>
                <TH bgcolor="red">PHYSICS</TH>
                <TH bgcolor="pink">EDM</TH>
                <TH bgcolor="purple">WEBAPP</TH>
            </TR>
        </table>
        <table align="center" bgcolor="white" border="2" cellspacing="2" cellpadding="2">
            <caption COURSES >
                <tr align="center" bgcolor="cyan">
                    <th>S.NO</th>
                    <th>COURSE CODE</th>
                    <th>COURSE NAME</th>
                </tr>
                <tr>
                    <td>1</td>
                    <td>19AI414</td>
                    <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPEMENT(WEB)</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>SH7801</td>
                    <td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>19AI302</td>
                    <td>EDM</td>
                </tr>
                <tr>
                    <td>4</td>
                    <td>19MA222</td>
                    <td>PROBABILITY AND QUEUING MODELS</td>
                </tr>
                <tr>
                    <td>5</td>
                    <td>SH3214</td>
                    <td>PHYSICS FOR QUANTUM COMPUTING</td>
                </tr>
                <tr>
                    <td>6</td>
                    <td>ECA-M-SCOFT</td>
                    <td>MENTOR MEET</td>
                </tr>
                <tr>
                    <td>7</td>
                    <td>19EE404</td>
                    <td>DIGITAL ELECTRONICS</td>
                </tr>
        </table>
        </body>
        </html>

## OUTPUT
![Screenshot (14)](https://github.com/user-attachments/assets/1f4eb949-18b4-4bf4-be02-db56e1bbb4eb)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
