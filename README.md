# Using firebase

Log to firebase using your goole account
got to pricing and choose free plan
Create a new project with default settings, disabling google analytics
Got to create, and realtime database
Create database in "test mode"

create a secret. js fil in your src folder root looking like

```
export const firebaseURL = 'https://your firebase-urlfirebasedatabase.app/'
```

then add to git ignore

```
# firebase URL not sent to github
src/secret.js
```
