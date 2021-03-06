# E-Commerce-Back-End

## Description

An E-Commerce Back End Platform, using Node, Express, Sequelize, with a MySQL database.

**Tools & Skills Used**<br>
Node.js, Express, Sequelize, and MySQL.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

Here are some guidelines to help you get started:

- Git Clone the Repo:

```
git clone git@github.com:carlincb/E-Commerce-Back-End.git
```

- Create a `.gitignore` file and include `node_modules/`, `.DS_Store`, and `.env`, so that these directories are not tracked or uploaded to GitHub. Be sure to create your `.gitignore` file before installing any npm dependencies.

- Create your own .env file. Using the following format:

```
DB_NAME=ecommerce_db
DB_USER=yourusername
DB_PW=yourpassword
```

- Your application should use [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data. These are included as dependencies and should be installed by running the following command in the current working directory for this application:

```
npm install
```

- Open your terminal from the root of the file and enter:

```
mysql -u username -p
```

- Enter password for MySql if applicable.

- Source the schema by entering this command in the terminal from the root folder:

```
SOURCE db/schema.sql
```

- Exit MySql by typing `exit`.

- You can then seed data to your database with this command:

```
npm run seed
```

- The application will be invoked by using the following command:

```bash
node server.js
```

- Finally, the GET, POST, PUT, and DELETE routes can all be tested in [Insomnia Core](https://insomnia.rest/products/insomnia) or similar program.

## Usage

Please see below for examples of this application's usage.

### Video of Usage:

- https://watch.screencastify.com/v/fkvrQnYIkvcA0HVFqnXK

## Credits

- https://www.npmjs.com/package/mysql2
- https://www.youtube.com/watch?v=qsDvJrGMSUY&ab_channel=AlexBooker
- https://www.youtube.com/watch?v=6NKNfXtKk0c&ab_channel=AlexBooker
- https://www.youtube.com/watch?v=pxo7L5nd1gA
- https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)<br/>

    MIT License

    Copyright (c) 2021 COLLEEN FIMISTER

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

## Contributing

No contributions needed at this time, but please feel free to contact me at my email address below if you would like to contact me about this project.

## Questions

If you have questions, please contact me at carlin.colleen@gmail.com or find me at https://github.com/carlincb.
