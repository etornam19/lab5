<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Document</title>
</head>
<body>
  <h1>College Application</h1>
  <form method="post" autocomplete="on" action="http://bloomingdale.sat.iit.edu/kriedan/lab3formscript.php" enctype="multipart/form-data">
    <fieldset>
      <legend>Your Info</legend>
      <div><label>first name: <input size="100" type="text" name="first_name_field"></label></div>
      <div><label>last name: <input size="100" type="text" name="last_name_field"></label></div>
      <div><label>phone: <input size="100" type="text" name="phone_field"></label></div>
      <div><label>email: <input size="100" type="text" name="email_field"></label></div>
      <div><label>level of education: <input size="100" type="text" name="level_of_education_field"></label></div>
      <div><label>grade point average: <input size="100" type="text" name="grade_point_average_field"></label></div>
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
      <legend>Your Anticipated Major(s)</legend>
      <h3>Available Majors:</h3>
      <div>
        <div><label>Computer Science <input type="checkbox" name="available_field[]" value="Computer_Science"></label></div>
        <div><label>Psychology <input type="checkbox" name="available_field[]" value="Psychology"></label></div>
        <div><label>Public Health <input type="checkbox" name="available_field[]" value="Public_Health"></label></div>
        <div><label>Information Technology Management <input type="checkbox" name="available_field[]" value="Information_Technology_Management"></label></div>
        <div><label>Biomedical Engineering <input type="checkbox" name="available_field[]" value="Biomedical_Engineering"></label></div>
        <div><label>Pre-Med <input type="checkbox" name="available_field[]" value="Pre-Med"></label></div>
        <div><label>Humanities <input type="checkbox" name="available_field[]" value="Humanities"></label></div>
        <h3>Any Comments?</h3>
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
