Week 7 unit 13

# E-Commerce[![License: GPL v2](https://img.shields.io/badge/License-GPL_v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
## Table of Contents
- [E-Commerce![License: GPL v2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)](#e-commerce)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [License](#license)
  - [Questions](#questions)
  - [Summary](#summary)

## Description
A database for dynamically storing product information into different categories and their associated tags.

## Screenshots
![image](https://user-images.githubusercontent.com/98775943/166871783-97c0ceb3-15ff-4afc-9791-d94ffbc59acd.png)
![image](https://user-images.githubusercontent.com/98775943/166871953-50dde53b-012d-4ebc-a72d-75c48d05fab9.png)



## Installation
In order to get this database to worka user must install the following packages: sequelize, express,and  mysql2. They must also ensure that under "scripts" in the package.json file there is one called "seed":node seeds/index.js in order to add the seeds. Also the .env folder will need to be updated with the users sql username and password in order for it to connect properly. Then, the first thing the user will need to do is open up mysql by loggin in and then running the schema.sql file inside of the db folder. Then they will exit sql and do the "npm run seed" which will add all of the seeds by adding them into dynamically produced tables into the open database. After this, the testing and adding of new information can take place in Insomnia, as shown in the demo video. 

## Usage
This project is intented to bring the user a modern way to keep track of all of their merchandise in a database. Where every product is within a category and has a product tags. Products are described with their name, price, amount of stock and their category ids. They are also given a product tag for even further unique identification. 

## Contributing 


## Tests
None

## License

This README is covered under license GPLv2

## Questions
* For any questions please contact me at this email address:dahlialolagraves@gmail.com

* [GitHub Portfolio](https://github.com/DahliaGRV)

* [Repository Link](https://github.com/DahliaGRV/E-commerce-Back-End-ORM-)
* [Deployed Link]Deployed link: (https://drive.google.com/file/d/1WcleMbu8lRm-PsgZ26TN0xa6oAL-MS2-/view) Heroku app link(to be ran in insomnia for alternative testing): (https://vast-temple-86360.herokuapp.com/)

## Summary
At first I had a hard time visualizing the joins. It was hard for me to see the connection between the products and tags through the producttags. Eventually I was able to see that the product tags were essentially acting as data holding middleware. This was challenging but also very interesting and honestly a lot of fun.  
  
