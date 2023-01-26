# Registration-Form

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <style>
        h1{
            margin: 0px;
        }
        body{
            background-color: rgb(146, 235, 243);
        }
    </style>
</head>
<body>
    <h1>Registration Form</h1>
    <p>Enter your datails belows</p>

    <li>
        <input type="email" name="" id="" placeholder="your_email@gmail.com">
    </li>
    <br>
    <li><input type="password" name="" id="" placeholder="password"></li>

    <p><strong>!Type a complex password with 8-20 characterss</strong></p>
    <li><input type="number" name="" id=""placeholder="+91 Phone Number"></li>

    <hr>

    <p><b>Enter your Professsion:</b></p>
    <li><input type="radio" name="" id="">Student
    <input type="radio" name="" id="">Teacher
    <input type="radio" name="" id="">Developer
    <input type="radio" name="" id="">Employee
    </li>
    <br>
    Choose the stage if you are (student):
    <select name="" id="">
        <option value="">First Name</option>
        <option value="">Middle Name</option>
        <option value="">Last Name</option>
    </select>    
    <hr>

    <li>
        <label for="">Enter the birthdate.</label>
        <input type="date" name="" id="">
    </li>
    <hr>
    <li>
        <input type="text" placeholder="Any Notes">
    </li>
    <br>
    <input type="button" value="submit">
    <input type="reset" value="reset">
</body>
</html>
