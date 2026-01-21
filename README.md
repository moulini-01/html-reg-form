# html-reg-form
registration form online in html language 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>registration form</title>
</head>
<body>
    <h1> registration form</h1>
    <form>
        <label> First Name: <input type="text" name="firstname" placeholder="firstname"required></label>
        <label>last name:<input type="text" name="lastname" placeholder="lastname"required></label>
        <label> male <input type="radio" name="gender" value="male"></label>
        <label>female <input type="radio" name="gender" value="female"></label>
        <label>other <input type="radio" name="gender" value="other"></label><br>
        <label> email <input type="email" name="email" placeholder="your email" required></label>
        <label>password <input type="password" placeholder="your password" pattern=".{5,10}" required title="please enter password length of 5 to 10"></label><br>
    </form>
</body>
</html>
