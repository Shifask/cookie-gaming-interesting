Create a Login page using HTML.
Once the user submits the form, write Javascript code which will perform the following tasks:
1. Check if the username & password supplied is valid or invalid
  For ex: check if the username is LTI and password is 123
2. If the user is invalid then show an error message to the user:
  Invalid Username/Password. Try again!
3. In case of a valid user, transfer the control to a welcome HTML page which will display a
message “Welcome Back, <Logged In Username>”
4. If the Remember Me option was selected in case of a valid user, then the username &
password should be encrypted and stored in a cookie on the client machine for 24 hours
5. Now for the next 24 hours if Login page is opened, you need to check if the required
cookie is present, decrypt the username & password and if the data is valid, automatically
transfer the control to the welcome page.
