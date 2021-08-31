<template>
   <div>
      oi
   </div>
</template>
<script>
   // Import the functions you need from the SDKs you need
   import { initializeApp } from "firebase/app";
   import { getAnalytics } from "firebase/analytics";
   // TODO: Add SDKs for Firebase products that you want to use
   // https://firebase.google.com/docs/web/setup#available-libraries

   // Your web app's Firebase configuration
   // For Firebase JS SDK v7.20.0 and later, measurementId is optional

const firebaseConfig = {
  apiKey: "AIzaSyAmtDtlyrqkrGhnvovg5iqKxj8845iuJEU",
  authDomain: "traquejochat.firebaseapp.com",
  projectId: "traquejochat",
  storageBucket: "traquejochat.appspot.com",
  messagingSenderId: "433450788298",
  appId: "1:433450788298:web:af7d7518c0daf1dec01b33",
  measurementId: "G-JSE5M4E45G"
};

   // Initialize Firebase
   const app = initializeApp(firebaseConfig);
   const analytics = getAnalytics(app);
</script>

