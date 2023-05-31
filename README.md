# registration_form
#html_code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>REGISTRATION FORM</title>
    <link rel="stylesheet" type="text/css" href="./style.css">
</head>
<body>
    <div class="registration-form">
        <h1>Registration Form</h1>
        <form action="#" mathod="post">
         <p>Full Name: </p>
         <input type="text" name="fullname" placeholder="Full Name">
         <p>User Name:</p>
         <input type="text" name="username" placeholder="User Name">
         <p>Email:</p>
         <input type="text" name="username" placeholder="Email">
         <p>Password:</p>
         <input type="text" name="username" placeholder="Password">
         <button type="submit">Registration</button>
        </form>
</body>
</html>
    
    #css_code

    *{
    padding: 0;
    margin: 0;
    font-family: sans-serif;
}

body{
    background: url('./bg.jpg'); no-repeat;
    background-size: cover;
    color: #fff;
}
.registration-form{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    width:350px;
}
.registration-form h1{
    font-size: 40px;
    text-align: center;
    text-transform: uppercase;
    margin: 40px 0;
}
.registration-form p{
    font-size: 20px;
    margin: 5px 0;
    border-radius: 0%;

}
.registration-form input{
    font-size: 16px;
    padding: 15px 10px;
    width: 100%;
    border-radius: 5px;
    outline: none;
}
.registration-form buttton{
    font-size: 18px;
    font-weight: bold;
    margin: 20px 0;
    padding: 8px 8px;
    width: 40%;
    border: 0;
    border-radius: 5px;
    background-color: #fff;
    border-radius: 0%;

}
.registration-form button:hover{
    color: red;
}
