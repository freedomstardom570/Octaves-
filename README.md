<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up</title>
</head>
<body>
    <h1>Sign Up</h1>
    <form action="signup_process.php" method="POST">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label for="phone">Phone number:</label>
        <input type="tel" id="phone" name="phone" required><br><br>

        <label for="matriculation">Matriculation number:</label>
        <input type="text" id="matriculation" name="matriculation" required><br><br>

        <input type="submit" value="Sign Up">
    </form>
</body>
</html>

