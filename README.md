after cloning, when you unzip the files if its not created, make a new .env file and include in it this:
  PORT=3000
  JWT_SECRET=secret_key
then open the terminal and make a split terminal and run the commands:
  cd athlete-performance-tracker
  cd backend
  npm install
  npm run dev
in the other terminal run:
  cd athlete-performance-tracker
  cd frontend 
  npm install
  npm start
it will say:
  Something is already running on port 3000.   
  Would you like to run the app on another port instead? » (Y/n)
  click the button y it will work
to login:
  username: admin
  password: admin123

overview:
  This system allows admins to manage athletes, upload training videos, view performance over time, and generate reports. It uses an SQLite database and supports file uploads and   authentication.


Frontend:	React, Axios
Backend:	Node.js, Express.js
Database:	SQLite3
File Uploads:	Multer
Authentication:	JWT-based authentication


