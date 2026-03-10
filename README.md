# Assignment 3: Express and MongoDB CRUD Application

## Overview
This assignment is for you to modify your Express app from Assignment 2 to add storage using MongoDB and Mongoose, and to implement full CRUD (Create, Read, Update, Delete) functionality. You will also deploy this updated version of your app to the web. 

## Core Requirements
The core requirements for this assignment can be found in the Canvas assignment description. Please refer to that for the specific tasks you need to complete.

### Version control & documentation
- Start with the github repo provided in Github Classroom.
- Copy your Express application from Assignment 2 into this new repo to use as a starting point for your work on this assignment. Be sure not to copy the .git directory from your Assignment 2 repo, as that will cause problems with the git history in this new repo. You can just copy the files and directories that make up your Express app (e.g., `app.js`, `views/`, `public/`, etc.) into this new repo.
- Commit your code regularly with meaningful messages.
- Include a short `README.md`(edit this one) describing:
  - What the app does
  - How to run it locally (`node server.js` or `npm start`)
  - Your deployment link

### Deploy your app
- Deploy to Render (recommended) or Digital Ocean.
  - Refer to FTI's post in [Ed Discussion](https://edstem.org/us/courses/94002/discussion/7751223) for information on how to configure access to your github repo from Render. **It's no longer necessary to make a copy of your repo and manually add the teaching staff as collaborators to it.** 
- Dont forget to configure your environment variables in Render, and to whitelist your Render app's IP address in your MongoDB Atlas cluster settings to allow connections from your deployed app. .
- Verify that visiting your public URL displays the dynamic info.