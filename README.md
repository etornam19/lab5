<!DOCTYPE html>
<html lang="en">
  <meta charset="utf-8">
  <title>Document</title>
</head>
<body>
  <h1>Volunteer form</h1>
  <form method="post" autocomplete="on" action:"http://bloomingdale.sat.iit.edu/kriedan/lab3formscript.php" enctype="multipart/form-data">
    <fieldset>
      <legend>Your Info</legend>
      <div><label>first name: <input size="100" type="text" name="first_name_field"></label></div>
      <div><label>last name: <input size="100" type="text" name="last_name_field"></label></div>
      <div><label>phone: <input size="100" type="text" name="phone_field"></label></div>
      <div><label>email: <input size="100" type="text" name="email_field"></label></div>
      <div>Gender: </div>
      <div>
        <label>Male <input type="radio" name="gender_field" value="male"></label>
        <label>Female <input type="radio" name="gender_field" value="female"></label>
      </div>
      <div>Age: </div>
      <select name="age_field">
        <option>under 18</option>
        <option>over 18</option>
      </select>
    </fieldset>
    <fieldset>
      <legend>Your Availability</legend>
      <h3>Days Available:</h3>
      <div>
        <div><label>Sunday <input type="checkbox" name="available_field[]" value="Sunday"></label></div>
        <div><label>Monday <input type="checkbox" name="available_field[]" value="Monday"></label></div>
        <div><label>Tuesday <input type="checkbox" name="available_field[]" value="Tuesday"></label></div>
        <div><label>Wednesday <input type="checkbox" name="available_field[]" value="Wednesday"></label></div>
        <div><label>Thursday <input type="checkbox" name="available_field[]" value="Thursday"></label></div>
        <div><label>Friday <input type="checkbox" name="available_field[]" value="Friday"></label></div>
        <div><label>Saturday <input type="checkbox" name="available_field[]" value="Saturday"></label></div>
        <h3>Comments</h3>
        <textarea name="comments_field"></textarea>
      </div>
    </fieldset>
      <div>
        <input type="hidden" name="hidden_field" value="eadevor">
      </div>
      <input type="submit" value="Submit!"> 
  </form>
</body>
</html>
