# recipes
{
  "name": "twitter-clone",
  "version": "0.1.0",
  "private": true,
  "dependencies": {
 
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-scripts": "5.0.1",
    "web-vitals": "^2.1.4"
  },
  //import firebase from 'firebase'
import firebase from "firebase/compat/app";
import "firebase/compat/firestore";
import "firebase/compat/auth";

const firebaseApp = firebase.initializeApp(firebaseConfig)
const db = firebaseApp.firestore()
export default db;


https://pbs.twimg.com/profile_images/1266938830608875520/f-eajIjB_400x400.jpg
