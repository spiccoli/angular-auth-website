# Angular Auth Website</br>
This project implements a user authentication system as I have previously done in php [https://github.com/spiccoli/authWebsite](https://github.com/spiccoli/authWebsite)  but now using the MEAN stack: </br></br>

MongoDB: Stores user data (e.g., username, email, password).</br></br>
Express.js: Handles HTTP requests and builds the backend API for authentication.</br></br>
AngularJS: Creates the frontend UI for the signup and signin forms.</br></br>
Node.js: Powers the backend and manages interactions with the database.</br></br>
Key Features:</br></br>
</br>
Signup: Users create an account with their credentials, which are validated and securely stored with hashed passwords.</br>
Signin: Users log in by verifying their credentials, with a session or JWT token generated for authenticated access.</br>
Validation: Both client-side (AngularJS) and server-side (Express.js) validation ensure data integrity.</br>
Security: Passwords are securely hashed, and sessions/tokens maintain authentication.</br>
