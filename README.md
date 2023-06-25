<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grocery World</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Balsamiq+Sans&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Balsamiq Sans', cursive;
            color: white;
            margin: 0px;
            padding: 0px;
            background-image: url('groceries.jpg');
            background-size: 100%;
            background-repeat: no-repeat;

        }

        .left {
            display: inline-block;
            position: absolute;
            left: 34px;
            top: 15px;
            

        }

        .left img {
            width: 50px;
            filter: invert(100%);
        }

        .mid {
            display: block;
            width: 40%;
            margin: 15px auto;
            
        }

        .right {
            margin: 2px 3px;
            position: absolute;
            right: 34px;
            top: 15px;
            display: inline-block;
           
        }

        .right img {
            margin: 10px;
            filter: invert(100%);
            width: 50px
        }

        .right img:hover {
            transform: scale(1.2);
        }

        .shops {
            margin: 10px;
            padding: 5px 5px;
            float: left;
            text-align: center;
        }

        .shops:hover {
            cursor: pointer;
            color: lawngreen;
        }

        .navbar li {

            display: inline-block;
            font-size: 20px;

        }

        .navbar li:hover {
            transform: scale(1.2);
        }

        .navbar li a {

            color: white;
            padding: 34px 23px;
            text-decoration: none;
        }

        .word {
            text-align: center;
        }

        .navbar li a:hover {

            cursor: pointer;
            color: lawngreen;
        }

        .container {
            text-align: center;
            margin: 40px;
            padding-left: 0px;
           
            padding-top: 25px;

        }

        .form {
            padding: 2px;
            height: 300px;
            margin: 50px;
            
        }

        .form h2 {
            display: block;
            width: 15%;
            margin: auto;
        }

        .form-group input {
            text-align: center;
            display: block;
            width: 500px;
            height: 30px;
            border-radius: 20px;
            font-family: 'Balsamiq Sans', cursive;
            font-size: larger;
        }
        .form-group input:hover{
            transform: scale(1.1);
            color:black;
            cursor:pointer;
        }


        .form-group {
            margin-left: 400px;
            margin-top: 30px;
        }
        

        .btn {
            height: 30px;
            font-family: 'Balsamiq Sans', cursive;
            display: block;
            width: 10%;
            margin-top: 27px;
            margin-left: 591px;
            border-radius:20px
        }
        .btn:hover{
            transform:scale(1.2);
            cursor:pointer;
           background-color: grey;
        }
    </style>
</head>
<link rel="stylesheet" href="style.css">


<body>
    <header class="header">
        <div class="left">
            <img src="logo2.jpg" alt="unable to upload image">
            <div class="word">

                GROCERY WORLD
            </div>
        </div>
        <div class="mid">

            <ul class="navbar">
                <li><a href=" ">Home</a></li>
                <li><a href=" ">About</a></li>
                <li><a href=" ">Services</a></li>
                <li><a href=" ">Contact us</a></li>
            </ul>

        </div>
        <div class="right">
            <img src="shop.jpg" alt="unable to upload image">
            <div class="shops">
                Shop now
            </div>
        </div>

    </header>
    <div class="container">
        <h1>"Instant Commerce Indistinguishable from Magic"</h3>
            <h3>Get your groceries delivered at home in 15 mins!</h3>
    </div>

    <div class="form">
        <h2>Login Now</h2>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Address">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your phone number">
            </div>
            <button class="btn">SUBMIT</button>
        </form>
    </div>

</body>

</html>
