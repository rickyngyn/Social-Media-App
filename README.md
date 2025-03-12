# SociMedia

A simple social media app.

## Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/rickyngyn/Social-Media-App.git
   cd your-repo

2. Install dependencies
   ```bash
   npm install

3. Install packages (for server)
   ```bash
   npm i -g nodemon
   npm i express body-parser bcrypt cors dotenv gridfs-stream multer multer-gridfs-storage helmet morgan jsonwebtoken mongoose
   npm init -y

4. Install packages (for client)
   ```bash
   npx create-react-app client
   npm i react-redux @reduxjs/toolkit redux-persist react-dropzone dotenv formik yup react-router-dom@6 @mui/material @emotion/react @emotion/styled @mui/icons0material

5. Run Server
   ```bash
   nodemon index.js

6. Run Client
   ```bash
   npm run start

## Note
Environmental Variables include:
   - Mongoose DB API Key
   - PORT
   - JWT_SECRET
