# demo2
<!DOCTYPE html>
<html>
<head>
    <title>Login and Logout</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <div id="container">
        <div id="header">
            <h1>Welcome to Login and Logout Page</h1>
        </div>
        <div id="main">
            <form id="login-form">
                <h2>Login</h2>
                <input type="text" id="username" name="username" placeholder="Username">
                <input type="password" id="password" name="password" placeholder="Password">
                <input type="submit" value="Login">
            </form>
            <form id="logout-form">
                <h2>Logout</h2>
                <input type="submit" value="Logout">
            </form>
        </div>
    </div>
    <script src="scripts.js"></script>
</body>
</html>


body {
    font-family: Arial, sans-serif;
}

#container {
    width: 300px;
    margin: 0 auto;
}

#header {
    background-color: #f1f1f1;
    padding: 20px;
    text-align: center;
}

#main {
    padding: 20px;
}

form {
    margin-bottom: 20px;
}

input[type="text"], input[type="password"] {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
}

input[type="submit"] {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    width: 100%;
}

input[type="submit"]:hover {
    background-color
