<!doctype html>

<html>

<head>

<title>Example of Forms</title></head>

<body>
							

			
				
<img src="Phone/DCIM/Screenshots/Screens hot 2022-02-04-21-41-23-99.png" hight"100">
				

<form acƟon="link.html" method="post" Autocomplete name="form1">

<Fieldset><legend>Personal InformaƟon</legend>

Firstname:<input type="text" name="fname" value="" maxlength=5 minlength=3 placeholder="must enter

name in capital" ><br>

Lastname:<input type="text" name="lname" ><br>

Surname:<input type="text" name="snam">

</fieldset>

<br>

<br>

<fieldset><legend>Contact detail</legend>

Password: <input type="password" name="password" > <br>

Hobbies:<br> <input type="checkbox" name="hobbies"

value="Dancing">

Dancing<br>

<input type="checkbox" name="hobbies" value="Travelling">Travelling<br>

<input type="checkbox" name"=hobbies" value="Reading" checked>Reading<br>

Gender:<input type="radio" name="gender" value="male">Male<br>

<input type="radio" name="gender" value="female" checked >Female<br>

File Upload:<input type="file" accept="image/*" mulƟple ><br>

Address:<textarea cols=15 rows=3 maxlength=100 minlength=5 name="address" placeholder="please enter

full address">

</textarea><br>

City:<select name="city">

<opƟon value="Baroda" >Baroda</opƟon>

<opƟon value="Surat">Surat</opƟon>

<opƟon value="Ahmedabad">Ahmedabad</opƟon>

</select><br>

</fieldset>

Course:<input name="course" list="course">

<datalist id="course">

<opƟon value="BCA">

<opƟon value="BCOM">

<opƟon value="BBA">

<opƟon value="B.E.">

</datalist><br>

range:<input type="range" min=5 max=100><input type="text" value="" id=ans>

age:<input type="number" name="age" max=100 min=5>

Search:<input type="search" name="search"><br>

Email:<input type="email" name="email" paƩern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,3}$"><br>

URL:<input type="url" name="weblink" paƩern="hƩp?://.+" placeholder="hƩp://www.google.com"><br>

Mobile:<input type="tel" name="mobile no" paƩern="[0-9\s]{5}[0-9]{5}" placeholder="5digits 5digits">

Date: <input type="date" max="2016-12-01" min="1900-01-01" ><br>

Month: <input type="Month" name="joinmonth"><br>

Select a Week:<input type="week" name="year_week"><br>

DateTime:<input type="dateƟme-local" name="dob"><br>

Ɵme:<input type="Ɵme" name="Ɵme"><br>

<label for="username">username:</label><input type="text"><br>

<input type="submit" name=submit" value="Submit">

<input type="reset" name="reset" value="Reset">

</form>

</body>

</html
