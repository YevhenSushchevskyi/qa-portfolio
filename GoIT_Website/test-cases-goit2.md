✅ Test Cases – GoIT Website

TC ID	Title	Precondition	Steps	Expected Result	Status
TC001	Valid login	User is registered and on the login page
Open the login page<br>2. Enter a valid email and password<br>3. Click "Login"
User is redirected to the dashboard	Pass
TC002	Invalid login	User is registered and on the login page
Open the login page<br>2. Enter a valid email and an incorrect password<br>3. Click "Login"
Error message is displayed	Pass
TC003	Empty login fields	User is on the login page
Open the login page<br>2. Leave both fields empty<br>3. Click "Login"
Validation error messages are displayed	Pass
TC004	Register new user	User is logged out and on the registration page
Open the registration page<br>2. Enter valid information<br>3. Click "Register"
Confirmation message appears	Pass
TC005	Submit empty contact form	User is on the "Contact Us" page
Open the "Contact Us" page<br>2. Leave all fields empty<br>3. Click "Submit"
Validation errors are shown below the fields	Pass
TC006	Submit valid contact form	User is on the "Contact Us" page
Open the "Contact Us" page<br>2. Fill in name, email, and message<br>3. Click "Submit"
Thank-you message is displayed
