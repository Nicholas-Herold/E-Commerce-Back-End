# E-Commerce-Back-End

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Table Of Content

- [General Info](#general-info)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)

## General Info

Video Link https://youtu.be/i82b4zoJ6eQ

## Technologies

Project is created with

- [Javascript](https://www.javascript.com/)
- [Node.js](https://nodejs.org/en/)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Express](https://www.npmjs.com/package/express)
- [Dotenv](https://www.npmjs.com/package/dotenv)

## Installation

To get started clone this repository using
<br>

```terminal
git clone git@github.com:Nicholas-Herold/E-Commerce-Back-End.git
```

Install dependencies

This will install nessary packages from package.json

```terminal
npm i
```

update .env

```create file
create and update .env file will my sql permissions.
```

Create DB

```terminal
Run mysql -u xx -p  in terminal
Run source db/schema.sql
Run exit
```

Seed the database

```terminal
node seeds/index.js
```

to start running application simply input

```terminal
node server.js
```

Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## Usage

This application will be used as a backend to Add Change Delete and Get data from sql database. A Frontend could be added to display and input data.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br>
This repository is licensed under the MIT license.
