A flip-card resource for all things command line and git!
## You can make a website by this HTML code

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harry Fitness</title>

</head>
<link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@500&display=swap" rel="stylesheet">
<link rel="stylesheet" href="CSS/style.css">
<style>
    /* CSS reset*/
    body {
        font-family: 'Baloo Bhai 2', cursive;
        color: white;
        margin: 0px;
        padding: 0px;
        background: url('new.png');
        background-repeat: no-repeat;
    }

    .left {
        /*border: 2px solid red;*/
        color: yellow;
        display: inline-block;
        position: absolute;
        left: 34px;
        top: 20px;
        font-size: 17px;
        line-height: 13px;
    }

    .left img {
        width: 50px;
        filter: invert(100%);
        padding-left: 24px;
    }

    .mid {
        display: block;
        width: 52%;
        margin: 20px auto;
        /*border: 2px solid green;*/
    }

    .right {
        position: absolute;
        right: 34px;
        top: 20px;
        /*border: 2px solid yellow;*/
    }

    .navbar {
        display: inline-block;
        margin: 1px;

    }

    .navbar li {
        font-size: 14px;
        display: inline-block;
    }

    .navbar li a {
        color: white;
        text-decoration: none;
        padding: 34px 23px;
    }

    .navbar li a:hover,
    .navbar li a.active {
        text-decoration:underline;
        color: red;
    }

    .btn {
        margin: 0px 9px;
        background-color: black;
        color: #08afff;
        padding: 2px 13px;
        border: 2px solid gray;
        border-radius: 6px;
        font-size: 9px;
        cursor: pointer;
        font-family: 'Baloo Bhai 2', cursive;
    }

    .btn:hover {
        background-color: rgb(48, 46, 46);

    }

    .container {
        /*border: 2px solid #e3edf4;*/
        display: inline-block;
        margin: 60px 645px;
        padding: 21px 40px;
        width: 33%;
        border-radius: 8px;
    }

    .form-group input {
        font-size: 14px;
        text-align: center;
        display: block;
        width: 233px;
        padding: 2px;
        border: 2px solid black;
        margin: 3px auto;
        border-radius: 8px;
        font-family: 'Baloo Bhai 2', cursive;

    }
    .container h4{
        text-align: center;
    }
    .container button{
        display: block;
        width: 58.5%;
        margin: 5px auto;
        padding: 2.5px;
        font-size: 12px;
    }
</style>

<body>
    <header class="header">
        <!-- Left box for logo -->
        <div class="left">
            <img src="new3.png" alt="">
            <div>
                Harry Fitness
            </div>
        </div>

        <!-- Mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <!-- <li><a href="#" class="active">Home</a></li> -->
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact us</a></li>
            </ul>
        </div>

        <!-- Right box for buttons -->
        <div class="right">
            <button class="btn">Call us Now</button>
            <button class="btn">Email Us</button>
        </div>
    </header>
    <div class="container">
        <h4>Join the best gym of Delhi now</h4>
        <form >
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your City">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Email-ID">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Phone number">
            </div>
            <button class="btn">Submit</button>
            <button class="btn">Reset</button>
        </form>
    </div>
</body>

</html>

#### I hope this will be usefull for someone
