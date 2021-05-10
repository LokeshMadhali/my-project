<!Doctype html>
<html lan="en" and dir="Itr">
<head>
    <meta charset="utf-8">
    <title>We are Welcoming You</title>
    <link rel="stylesheet" href="style1.css">
    <script src="login.js"></script>
    </head>
    <body>
    <form class="box" action="loginpage.html" method="post">
        <h1>
        Login
        </h1>
        <label>UserName</label><br>
        <input type="text" name="" placeholder="Enter Username" id="username"><br><br>
        <label>Password</label><br>
        <input type="password" name="" placeholder="Enter password" id="password"><br><br>
        <input type="submit" name="" value="Login" onclick="validate()">
        <p>Not yet registered</p>
        <button type="submit" action="register1.html">Register</button>
        </form>
    </body>
</html>
body{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
    background: url(background.jpeg);
    background-size: cover;
}
.box{
    width: 300px;
    padding: 30px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    background: rgba(0,0,0,0.4);
    text-align: center;
}
.box h1{
    color: white;
    text-transform: uppercase;
    font-weight: 700;
}
.box p{
    color: white;
}
.box input[type="text"],.box input[type="password"]{
    border: 0;
    background: none;
    display: block;
    margin: 20px auto;
    text-align: center;
    border: 3px solid #0367fd;
    padding: 14px 10px;
    width: 220px;
    outline: none;
    color: white;
    border-radius: 24px;
    transition: o.25px;
}
.box input[type="text"]:focus,.box input[type="password"]:focus{
    width: 270
    border-color:#ffc400ec;
    
}
.box input[type="submit"]
{
    border: 0;
    background: none;
    display: block;
    margin: 20px auto;
    text-align: center;
    border: 3px solid #ffc400ec;
    padding: 7px 5px;
    width: 110px;
    outline: none;
    color: white;
    border-radius: 24px;
    transition: 0.25px;
    cursor: pointer;
}
.box input[type="submit"]:hover{
    background: #ffc400ec;
}
.box input[type="button"]
{
    border: 0;
    background: none;
    display: block;
    margin: 20px auto;
    text-align: center;
    border: 3px solid #ffc400ec;
    padding: 7px 5px;
    width: 110px;
    outline: none;
    color: white;
    border-radius: 24px;
    transition: 0.25px;
    cursor: pointer;
}
.box input[type="register"]:hover{
    background: #ffc400ec;
}
.box1{
    width: 300px;
    padding: 30px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    background: rgba(0,0,0,0.4);
    text-align: center;
}
.box h3{
    color: white;
    text-transform: uppercase;
}

<!Doctype html>
<html lan="en" and dir="Itr">
<head>
    <meta charset="utf-8">
    <h2>You can register here</h2>
    
    </head>
    <body>
    <form class="box1" action="register.html" method="post">
        <h3>
        Register
        </h3><label>First Name:</label><br>
        <input type="text" name="" placeholder="Enter Your Firstname" id="fname"><br><br>
        <label>Last Name:</label><br>
        <input type="text" name="" placeholder="Enter Your Lastname" id="lname"><br><br>
        <label>Your Age:</label><br>
        <input type="number" name="" placeholder="Enter Your Age" id="age"><br><br>
        <label>Email:</label><br>
        <input type="email" name="" placeholder="Enter Your Valid Email" id="email"><br><br>
        <label>Gender:</label>
        <input type="radio" name="" id="male">
        &nbsp;
        <span id="male">Male</span>
        &nbsp;
        <input type="radio" name="" id="female">
        &nbsp;
        <span id="female">Female</span>
        <br><br>
        <label>Address</label><br>
        <input type="text" name="" placeholder="Enter Your Address"id="address"><br><br>
        <input type="submit" name="" value="Submit" onclick="validate()">
        </form>
    </body>
</html>
