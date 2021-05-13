# E-Commerce Back End
  
  ## Description: 
  This project is the back end of an e-commerce site. This application allows users to add, update and delete products, categories, tags, and data within each section.
  [Walkthrough Video of the Application]
  ## Table of Contents
  * [Tools Used](#tools%20used) 
  * [Installation](#installation)
  * [Usage](#usage)
  * [Questions](#questions)
  ## Tools Used
  * Node.js
  * Express.js
  * MySQL2
  * Sequelize 
  * Dotenv
  

  ## Installation
  Run the following code in the command line to run dependencies:
      
      npm init --y
      npm install
      npm install express sequelize mysql2
      npm install dotenv

  Initiate SQL:

      mysql -u root -p
  From MySQL shell input:

      source db/schema.sql
      use ecommerce_db
      quit

  From the terminal type:

      npm run seed

  To start the application:

      node server.js

  ## Usage:
  ![Gif Demo](./video/Gif.gif)
  This application stores data using POST, updates using PUT, deletes using DELETE, and recalls the information with GET. 
  

  ## Questions:
  If you have any questions, please feel free to contact me at chrispruiz@att.net. For more of my work, visit [Chrispruiz](https://github.com/Chrispruiz).
