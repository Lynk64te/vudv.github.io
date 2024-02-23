Things to Download before you proceed
I used the MERN (MongoDB, ExpressJS, ReactJS and NodeJS) stack for this project.

MERN

NodeJS
MongoDB
The package.json files in the root, frontend and the backend folders contain all the required dependencies. First go ahead and make sure to download the latest stable version of NodeJS and also the latest version of MongoDB. Clone the repository and run the command npm install while in the root, frontend and backend folders to install all the dependencies. All the required steps to set up the project are mentioned below. Just follow through.

Configuration Steps
Installing the dependencies (using terminal):
$ cd MovieGo
$ npm install

$ cd backend
$ npm install

$ cd..

$ cd fronted
$ npm install
This installs all the required dependencies like React, React-router-dom, Concurrently, Express, Mongoose, Passport, etc.

dotenv file:
Create a .env file in the backend folder, and write the following code
MONGODB_PASSWORD=Password
SECRET=Anythingyouwant

and save it. The SECRET variable can literally have any value.

Configuring MongoDB:
Open your terminal, and go to the directory where you have MongoDB installed and from thereon cd to the directory which has the 'mongod.exe' file inside it. After you reach that directory through your terminal, type mongod and press enter, and the MongoDB server starts running locally on your machine on port 5000.

Checking if everything works fine:
Now open another terminal and cd to the MovieGo directory. Run the following code:

$ npm start

and you shall see that the website is loaded on your localhost port 3000.
