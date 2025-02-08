### Music Player Application

It is a small music player web app using the MERN stack (MongoDB, Express, React, Node.js). The app should allow users to sign up, sign in, select songs from a library, create playlists, play songs, and resume songs from where they left off.

**Live Website** - **https://soft-eclair-a82237.netlify.app/**

**Here's a breakdown of the technologies used, functionality, and how to set it up locally:**

### Technologies Used:

1. **Frontend**:

   - **React.js**: For building the user interface.
   - **Redux**: For state management, especially for managing the state of the music player and user authentication.
   - **Tailwind-CSS**: For styling the components and creating a responsive design.
   - **Axios**: For making HTTP requests to the backend.

2. **Backend**:

   - **Node.js**: As the runtime environment for the server-side code.
   - **Express.js**: For building the RESTful API that interacts with the frontend.
   - **MongoDB**: As the database for storing user data, playlists, and music information.
   - **Mongoose**: For object data modeling (ODM) to work with MongoDB.

3. **Authentication**:

   - **JWT (JSON Web Tokens)**: For user authentication, allowing secure login and session management.

4. **Deployment**:
   - **For deployment I used netlify free cloud hosting website.**

### Functionality:

- **User Authentication**: Users can sign up and log in using JWT-based authentication.
- **Music Library**: Users can browse and search for music tracks and albums using the API.
- **Playlist Management**: Users can create, view, and manage their playlists.
- **Music Player**: Users can play music, with features like play, pause, skip, and volume control.
- **Responsive Design**: The app is designed to be responsive, working well on both desktop and mobile devices.

## Here's a step-by-step guide to using the Music App once the live server is opened:

### Step 1: Open the Live Server

- Navigate to the URL where the app is hosted.

### Step 2: Sign Up or Log In

- **Sign Up:** If you are a new user, click on the "Sign Up" button and fill in the required details to create an account.
- **Log In:** If you already have an account, click on the "Log In" button and enter your credentials.

**Log In Sample Account**

- Email : kr@gmail.com
- Password : kr1234

### Step 3: Redirect to Home Page

- After successfully signing up or logging in, you will be redirected to the home page.

### Step 4: Navigate the Home Page

- On the home page, you will see two main buttons: **Upload** and **Stream**.

### Step 5: Upload Songs

- Click on the **Upload** button.
- A file selection dialog will appear. You can upload any number of songs from your device.
- After uploading, the songs will be added to your library.

### Step 6: Stream Songs

- Click on the **Stream** button.
- You will be able to see the list of songs available in your library.
- You can play any song by clicking on it.

### Step 7: Add to Playlist

- While streaming a song, you have the option to add it to a playlist.
- Create a new playlist or add the song to an existing playlist.

### Step 8: Log Out

- After you are done, you can log out by clicking on the **Log Out** button, which will be available on the navigation bar or in a dropdown menu.

**These instructions should guide you through the basic functionalities of the Music App.**
