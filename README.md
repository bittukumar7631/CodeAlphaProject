# CodeAlphaProject
Task 1 Assigment of COde Alpha
<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Survey Form</title>
	<link rel="stylesheet" href="style.css">
</head>

<body>
	<!-- heading -->
	<h1>CodeAlpha - Survey Form</h1>

	<!-- start the form -->
	<form id="form">

		<!-- for first name and second name -->
		<div class="formtag">
			<label for="first_name">First Name</label>
			<input type="text" id="first_name" placeholder="Enter your first names">
		</div>
		<div class="formtag">
			<label for="last_name">Last Name</label>
			<input type="text" id="last_name" placeholder="Enter your last name">
		</div>

		<!-- for gender -->
		<div class="formtag">
			<label>Gender</label>
			<label for="gender1">
				<input type="radio" id="gender1" name="gender" value="Male">Male</label>
			<label for="gender2">
				<input type="radio" id="gender2" name="gender" value="Female">Female</label>
		</div>

		<!-- for contact number -->
		<div class="formtag">
			<label for="contact">Contact Number</label>
			<input type="number" id="contact" name="contactnumber" placeholder="Enter your 10-digit number">
		</div>

		<!-- for e-mail -->
		<div class="formtag">
			<label for="email">E-mail Address</label>
			<input type="email" id="email" name="emailaddress" placeholder="Enter your e-mail here">
		</div>


		<!-- for age -->
		<div class="formtag">
			<label for="age">D-O-B</label>
			<input type="date" id="age" name="birthday">
		</div>

		<!-- for the College name -->
		<div class="formtag">
			<label for="college" id="add">Enter your college name</label>
			<input type="text" id="college" name="collegename" placeholder="Enter your college name">
		</div>

		<!-- current profession -->
		<div class="formtag">
			<label for="profession">Current Occupation</label>
			<select id="profession">
				<option selected disabled>Select your profession</option>
				<option>Student</option>
				<option>Employee</option>
				<option>Looking for a job</option>
			</select>
		</div>

		<!-- Domain choosing by using checkbox -->
		<div class="choose">
			<label>Choose your internship domain in "CodeAlpha"</label>
			<br>
			<div class="options">

				<input type="checkbox" id="domain1" name="domain">
				<label for="domain1">C++</label>
				<br><br>

				<input type="checkbox" id="domain2" name="domain">
				<label for="domain2">WEB DEVELOPMENT</label>
				<br><br>

				<input type="checkbox" id="domain3" name="domain">
				<label for="domain3">PYTHON DEVELOPMENT</label>
				<br><br>

				<input type="checkbox" id="domain4" name="domain">
				<label for="domain4">JAVA DEVELOPMENT</label>
				<br><br>

				<input type="checkbox" id="domain5" name="domain">
				<label for="domain5">CYBER SECURITY </label>
				<br><br>

				<input type="checkbox" id="domain6" name="domain">
				<label for="domain6">DEVOPS </label>
				<br>
			</div>
		</div>
		</div>

		<!-- for Feedback -->
		<div class="formtag">
			<label for="feedback">Feedback (optional)</label>
			<textarea id="feedback" name="yourfeedback" placeholder="Give the Feedback of your journey"></textarea>
		</div>

		<!-- submit button -->
		<button type="submit" value="submit">Submit</button>
	</form>
</body>

</html>
