# mern-demo-crud-app
MERN Demo CRUD Application 

This app was built with the help from the tutorial found at: 
https://codingthesmartway.com/the-mern-stack-tutorial-building-a-react-crud-application-from-start-to-finish-part-1/

This is a todo CRUD (Create, Read, Edit, Delete) application built using the MERN stack (Mongo DB, Express.js, React.js and Node.js).  All exisitng notes are displayed on the home page. From there you can either create a new todo, edit an existing todo, or delete an exiting todo. All todos are stored in a MongoDB database through Mongoose. There is also validation put in place to stop users from submitting or editing a todo without filling in all required fields. 

In order to run the project, clone this repository into an empty directory. You then have to install and start MongoDB for your operating system: https://docs.mongodb.com/manual/administration/install-community/ and create a new todos database:

1. mongo
2. use todos 

Once this is done, go into the mern-demo-crud-app-backend folder and run:

1. npm install 
2. npm install -g nodemon 
3. nodemon server.js 

The backend should now be running on port 4000 and MongoDB should be connected 

After the backend is running, go into the mern-demo-crud-app-frontend folder and run:

1. npm install 
2. npm start 

This should launch the React application frontend on: http://localhost:3000 

