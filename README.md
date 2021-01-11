# ReactJS-Firebase Login-SignUp (Authentication and Authorization)

This is a starter template for Javascript-ReactJS developer

**Language:** JavaScript-NodeJS, ReactJS, Firebase and Tailwindcss


## Prerequsition

-[Node.js](https://nodejs.org/en/download/)
-Text editor - [VS-code](https://code.visualstudio.com/) 
- Google Firestore account - [Firestore docs](https://firebase.google.com/docs/firestore/quickstart#web) or [Video](https://www.youtube.com/watch?v=2Vf1D-rUMwE&feature=youtu.be)


## Demo

Feel free to see the example and play around with the files

![](https://salweyar.github.io/images/react-firebase/react-firebase-login-signup.gif)

## Usage

1. Create a folder anywhere in your pc then open terminal and Clone this repo

   ```bash
   cd projectName
   git clone https://github.com/Salweyar/Reactjs-firebase.git
   ```

2. Install dependencies

   ```bash
   npm install
   ```
   
3. Create file under /src/config/fire.js and paste the code

   ```bash
   import firebase from "firebase";

   var firebaseConfig = {
   apiKey: "Api key from firestore",
   authDomain: "authDomain from firestore",
   databaseURL: "databaseURL from firestore",
   projectId: "projectId from firestore",
   storageBucket: "storageBucket from firestore",
   messagingSenderId: "messagingSenderId from firestore",
   appId: "appId from firestore"
   };

   const fire = firebase.initializeApp(firebaseConfig);
   export default fire;
    ```

4. start the development server

   ```bash
   npm start
   ```
