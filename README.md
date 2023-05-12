# recipes

import db from './firebase'....feed...
    
    
import db from './firebase'..tweetbox

import firebase from 'firebase'


const firebaseConfig = {
    apiKey: "AIzaSyCzyVe9YMfWV-Dxep52BaA-ulOzELhqqoE",
    authDomain: "twitter-clone-73f66.firebaseapp.com",
    projectId: "twitter-clone-73f66",
    storageBucket: "twitter-clone-73f66.appspot.com",
    messagingSenderId: "401952626886",
    appId: "1:401952626886:web:373394d1dd4b857147dfc7",
    measurementId: "G-DC5EJT1RY9"
  };

  const firebaseApp = firebase.initializeApp(firebaseConfig)
  const db = firebaseApp.firestore()

  export default db;
