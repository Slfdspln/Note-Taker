# <h1 align="center">Note Taker (powered by Express.js) </h1>
Week-11 Challenge

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

*  [Description](#Description)
          <a name="Screenshots"></a>
          
*  [Live-URL-of-Deployed-Application](#Live-URL-of-Deployed-Application)
          <a name="Live-URL-of-Deployed-Application"></a>

*  [Screenshots](#Screenshots)
          <a name="Screenshots"></a>
   
*  [Technologies-Used](#Technologies-Used)
          <a name="Technologies Used"></a> 
          
*  [Installation](#Installation)
          <a name="Installation"></a> 
    
*  [Usage-Information](#Usage-Information)
          <a name="Usage Information"></a>  
          
*  [License](#License)
          <a name="License"></a> 
         
*  [Questions](#Questions)
          <a name="Questions"></a> 
          

##  Description 
This application was developed to provide users with a platform for organizing their thoughts and managing tasks through note storage. It utilizes Express and JavaScript, employing a json file (db.json) as a pseudo-database for data storage and retrieval. My responsibilities involved integrating the backend and frontend of the application using Express, enabling users to save, retrieve, post, and delete data through the frontend UI. To test the application's GET, POST, and DELETE routes, I utilized Insomnia, a valuable tool for backend development that eliminates the need for an index.html file and linked script.js file. While building the application, I gained insight into the capabilities of Express and its potential for large-scale database interactions with APIs. I encountered some errors related to race conditions and concurrency issues, which would be addressed in future development. This includes organizing the server.js file by creating a routes folder for improved file organization and considering the use of a proper database like MySQL for data management.

## Live-URL-of-Deployed-Application 

https://notes-ucberkeley.herokuapp.com/
 
##  Live Screen Recording of Application Functionality 

https://drive.google.com/file/d/16mjh5Pk8DIZsmYwZ340xfOBqjaGSaVU9/view

## Screenshots 

<img width="1470" alt="Screenshot 2023-05-16 at 6 25 01 PM" src="https://github.com/Slfdspln/note-taker/assets/121422214/b6234aae-c5aa-4718-8ceb-f0f5eb6c164c">

<img width="1214" alt="Screenshot 2023-05-16 at 6 25 25 PM" src="https://github.com/Slfdspln/note-taker/assets/121422214/a306734b-1871-46a4-93dc-76753e3b1df0">

<img width="1470" alt="Screenshot 2023-05-16 at 6 25 55 PM" src="https://github.com/Slfdspln/note-taker/assets/121422214/16cb5048-12ed-40f8-83bc-f0958e3a6227">

<img width="1470" alt="Screenshot 2023-05-16 at 6 26 09 PM" src="https://github.com/Slfdspln/note-taker/assets/121422214/3d7f2369-d526-427b-bc68-6f6a30f453e6">




## Technologies Used

This project is powered by Express.js and Node.js (v16.19.1), utilizing JavaScript as the programming language. It incorporates uniqid and file system modules as dependencies. To facilitate testing of GET, POST, and DELETE request routes, the application leverages Insomnia, eliminating the need for a dedicated front-end framework.

## Installation

1. Clone the repo: git clone git@github.com:Slfdspln/logo-maker.git

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

4. Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install express and uniqid directly from the command line, to do so the command for express will be npm i express to install the latests version of Express framework globally so that it can be used within the node terminal, and npm i uniqid to install the latest version of uniqid).

6. To run the server, within the terminal, type the command npm start or node server.js.

7. Once the server is running, users can then access the front end of the application within the browser to observe full functionality of the site.

## Usage Information

This application requires a server running in the background, which is powered by Express. To start the server, follow these steps:

1. Navigate to the application's directory.

2. Install all dependencies by running the command "npm i".

3. Start the server by typing "npm start" or "node index.js".

4. The command line will display a message: "App listening at http://localhost:3001 🚀".

5. Once the server is running, access the application's front end directly from the command line by holding the command key and clicking on the link http://localhost:3001.

6. Users can then view existing notes from the database or create new notes.

7. Any newly created notes will be saved to the database and persisted.


## License

NOTICE: This application is covered under the MIT License

## Questions

Need more information? You can contact me through my LinkedIn or Email. Links provided below.

Click for LinkedIn -> [LinkedIn](mailto:inaliaashanti@gmail.com?subject=[Email]%20Source%20Han%20Sans)

Click to Email -> [Email](https://www.google.com)

