
check points https://youtu.be/hT3j87FMR6M?t=3940

add firebase.js into src

```
//    src/firebase.js

import firebase from 'firebase/app';
import 'firebase/firestore';

const firebaseConfig = firebase.initializeApp({
    apiKey: YOUR_API_KEY,
    authDomain: YOUR_AUTH_DOMAIN,
    databaseURL: YOUR_DATABASE_URL,
    projectId: YOUR_PROJECT_ID,
    storageBucket: YOUR_STORAGE_BUCKET,
    messagingSenderId: YOUR_M_S_ID,
    appId: YOUR_APP_ID
});

export { firebaseConfig as firebase };

```
