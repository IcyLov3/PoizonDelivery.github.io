<!DOCTYPE html>
<html>
<head>
 <title>Delivery form</title>
</head>
<body>
 <h1>Delivery</h1>
 <form action="submit-form.php" method="post">
  <label for="first_name">First Name:</label>
  <input type="text" id="first_name" name="first_name" required>
  <br>
  <label for="last_name">Last Name:</label>
  <input type="text" id="last_name" name="last_name" required>
  <br>
  <label for="phone">Phone:</label>
  <input type="tel" id="phone" name="phone" required>
  <br>
  <label for="address">Addres:</label>
  <textarea id="address" name="address" required></textarea>
  <br>
  <input type="submit" value="Send form">
 </form>
</body>
</html>
