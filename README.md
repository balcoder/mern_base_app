# Full Stack MERN Base App

### About

Full stack MERN (MongoDB, Express.js, React, and Node.js.) base app with authentication using JWT, Firebase, and Google OAuth and all the signin/signup, delete and update functionality for users with the image storage in firebase and the database in mongoDB.You can follow the instructions in the pdf or just clone the git repo and have all the basic functionality ready to go for your next project.

### To Run

1. Clone to folder of your choice.
2. Change the env.example content in the root folder to your information from
   mongodb and make your own unique Json web token (jwt) secret key, just tap
   on your keyboard a bunch of times.
3. Then save env.example as .env
4. Change the firebase config file at client/firebase.js to your own firebase
   config settings and then change the env.example for firebase in the client folder
   to your firebase key and save it as .env
5. Now you can run _npm run dev_ in both the root folder which is the backend api
   and client folder which is the react frontend.

6. In the root of the app which is your backend run _npm run dev_
   The api terminal should look like this after running _npm run dev_
   ```
   [nodemon] 3.1.9
   [nodemon] to restart at any time, enter `rs`
   [nodemon] watching path(s): _._
   [nodemon] watching extensions: js,mjs,cjs,json
   [nodemon] starting `node api/index.js`
   Express Server running on port 3000!!!
   Connected to MongoDB
   ```
7. Open up another terminal and cd into the client folder and run _npm run dev_
   The terminal should look like this.

VITE v6.2.5 ready in 4365 ms

➜ Local: http://localhost:5173/
➜ Network: use --host to expose
➜ press h + enter to show help

ctrl+click http://localhost:5173/ and you will see your app in the browser

Good luck with your app.
