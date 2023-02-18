// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyDvlS9E8Fx75P0ugZpK4lDWRQ-c2n41bew",
  authDomain: "stimmungsindex-b39d1.firebaseapp.com",
  projectId: "stimmungsindex-b39d1",
  storageBucket: "stimmungsindex-b39d1.appspot.com",
  messagingSenderId: "754586593124",
  appId: "1:754586593124:web:e58b378d851eed37a63c71",
  measurementId: "G-GQM7SZNBBX"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);