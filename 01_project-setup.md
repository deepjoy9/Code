# Project Setup

## Setting Up a React Project Using Vite

1. **Install Vite**:

   ```sh
   npm create vite@latest
   ```

2. **Choose React**:
   When prompted, select `React`.

3. **Navigate to the Project Directory**:

   ```sh
   cd your-project-name
   ```

4. **Install Dependencies**:

   ```sh
   npm install
   ```

5. **Start the Development Server**:
   ```sh
   npm run dev
   ```

## Setting Up a Backend with Node.js and Express.js

1. **Initialize a New Node.js Project**:

   ```sh
   npm init -y
   ```

2. **Install Express.js**:

   ```sh
   npm install express
   ```

3. **Create an `index.js` File**:

   ```javascript
   // index.js
   const express = require("express");
   const app = express();
   const port = 3000;

   app.get("/", (req, res) => {
     res.send("Hello World!");
   });

   app.listen(port, () => {
     console.log(`Server is running on http://localhost:${port}`);
   });
   ```

4. **Start the Server**:
   ```sh
   node index.js
   ```

## Setting Up a Next.js Project

1. **Create a New Next.js App**:

   ```sh
   npx create-next-app@latest
   ```

2. **Navigate to the Project Directory**:

   ```sh
   cd your-project-name
   ```

3. **Start the Development Server**:
   ```sh
   npm run dev
   ```


