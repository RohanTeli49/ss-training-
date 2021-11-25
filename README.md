# ss-training-
Learning modules
<html>
    <head>
        <title>
            login page
        </title>
        <link rel="stylesheet" type="text/css" href="style.css">
        
    </head>
<body>
    <div class="login">
        <h1></h>Login Here</h1>
        <form>
            <p><h2>Username</h2></p>
            <input type="text" name="" placeholder="Enter Username">
            <p><h2>Password</h2></p>
            <input type="password" name="" placeholder="Enter Password">
            <input type="Submit" name="" value="Login">
            <a href="#">Forget Password</a><br>
            <a href="#">Don't have an account</a>
        </form>
    </div>
</body>
</html>
body{
    margin: 0;
    padding: 0;
    background-color: rgb(173, 185, 206);

}
.login{
    width: 350px;
    height: 450px;
    background: rgb(230, 216, 216);
    color: rgb(15, 0, 0);
    top: 50%;
    left: 50%;
    position: absolute;
    transform: translate(-50%,-50%);
    box-sizing: border-box;
    padding: 70px 30px;
}
 h1{
     margin: 0;
     padding: 0;
     text-align: center;
     font-size: 30px;
}
h2{
    margin: 0;
    padding: 0;
    font-size: 20;
}
.login p{
    margin: 0;
    padding: 0;
    font-weight: bold;
}
.login input{
    width: 100%;
    margin-bottom: 20px;
}
.login input[type="text"], input[type="password"]
{
    border: none;
    border-bottom: 1px solid #fff;
    background: transparent;
    outline:  none;
    height: 40px;
    color: rgb(8, 8, 8);
    font-size: 16px;
}
.login input[type="submit"]
{
    border: none;
    outline: none;
    height: 40px;
    background: #fb2525;
    color: #fff;
    font-size: 18px;
    border-radius: 20px;
}
