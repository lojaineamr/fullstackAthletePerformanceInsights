when you unzip the files make a new .env file and include in it this:
  PORT=3000
  JWT_SECRET=secret_key
then open the terminal and make a split terminal and run the commands:
  cd frontend 
  npm install
  npm start
it will say:
  Something is already running on port 3000.   
  Would you like to run the app on another port instead? » (Y/n)
  click the button y it will work
in the other terminal run:
  cd backend
  npm install
  npm run dev
to login:
  username: admin
  password: admin123
