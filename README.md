# E-Commerce-Backend


E-Commerce-Backend
The challenge is to build the back end for an e-commerce site.


We’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database. This application won’t be deployed so i’ll show a walkthrough video that demonstrates its functionality.
Image showcasing the application running in Insomnia. 

Demonstration Video demogif.gif

Technologies
Javascript
Node.js
Sequelize
MySQL2

To get started clone this repository using

Install dependencies

npm init --y
npm install express sequelize mysql2
Open up MySQL shell and input

source db/schema.sql
and

use ecommerce_db
Then quit MySQL shell and input the following in your terminal

npm run seed
to start running application simply input

node server.js
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.


License
License: MIT
This repository is licensed under the MIT license.

