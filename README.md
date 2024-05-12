# Ex03 Time Table
## Date:14/3/2024

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
<html lang="en">
     <head>
              <title> web </title>
     </head>
     <body bgcolor="white" TEXT="black">
<center>
     <img src="C:\Users\user1\slot\logo.png"  height="90" width="1000" align="center" /></center>
          
          <table border= "5"  cellpadding="8px" bgcolor="black" align="center" >
          <h2 style="text-align: center;"> SLOT TIME TABLE - Sushiendar M(212223040217) </h2>
               <tr bgcolor="green">
                <th bgcolor="blue">   DAY/TIME </th>
                <th>   MONDAY </th>
                <th>   TUESDAY </th>
                <th>   WEDNESDAY </th>
                <th>   THURSDAY </th>
                <th>   FRIDAY </th>
                <th>   Saturday</th>
               </tr>
               <tr>
                <th bgcolor="green"> 8-10 </th>
                <td bgcolor="red">FWAD</td>
                <td bgcolor="red">FREE SLOT</td>
                <td bgcolor="red">FREE SLOT</td>
                <td bgcolor="red">EDM</td>
                <td bgcolor="red">FREE SLOT</td>
                <td bgcolor="red">FREE SLOT</td>
               </tr>
               <tr>
                <th bgcolor="green"> 10-12 </th>
                <td bgcolor="maroon">OS</td>
                <td bgcolor="maroon">FREE SLOT</td>
                <td bgcolor="maroon">CC</td>
                <td bgcolor="maroon">FREE SLOT</td>
                <td bgcolor="maroon">Fundamentals of C programming</td>
                <td bgcolor="maroon">FREE SLOT</th>
              </tr>
               <tr>
                <th bgcolor="green"> 12-1 </th>
                 <td colspan="6" align="center" bgcolor="white">LUNCH TIME</td>
               </tr>
               <tr>
                <th bgcolor="green"> 1-3 </th>
                <td bgcolor="silver">Math</td>
                <td bgcolor="silver">FREE SLOT</td>
                <td bgcolor="silver">OS</td>
                <td bgcolor="silver">FWAD</td>
                <td bgcolor="silver"> FWAD </td>
                <td bgcolor="silver">Computer Networks</td>
               </tr>
               
              
              <tr>
               <th bgcolor="green"> 3-5 </th>
               <td bgcolor="yellow">Fundamentals of C programming</td>
               <td bgcolor="yellow">EDM</td>
               <td bgcolor="yellow">FREE SLOT</td>
               <td bgcolor="yellow">Computer Networks</td>
               <td bgcolor="yellow">Math</td>
               <td bgcolor="yellow">FREE SLOT</td>
              </tr>
           </table>
            <table border= "3" cellpadding="7px"  align="center" >
            <br><br>
           <tr>
            <th bgcolor="violet"> S.No </th>
            <th bgcolor="aqua blue"> SUBJECT CODE </th>
            <th bgcolor="gold"> SUBJECT NAME </th>
           </tr>
           <tr> 
            <td bgcolor="violet">  1. </td>
            <td bgcolor="aqua blue"> 19AI414 </td>
            <td bgcolor="gold"> Fundamental of web application and development(FWAD) </td>
           </tr>
           <tr>
           <td bgcolor="violet"> 2. </td>
           <td bgcolor="aqua blue"> 19EY702 </td>
           <td bgcolor="gold">Creative Skills for Communcation(CC) </td>
           </tr>
           <tr>
            <td bgcolor="violet"> 3. </td>
            <td bgcolor="aqua blue"> 19MA206 </td> 
            <td bgcolor="gold">Logics and combinatorics(Math)</td>
           </tr>
           <tr>
            <td bgcolor="violet"> 4. </td>
            <td bgcolor="aqua blue"> 19AI304 </td>
            <td bgcolor="gold">Fundamentals of C programming</td>
           </tr>
           <tr>
            <td bgcolor="violet"> 5. </td>
            <td bgcolor="aqua blue"> 19AI302 </td>
            <td bgcolor="gold">Engineering Designing and Modelling(EDM)</td>
           </tr>
           <tr>
            <td bgcolor="violet"> 6. </td>
            <td bgcolor="aqua blue"> 19CS405 </td>
            <td bgcolor="gold"> Operating System(OS) </td>
           </tr>
           <tr>
            <td bgcolor="violet"> 7. </td>
            <td bgcolor="aqua blue"> 19CS406 </td>
            <td bgcolor="gold"> Computer Networks </td>
           </tr>
           </table>
              
        </body>
</html>
```
## OUTPUT
![Screenshot 2024-03-31 132225](https://github.com/Sushiendar/slot/assets/159266287/e76d9902-34ec-4a15-976b-78b5cbbc5dbd)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
