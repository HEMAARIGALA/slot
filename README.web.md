# Ex03 Time Table
## Date: 12/11/24

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
        <img src="/static/logo.png">
        <table border="2" cellspacing="10" cellpadding="10">
<caption>Camu Schedule Hema 24011259</caption>
            <tr bgcolor="cyan">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>wednesday</th>
                <th>thursday</th>
                <th>friday</th>
                <th>saturday</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td>freeslot</td>
                <td>edm</td>
                <td>edm</td>
                <td>statistics</td>
                <td>fwad</td>
                <td>statistics</td>
            
                <tr>
                    <td>10-12</td>
                    <td>physics</td>
                    <td>statistics</td>
                    <td>cprogramming</td>
                    <td>edm</td>
                    <td>cprogramming</td>
                    <td>phy</td>
                <tr>
                    <td>12-1</td>
                    <td colspan="6">lunch</td>/td>
                    <tr>
                <tr bgcolor="orange">
                    <td>1-3</td>
                    <td>fwad</td>
                    <td>phy</td>
                    <td>mentor meet</td>
                    <td>edm</td>
                    <td>statistics</td>
                    <td>cprogramming</td>

                </tr>
            </table>
            <table border="1" cellspacing="10" cellpadding="10">
             <caption>SLOT TIME TABLE HEMA(24011259) </Caption>
                </tr>
                <th>s.no</th>
                <th>subject code</th>
                <th>subject Name</th>
            </tr>
                 <td>1.</td>
                 <td>2681</td>
                 <td>physics</td>
        </tr>
        <tr>
                <td>2.</td>
                <td>19A1414</td>
                <td>FWAD</td>
        </tr>
        <tr>
                <td>3.</td>
                <td>19A1302</td>
                <td>edm</td>
        </tr>
        <tr>
                <td>4.</td>
                <td>19MA211</td>
                <td>statistics</td>
        </tr>
        <tr>
                <td>5.</td>
                <td>19A1304</td>
                <td>cprogramming</td>
                    </td>

                    </td>
                </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-11-12 144844.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
