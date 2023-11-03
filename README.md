# E-Commerce Back End [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
## Description
  
Every online retailer needs a back end to store their data. This app is a mock-up of how these sites structure their data storage, using a relational database (MySQL in this case). An easy-to-use API is constructed as well that performs useful CRUD operations (Create, Read, Update, and Delete).
  
## Table of Contents
  
-[Installation](#installation)
  
-[Usage](#usage)
  
-[License](#license)
  
-[Credits](#credits)
  
-[Contributions](#how-to-contribute)
  
## Installation
  
You must have node installed on your machine for this program to run. To check if you have node already installed, run the following code in your terminal:

`node --version`

If you see something like (but perhaps different numbers for another version)

`v18.18.2`

you're all set! If not, enter the following:

`npm init -y`

followed by 

`npm i`

Next, you will need to make sure you can connect to your database. In a .env file, save your user credentials so they can be properly passed to MySQL for login. In addition, you will want to make sure that the database name is correct; this line can be found in the server.js file at the root of the repository.

Once you've done all of that, you are good to go!
  
## Usage
  
Use the command line to navigate to the directory where the program is located. Then, type the following command in your terminal:

`npm start`

Our application also includes a folder that can seed your DB with some initial data. To run the seeder, type in the command line:

`node seeds/index.js`

For a look at the application running and some queries returning, please see the following video:

[Video](https://watch.screencastify.com/v/VqhLbCNfafnpHRdvH05u)

## Technologies used in development

1. Node.js
2. Express.js
3. Sequelize
4. DBeaver (DB management)
5. Insomnia (API testing)


## License

[This project uses the following license: MIT](https://opensource.org/licenses/MIT)

## How to Contribute
  
Please contact me on github or through my email listed below if you have any ideas or want to help extend my project!

## Questions

[Please follow this link to my GitHub profile!](https://github.com/kurtriecken)

For any additional questions, please [email me here.](mailto:kurt.riecken@gmail.com)

## Credits
  
[Kurt Riecken](https://github.com/kurtriecken)