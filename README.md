# Creating a React chat room with firebase and deploying to Firebase Web hosting 

Create a project inside firebase console.

Afterwards create a new cloud firestore db.

# Auth: Google Sign

Inside the newly created project, enable google sign in auth.

# Deploying to firebase

Intall firebase tools globally by running in your terminal

### `npm install -g firebase-tools`

Afterwards login in to your firebase account

### `firebase login`

Then at the root of your project initialize a firebase CLI

### `firebase init`

Choose Hosting option and follow the prompts. (Do not overwhite your public html)

Then run and build your application by running in your terminal

### `yarn run build`

Then finally deploy by typing

### `firebase deploy`



