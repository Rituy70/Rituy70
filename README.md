<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Registration Form</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background: linear-gradient(45deg, #FF9A9E, #FFD3B7, #FFACAC, #84FAB0);
        background-size: 400% 400%;
        animation: gradientBG 15s ease infinite;
    }

    @keyframes gradientBG {
        0% {
            background-position: 0% 50%;
        }
        50% {
            background-position: 100% 50%;
        }
        100% {
            background-position: 0% 50%;
        }
    }
    
    .container {
        max-width: 500px;
        margin: 50px auto;
        background: rgba(255, 255, 255, 0.9); /* Semi-transparent white background */
        padding: 30px;
        border-radius: 10px;
        box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
    }
    
    h2 {
        text-align: center;
        color: #333;
    }
    
    input[type="text"],
    input[type="email"],
    input[type="password"] {
        width: calc(100% - 20px);
        padding: 12px;
        margin: 10px 0;
        border: none;
        border-radius: 25px;
        background-color: rgba(255, 255, 255, 0.8);
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    
    input[type="submit"] {
        width: calc(100% - 20px);
        background: linear-gradient(to right, #FF416C, #FF4B2B); /* Gradient background */
        color: #fff;
        border: none;
        padding: 12px;
        border-radius: 25px;
        cursor: pointer;
        transition: background 0.3s ease;
    }
    
    input[type="submit"]:hover {
        background: linear-gradient(to right, #FF4B2B, #FF416C); /* Gradient background on hover */
    }
    
    .form-group {
        margin-bottom: 20px;
    }
    
    .form-group:last-child {
        margin-bottom: 0;
    }
</style>
</head>
<body>

<div class="container">
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <div class="form-group">
            <input type="text" placeholder="Username" name="Username" required>
        </div>
        <div class="form-group">
            <input type="email" placeholder="Email" name="email" required>
        </div>
        <div class="form-group">
            <input type="password" placeholder="Password" name="password" required>
        </div>
        <div class="form-group">
            <input type="password" placeholder="Confirm Password" name="confirm_password" required>
        </div>
        <div class="form-group">
            <input type="submit" value="Register">
        </div>
    </form>
    
</div>

</body>
</html>
