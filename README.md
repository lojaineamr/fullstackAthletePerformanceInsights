when you unzip the files make a new .env file and include in it this:
PORT=3000
JWT_SECRET=secret_key
then open the terminal and make a split terminal and run the commands:
cd frontend 
npm install
npm start
it will say that there is something running on the same port click the button y it will work
in the other terminal run:
cd backend
npm install
npm run dev
