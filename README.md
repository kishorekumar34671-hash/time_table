# Ex03 Time Table
# Date: 29-09-2025
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
<!DOCTYPE HTML>
<html>
    <head>
        <title>Microsoft</title>
     <link rel="stylesheet" href="kishore.css">
        
    </head>
    <body>
        <center>
        <img src="C:\Users\acer\Documents\saveetha.jpg">
        <h2>SLOT TIME TABLE-KISHORE KUMAR B (25007664)</h2>
        </center>
        
        <table align="center" border="2" cellpadding="10">
            <tr>
                <th>DAY</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>1-3</th>
                <th>3-5</th>
            </tr>
            <tr>
                <td style="background-color: chocolate; font-style: initial;">MONDAY</td>
                <td align="center">FREE SLOT</td>
                <td align="center" class="web">Fundamentals of web development</td>
                <td align="center">FREE SLOT</td>
                <td align="center" rowspan="2">FREE SLOT</td
            </tr>
            <tr>
                <td class="kishore">TUESDAY</td>
                <td align="center" class="web">Fundamentals of web development</td>
                <td align="center">FREE SLOT</td>
                <td align="center" class="web">Fundamentals of web development</td>
                
                
            </tr>
            <tr>
                <td class="kishore">WEDNESDAY</td>
                <td align="center">FREE SLOT</td>
                <td rowspan="2" class="c" align="center">Fundamentals of c programming</td>
                <td align="center">FREE SLOT</td>
                <td class="c" align="center">Fundamentals of c programming</td>
            </tr>
            <tr>
                <td class="kishore">THURSDAY</td>
                <td class="c" align="center">Fundamentals of c programming</td>
                <td class="c" align="center">Fundamentals of c programming</td>
                <td rowspan="3" align="center">FREE SLOT</td>
                
            </tr> 
             <tr>
                <td class="kishore">FRIDAY</td>
                <td align="center" colspan="2">FREE SLOT</td>
                <td align="center" class="web">Fundamentals of web development</td>
                
                
            </tr> 
            <tr>
                <td class="kishore">SATURDAY</td>
                <td align="center" class="web">Fundamentals of web development</td>
                <td class="c" align="center">Fundamentals of c programming</td>
                <td align="center">FREE SLOT</td>
                
            </tr> 
        </table>
        <table align="center" border="2" cellpadding="10" style="margin-top: 20px;">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td class="web">Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI304</td>
                <td class="c">Fundamentals of C Programming</td>
            </tr>


        </table>
        
     </body>
     <style>
        th{
            background-color:yellow ;
        }
        .kishore{
            color: FFD700 ;
            background-color:chocolate ;
            font-style:initial;
        }
        .c{
            background-color:coral;

        }


        table{
    
            background-color:skyblue;
            tab-size: 0cqi;
            background-size: 20px;
        }
        .web{
            background-color: bisque;
        }



     </style>
</html>
```
# OUTPUT
<img width="1524" height="769" alt="Screenshot 2025-09-29 133607" src="https://github.com/user-attachments/assets/bad2e16f-5dbe-4787-9150-59cbcc7e7646" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
