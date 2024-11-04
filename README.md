<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>REGISTRSTION</title>
    <link rel="stylesheet" href="form.css">
</head>

<body>
    <h2>EVENT REGISTRSTION FORM</h2>
    <form action="/register" method="post">
        <label for="name">name:</label>
        <input type="text" id="name" name="name" required>
        <label for="rollnumber">roll number:</label>
        <input type="rollnumber" id="rollnumber" name="roll number" required>

        <label for="emial">emial:</label>
        <input type="email" id="emial" name="emial" required>
        <label for="phone">phone:</label>
        <input type="text" id="phone" name="phone" required>
        <input id="btn" type="submit" value="register">
    </form>
</body>

</html>
