<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<form>
<h1>Volunteer Form</h1>
<legend>Information</legend>
<div>
  <label>first name<input size="90" type="text" name "first_name_field"></label>
  <label>last name<input size="90" type="text" name "last_name_field"></label>
  <label>phone<input size="90" type="text" name "phone_field"></label>
  <label>email <input size="90" type="text" name "email_field"></label>
  <label>gender<input size="90" type="text" name "gender_field"></label>
</div>
<div>
     <label>Male <input type="radio" name="gender_field" value="male"></label>
     <label>Female <input type="radio" name="gender_field" value="female"></label>
	 <label>Other <input type="radio" name="gender_field" value="female"></label>
</div>
<div>Age: </div>
   <select name="age_field">
   <option>under 18</option>
   <option>over 18</option>
</select>
    <fieldset>
      <legend>My Availability</legend>
      <h3>Days Available:</h3>
      <div>
        <div><label>Sunday <input type="checkbox" name="available_field[]" value="sunday"></label></div>
        <div><label>Monday <input type="checkbox" name="available_field[]" value="monday"></label></div>
        <div><label>Tuesday <input type="checkbox" name="available_field[]" value="tuesday"></label></div>
        <div><label>Wednesday <input type="checkbox" name="available_field[]" value="wednesday"></label></div>
        <div><label>Thursday <input type="checkbox" name="available_field[]" value="thursday"></label></div>
        <div><label>Friday <input type="checkbox" name="available_field[]" value="friday"></label></div>
        <div><label>Saturday <input type="checkbox" name="available_field[]" value="saturday"></label></div>
        <h3>Comments</h3>
      </div>
    </fieldset>
</form>
</body>
</html>