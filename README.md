# Firebase Setup and Hosting

## Set up Firebase for Authentication

1. Create a Firebase project.
2. Create a web app in the Firebase project.
3. Install Firebase by running `npm i firebase`.
4. Save the Firebase config and export the default app.
5. In the Firebase console, go to Build > Authentication > Get Started and enable sign-in method.
6. Create sign-up and login routes.

<!-- ## Setting up a Context Provider

1. Create a context provider file.
2. Create a context and set the provider.
3. Set the `children` props.
4. Set the context value.
5. Set the provider.
-->
## Hosting the project

### One-time Setup per Computer

1. Install firebase-tools using `npm install -g firebase-tools`.
2. Run `firebase login`.

### One-time Setup per Project

1. Run `firebase init`.
2. Proceed with the setup.
3. Select Hosting using the up and down arrow keys and use space bar to select.
4. Choose an existing project.
5. Select the project carefully.
6. Select   Question What do you want to use as your public directory? Ans:(public) Create Project By `Vite` Ans Is `dist` Create Project By React App Ans Is `build`  
6. Set the public directory to `dist`.
7. Select Yes for Single Page Application.
8. Choose No for Continuous Deployment.

### Deploying the Project

1. Build the project by running `npm run build`.
2. Deploy the project by running `firebase deploy`.
