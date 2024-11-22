# Ex03 Time Table
## Date:18.11.24

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
        <table border="2"
        cellspacing="15"
        cellpadding="5"
        <capion>
            SLOT TIMETABLE-YAZHINI.R.R(24900920)
        </capion>
        <tr bgcolor="yellow">
            <th>DAY/TIME</th>
            <th> MONDAY</th>
            <th>TUESDAY</th>
            <th> WEDNESDAY</th>
            <th> THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
            <td>FREE SLOT</td>
            <td>HUMAN VALUES</td>
            <td>PROBABILITY</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>C PROGRAMMING LANGUAGE</td>
            <td>CARRER DEVELOPMENT</td>
            <td>C PROGRAMMING LANGUAGE</td>
            <td>PROBABILITY</td>
        </tr>
        <tr>
            <td>12-1</td>
            <td colspan="6">LUNCH BREAK</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td>CHEMISTRY</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>MENTOR MEET</td>
            <td>CHEMISTRY</td>
            <td>WEB APPLICATION</td>
            <td>WEB APPLICATION</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td colspan="6">FREE SLOT</td>
            </tr>
        </table>
        <table border="2"
        cellspacing="15"
        cellpadding="5">
        <caption COURSES>
            <tr bgcolor="cyan">
            <th>S.NO</th>
            <th>COURSE CODE</th>
            <th>COURSE NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION(WEB)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>SH2222</td>
                <td>PROBABILITY AND QUEEING MODELS(PROBABILITY)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI304</td>
                <td>FUNDAMENTALS OF C PROGRAMMING LANGUAGE(C PROGRAMMING)</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH(ENGLISH)</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19CY205</td>
                <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING(CHEMISTRY)</td>
            </tr>
            <tr>
                <td>6</td>
                <td>ECA-M-SCOFT</td>
                <td>MENTOR MEET</td>
            </tr>
            <tr>
                <td>7</td>
                <td>SH7801</td>
                <td>HUMAN VALUES AND PROFESSIONAL ETHICS(HUMAN VALUES)</td>
            </tr>
            <tr>
                <td>8</td>
                <td>19EY708</td>
                <td>CARRER DEVELOPMENT SKILLS</td>
            </tr>
        </table>
    

## OUTPUT
![alt text](<Screenshot (44).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
