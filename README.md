# Form-Assignment
HTML , CSS  , JAVASCRIPT
<html>
<head>
<title> Photography Session Booking Form</title>
<link rel="stylesheet" href="form.css">
<script src="form-validation.js"></script>
</head>	    
<header>
<img src="logo.png" align alt="template image" height="150px" width="250px"  >      
<h2> PHOTOGRAPHY SESSIONS </h2>
</header>
<body bgcolor="Coral" onload="document.registration.userid.focus();">
	<div class="text">
	<h3> Our Policy</h3>
	<p> We need to collect, use and disclose personal information in order to perform our business functions and activities. 
	We are firmly committed to protecting the privacy and confidentiality of personal information with various physical, 
	electronic and procedural safeguards.We use your images on social media.  </p>
	<h3>Legal:</h3>
	<p> Photogrpahers are protected by federal copyright laws. 
		you understant it is Illegal to scan, copy, print or reproduce 
 		without photographers permission and violators of this fedral 
		law will bw subject to its civil and ceiminal penalties. 
	</p>
	<h3>Instructions:</h3>
	<p>	You understand that the session is not confirmed until the retainer is paid.
		Cancellations will be made at the photographers discreation. 
		Your session will remain with in the scheduled time frame.If you need to reschedule you will give
		contact prior 48 hours notice of said reserved session date. </p></div>
	<div id="container">
<main>
	<fieldset><h3 align="center"> Photography Session Booking Form</h3>
	<form name='registration' onSubmit="return formValidation();">
	<fieldset><br>
	<legend> User Account Registration </legend>
	 UserName :<input type="text" name="userid"><br><br>
	 Choose your password:<input type="password"  name="passid"><br><br>
 	</fieldset><br>
<fieldset><br>
	<legend>Personal Information</legend>
	 Name:  <input type="text" name="username"><br><br>
	 Gender: <input type="radio" name="msex" value="Male" />Male
		 <input type="radio" name="fsex" value="Female"/>Female
	<br><br>
	 Marital Status:<input type="radio" name="m" value="Married" />Married
		<input type="radio" name="un" value="Single"/>Unmarried<br><br>
	 E-mail id   :<input type="text"  name="email"><br><br>
 	 Contact Number:<input type="text"  name="ph"><br><br>
 	</fieldset><br>
	
<fieldset>
	<legend>Address:</legend><br>
	Country:<select name="country">
	<option selected="" value="Default">(Choose your Country)</option>
	<option value="AF">Australia</option>
	<option value="AL">Canada</option>
	<option value="DZ">India</option>
	<option value="AS">Russia</option>
	<option value="AD">USA</option> </select> <br><br>
	State/Province:<input type="text" name="state"><br><br>
	City:<input type="text" name="City"><br><br>Street Address:<input type="text" name="address"><br><br>
	Street Address line2: <input type="text" name="address2"><br><br>
	Postal/Zip Code:<input type="text" name="zip"><br><br>
	<br>
</fieldset><br>

<fieldset>
	<legend>Appointment Information:</legend><br>
 	Select an Appointment Date:
  	<input type="date" name="date"><br><br>
  	Did Deep Photography give you a session to confirm prior to filling out this form?<br><br>
	<input type="radio" name="Yes">Yes. Continue with form submition<br>
	<input type="radio" name="no">No, Please contact Deep Photography for a Session Date.<br><br>
	Type of Session:
	<input type="radio" name="s1"> Morning	<input type="radio" name="s2"> Evening <br><br>
</fieldset><br>
	
<fieldset><legend>Other Information:</legend><br>
	Note to Photographer:	<textarea name="desc" id="desc"></textarea>	
</fieldset><br>

<fieldset>Choose your Language:
	<li><input type="checkbox" name="en" value="en" checked /><span>English</span></li>
	<li><input type="checkbox" name="nonen" value="noen" /><span>Non English</span></li>

	<center>
	<input type="Submit" name="Submit" value="Submit Form">
	<input type="Reset" name="Reset">
	</center>
</form></select>
</fieldset></div></fieldset></form>
</main>
</html>
