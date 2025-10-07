# Ex03 Time Table
## Date:07.10.2025
## NAME: JAIRAM J
## REGISTER NO: 25012221

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
    <title>Timetable</title>
</head>            
<title>Google <div class="Timetable"></div></title>
    <body> 
     <center> 
     <img src="logo.jpg" height="150" width="800">
     </center>
      <h3 align="center">  SLOT TIME TABLE - STUDENT NAME ( 25017708) </h3>
        
       <table align="center"border="3" bgcolor="CYANX"height="100" width="300"cellpadding="3"cellspacing="4" >
        <tr>
            <th>DAYS</th>
            <th>8.00-10.00</th>
            <th>10.00-12.00</th>
            <th>12.00-1.00</th>
            <th>1.00-3.00</th>
            <th>3.00-5.00</th>
        </tr>
        <tr>
            <td>MONDAY</td>
            <td>PUBLIC SPEAKING</td>
            <td>PUBLIC SPEAKING</td>
            <td>LUNCH</td>
            <td>WEB DEVELOPMENT</td>
            <TD>---</TD>
        </tr>
        <tr>
            <td>TUESDAY</td>
            <td>PUBLIC SPEAKING</td>
            <td>C PROGRAMMING</td>
            <TD>LUNCH</TD>
            <td>PUBLIC SPEAKING</td>
            <TD>---</TD>
            
        </tr>
        <tr>
            <td>WEDNESDAY</td>
            <TD>---</TD>
            <td>C PROGRAMMING</td>
            <TD>LUNCH</TD>
            <TD>MENTOR MEET</TD>
            <TD>WEB DEVELOPMENT</TD>
           
        </tr>
        <TR>
            <TD>THURSDAY</TD>
            <TD>WEB DEVELOPMENT</TD>
              <TD>WEB DEVELOPMENT</TD>
              <TD>LUNCH</TD>
              <TD>C PROGRAMMING</TD>
              <TD>---</TD>
        </TR>
        <TR>
            <TD>
                FRIDAY
            </TD>
            <td>PUBLIC SPEAKING</td>
            <TD>PUBLIC SPEAKING</TD>
            <TD>LUNCH</TD>
            <TD>C PROGRAMMING</TD>
            <TD>WEB DEVELOPMENT</TD>
        </TR>
        <TR>
            <TD>SATURDAY</TD>
            <TD>---</TD>
            <TD>---</TD>
            <TD>LUNCH</TD>
            <TD>C PROGRAMMING</TD>
            <TD>---</TD>
        </TR>
    </table>
    
        <br> 
        <table border="5" cellpadding="7" cellspacing="2" align="center" bgcolor="red" >
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
        
         <tr>
             <th>1.</th>
             <td>4V1-2</td>
             <td>PUBLIC SPEAKING </td>
          </tr> 
          
          <tr>
             <th>2.</th>
             <td>4L1-1</td>
             <td>FUNDAMENDALS OF C PROGRAMMING  </td>
          </tr>
           
          <tr>
             <th>3.</th>
             <td>6J1-1</td>
             <td>FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT   </td>
          </tr>
         </table>   
    </body>
</html>

```

## OUTPUT
![alt text](<img width="1891" height="980" alt="Screenshot 2025-10-06 190652" src="https://github.com/user-attachments/assets/16daefed-42f5-4436-9e4f-399003c327e6" />
)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

