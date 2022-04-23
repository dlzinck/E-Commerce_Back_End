# E-Commerce_Back_End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Description

The goal of this project was to modify starter code to create the back end for an e-commerce site by modifying starter code. i WILL configure a working Express.js API to use Sequelize to interact with a MySQL database.

When I add my database name, MySQL username, and MySQL password to an environment variable file I am able to connect to a database using Sequelize. When I enter schema and seed commands a development database is created and is seeded with test data. When I enter the command to invoke the application my server is started and the Sequelize models are synced to the MySQL database. When I open API GET routes in Insomnia for categories, products, or tags the data for each of these routes is displayed in a formatted JSON. When I test API POST, PUT, and DELETE routes in Insomnia I am able to successfully create, update, and delete data in my database.


## Table of Contents

- [Technology Used](#technology-used)
- [Links](#links)
- [Screenshots](#screenshots)
- [Usage](#usage)
- [Questions](#questions)
- [License](#license)


## Technology Used

- [Visual Studio Code](https://code.visualstudio.com/)
- [Node.js](https://nodejs.org/en/)
- [Insomnia](https://docs.insomnia.rest/)
- [Express](https://www.npmjs.com/package/express)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [Node MySQL 2](https://www.npmjs.com/package/mysql2)
- [Sequelize](https://sequelize.org/)
- [Nodemon](https://www.npmjs.com/package/nodemon)
- [GitHub](https://www.github.com)


## Links

- [GitHub Repository](https://github.com/dlzinck/E-Commerce_Back_End)

- [Return all & by ID](https://watch.screencastify.com/v/gkrblskgW4SOZwNNnklM)
- [CREATE UPDATE DELETE Categories](https://watch.screencastify.com/v/efzfpKGEDnmnHrViCWhE)
- [CREATE UPDATE DELETE Products](https://watch.screencastify.com/v/FIwEzZRds6SmNAdPRpOE)
- [CREATE UPDATE DELETE Tags](https://watch.screencastify.com/v/9sT8MaiIYmZ6SsXyoSbr)


## Screenshots


## Usage

`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`

Run the following command at the root of your project and answer the Prompted questions:

`mysql -u root -p`

Enter PW when prompted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`


## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit).

Copyright (c) 2021 Drew Lane Zinck II

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.