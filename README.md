# E-commerce-Back-End

## Table of Contents
* [Challenge Goal](#challenge-goal)
* [Challenge Requirements](#challenge-requirements)
* [Challenge Result](#challenge-result)
---

## Challenge Goal
Create an application that asks the user questions to create a README.md file automatically.


## Challenge Requirements

### User Story
>AS A manager at an internet retail company <br>
I WANT a back end for my e-commerce website that uses the latest technologies <br>
SO THAT my company can compete with other e-commerce companies <br>

### Acceptance Criteria
>GIVEN a functional Express.js API <br>
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file <br>
*THEN* I am able to connect to a database using Sequelize <br>
WHEN I enter schema and seed commands <br>
*THEN* a development database is created and is seeded with test data <br>
WHEN I enter the command to invoke the application <br>
*THEN* my server is started and the Sequelize models are synced to the MySQL database <br>
WHEN I open API GET routes in Insomnia Core for categories, products, or tags <br>
*THEN* the data for each of these routes is displayed in a formatted JSON <br>
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core <br>
*THEN* I am able to successfully create, update, and delete data in my database <br>


## Challenge Result

### Application Video Walkthrough
[Application Walkthrough]()

### GitHub Repository
[GitHub Repository URL]()

---

*Tip: install these packages to be able to use this application:* <br>

**NPM** <br>
`npm init` <br>

**MySQL** <br>
`npm i --save mysql2` <br>

**Sequelize** <br>
`npm i sequelize` <br>

**Using dotenv** <br>
`npm i dotenv --save` <br>

**Express** <br>
`npm i express` <br>

**Want to install all at once?** <br>
`npm init` first then enter the next code:
`npm i mysql2 sequelize express dotenv`

### Using the program
Make sure to follow the instructions below to use the database:
1. Install NPM first: `npm i`
2. Start MySQL: `mysql -u root -p` and enter your MySQL password
3. Create database tables: `source db/schema.sql`
4. Quit MySQL: `quit`
5. Seed tables with data: `npm run seed`
6. Start the program: `npm start`