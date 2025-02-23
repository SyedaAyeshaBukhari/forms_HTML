<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML FOTMS</title>
</head>
<body>
    <h1> HTML FORMS </h1>
    <form action="thankyou.html" mathod="GET"> <!--get and post method-->
        <label for="UserName">UserName</label>
        <input type="text" id="UserName" placeholder="UserName" required>

        <br> <br>

        <label for="password">Paaword</label>
        <input type="password" id="password" name="password" placeholder="password" required>

        <br> <br>

        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="email" required>

        <br> <br>

        <input type="submit" value="sign in">
    </form>
</body>
</html>
