


<!-- Time Table-->



<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initialscale=1.0">
    <title>Document</title>
</head>

<body>
    <h1>This is Time Table</h1>
    <table border="5" cellspacing="5" cellpadding="7">
        <!-- Table Head -->
        <thead>
            <tr>
                <th>Days/Period</th>
                <th>1</th>
                <th>2</th>
                <th>3</th>
                <th> </th>
                <th>4</th>
                <th>5</th>
                <th>6</th>
            </tr>
        </thead>
        <!-- Table Body -->
        <tbody>
            <tr>
                <td>Mon</td>

                <td>Science</td>
                <td>English</td>
                <td>Hindi</td>
                <td rowspan=" 6">BREAK</td>
                <td>Math</td>
                <td>Games</td>
                <td>Moral Science</td>
            </tr>
            <tr>
                <td>Tue</td>

                <td>Science</td>
                <td>English</td>
                <td>Hindi</td>

                <td>Math</td>
                <td>Games</td>
                <td>Moral Science</td>
            </tr>
            <tr>
                <td>Wed</td>
                <td>Science</td>
                <td>English</td>
                <td rowspan="3">Hindi</td>

                <td>Math</td>
                <td>Games</td>
                <td>Moral Science</td>


            </tr>
            <tr>
                <td>Thu</td>
                <td>Science</td>
                <td>English</td>


                <td>Math</td>
                <td>Games</td>
                <td>Moral Science</td>
            </tr>
            <tr>
                <td>Fri</td>
                <td>Science</td>
                <td>English</td>


                <td>Math</td>
                <td>Games</td>
                <td>Moral Science</td>
            </tr>
            <tr>
                <td>Sat</td>
                <td>Science</td>
                <td>English</td>
                <td>Hindi</td>

                <td colspan="3" >Math</td>
                
            </tr>
        </tbody>
        <!-- Table foot -->
        <tfoot>
            <tr>
                <th colspan="8">This is class VIII</th>
            </tr>
        </tfoot>
    </table>

</body>

</html>


<!--Bio-Data form-->



<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>biodata-form</title>
</head>

<body>
    <h1>My Bio Data</h1>

    <form action="#">
        <fieldset>
            <legend>Personal information</legend>

            <label for="name">FirstName:</label>
            <input type="text" placeholder="First Name" id="name" maxlength="8">

            <label for="lastname">LastName:</label>
            <input type="text" placeholder="Last Name" id="lastname" maxlength="8">
            <br>
            <br>
            Male:
            <input type="radio" name="gender">
            Female:
            <input type="radio" name="gender">
            Others:
            <input type="radio" name="gender">


            <br>
            <br>
            Date of birth:
            <input type="month" placeholder="mm/dd/yyyy">
            <br>
            <br>
            <label for="email"> E-Mail:</label>
            <input type="email" placeholder="Enter Your Email" id="email" required>
            <br>
            <br>
            <label for="1">Phone:</label>
            <input type="tel" placeholder="+91" id="1" maxlength="10">
            <br>
            <br>
            <label for="height">Hight:</label>
            <input type="text" placeholder="Height in feet" id="height">

        </fieldset>
        <fieldset>
            <legend>Education</legend>

            <label for="sname">School Name:</label>
            <input type="text" placeholder="School Name" id="sname">
            <br>
            <br>
            <label for="class">Class:</label>
            <input type="text" placeholder="Enter Class" id="class">
            <br>
            <br>
            Stream :
            <select name="Stream" id="stream">
                <option value="">Science</option>
                <option value="">Commerce</option>
                <option value="">Arts</option>
            </select>
            <br>
            <br>
            <label for="file">MarkSheet :</label>
            <input type="file" id="file">


        </fieldset>
        <br>

        <input type="submit" placeholder="Submit">
    </form>


</body>

</html>
