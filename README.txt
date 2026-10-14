STUDENT RECORDS API — SETUP

1. Make sure Node.js and MongoDB are installed and MongoDB is running
   (open a separate Command Prompt and run: mongod  — leave it open).

2. Open this folder (StudentRecordsAPI) in VS Code.

3. Open a terminal in VS Code (Terminal -> New Terminal) and run:

     npm install

   This installs express, mongoose, and nodemon using the versions
   listed in package.json.

4. Start the server:

     npm run dev

   You should see:
     MongoDB connected
     Server running on http://localhost:3000

5. Open index.html (the frontend) in Chrome — it will talk to
   http://localhost:3000 automatically.

Keep the "npm run dev" terminal and the "mongod" window open the
whole time you're using the app.
