<!DOCTYPE html>
<html>
<body>
    <body style="background-color:cornsilk;">
<h1>Log In</h1>

<form>
 <fieldset>
  <legend>Information:</legend>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  <label for="birthday">Birthday:</label>
  <input type="date" id="birthday" name="birthday"><br><br>
 <fieldset>
      <legend>Gender</legend>
    <div>
      <input type="radio" name="Gender" value="Gender,Female" id="G"/>
      <label for="G" >Female</label>
      <br/>
      <input type="radio" name="Gender" value="Gender,male" id="M"/>
      <label for="M">Male</label>
    </div>
  </fieldset>
  <br/>
  <input type="submit"/>
  <input type="reset"/>
 </fieldset>
</form>

</body>
</html>
