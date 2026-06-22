# first
I am the greatest
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Patient Registration Form</title>
</head>
<body>
     <h1>Patient Registration Form.</h1>
    <p>Please fill in your required details below in all requested fields.</p><br>
    <form action="">
    <label for="">Full name:</label>
    <input type="text"><br><br>
    <label for="">Email Address:</label>
    <input type="text"><br><br>
    <label for="">Phone number:</label>
    <input type="number"><br><br>
    <label for="">Date of Birth:</label>
    <input type="text"><br><br>
    <label for="">Gender:</label>
    <select name="gender" id="gender">
    <option value="">Male</option>
    <option value="">Female</option>
    <option value="">Other</option>
    </select>
    <hr>
    <label for="">Services required</label><br>
    <input type="checkbox" value="Consultation">
    <label for="">Consultation</label><br>
    <input type="checkbox" value="Laboratory">
    <label for="">Laboratory</label><br>
    <input type="checkbox" value="Test">
    <label for="">Test</label><br>
    <input type="checkbox" value="Pharmacy">
    <label for="">Pharmacy</label><br><br>
    <label for="">Country of Residence</label>
    <select name="country" id="country">
    <option value="">Kenya</option>
    <option value="">Tanzania</option>
    <option value="">Ethiopia</option>
    <option value="">Uganda</option>
    </select><br><br>
    <textarea name="comment" id="" rows="5" cols="40">Thank you for choosing Melvin Hospital. Get well soon!</textarea><br><br>






    <input type="submit" value="Submit">
    <input type="reset" value="Reset">


    </form>
</body>
</html>
