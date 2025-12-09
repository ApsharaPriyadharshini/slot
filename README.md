# Ex03 Time Table
## Date:

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
     <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-12-09 214014.png" height="150" width="800">
     </center>
      <h3 align="center">  SLOT TIME TABLE - STUDENT NAME ( ROLL NO. ) </h3>
        <table align="center" border="5" cellpadding="6" cellspacing="2" bgcolor="cyan">
        <tr>
          <th bgcolor="yellow">Day</th>    
          <th bgcolor="yellow">8-10</th>
          <th bgcolor="yellow">10-12</th>
          <th bgcolor="yellow">12-1</th>
          <th bgcolor="yellow">1-3</th>
          <th bgcolor="yellow">3-5</th>
        </tr>
        <tr> 
           <th bgcolor="yellow">MONDAY </th>
           <td>FREE SLOT  </td>
           <td>FREE SLOT</td>
           <td rowspan="6">L<br>U<br>N<br>C<br>H </td>
           <td>WEB APPLICATION    </td>
           <td>C PROGRAMMING  </td>
        </tr>
        <tr>
            <th bgcolor="yellow">TUESDAY  </th>
            <td>WEB APPLICATIION </td>
            <td>DATA SCIENCE</td>
            <td>C PROGRAMMING</td>
            <td>WEB APPLICATION</td>
         </tr> 
         <tr>
            <th bgcolor="yellow">WEDNESDAY </th>
            <td>WEB APPLICATION</td>
            <td>DATA SCIENCE</td>
            <td>MENTOR MEET  </td>
            <td>DATA SCIENCE</td>
         </tr> 
         <tr>
            <th bgcolor="yellow">THURSDAY  </th>
            <td>DATA SCIENCE </td>
            <td>FREE SLOT</td>
            <td>WEB APPLICATION </td>
            <td>FREE SLOT</td>
         </tr>
          <tr>
            <th bgcolor="yellow">FRIDAY    </th>
            <td>DATA SCIENCE</td>
            <td>FREE SLOT</td>
            <td>C PROGRAMMING  </td>
            <td>C PROGRAMMING</td>
         </tr>
         <tr>
            <th bgcolor="yellow">SATURDAY  </th>
            <td>FREE SLOT</td>
            <td>C PROGRAMMING  </td>
            <td>FREE SLOT </td>
            <td>FREE SLOT</td>
         </tr>
        </table>
        <br> 
        <table border="5" cellpadding="7" cellspacing="2" align="center">
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th>1.</th>
            <td>4S3-1</td>
            <td>C PROGRAMMING</td>
         </tr>
         <tr>
             <th>2.</th>
             <td>4V1-2</td>
             <td>WEB APPLICATION </td>
          </tr> 
          <tr>
             <th>3.</th>
             <td>4I3-1</td>
             <td>DATA SCIENCE</td>
          </tr> 
          
           
         </table>   
    </body>
</html>
```

## OUTPUT
![WhatsApp Image 2025-12-09 at 9 47 16 PM](https://github.com/user-attachments/assets/60e14f1d-dec9-44bf-bfd1-4ae765449617)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
