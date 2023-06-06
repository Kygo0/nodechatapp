To run the application, XAMPP control panel was used . After you have downloaded xampp control panel place the folder with the files inside the htdocs folder, then launch XAMPP and start Apache,MySQL and FileZilla

NodeJS must be installed

The dependencies are:

{
  
  "dependencies":
    "mysql": "^2.18.1",
    "node": "^20.0.0",
    "qs": "^6.11.1",
    "socket.io": "^4.6.1",
    "websockets": "^0.2.0",
    "ws": "^8.13.0"
  }
}

The MYSQL database structure should be

Database name = chat
Table = users
Columns = ID, username, password

Finally to run the program enter "node server.js" to start the app and go to the following link

localhost/`the name of the folder that includes all the files`/register.php
OR
localhost/`the name of the folder that includes all the files`/login.php
