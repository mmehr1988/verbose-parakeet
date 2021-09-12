# verbose-parakeet

## Project Title: E-Commerce Back End

<a href="https://choosealicense.com/licenses/mit" target="_blank"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" /></a>

## Table of Contents:

1. [Description](#description)
1. [Technologies](#technologies)
1. [Installation](#installation)
1. [Usage](#usage)
1. [Video](#video)
1. [Contributing](#contributing)
1. [License](#license)
1. [Questions](#questions)

## Description

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. Due to their prevalence, we've been tasked to to build the back end for an e-commerce site by modifying starter code.

Our main objective is to use [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect a working Express.js API to a MySQL database through the use of [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

## Technologies

1. [Node.js](https://www.npmjs.com/package/inquirer)

   a. [MySQL2](https://www.npmjs.com/package/mysql2)

   b. [Sequelize](https://www.npmjs.com/package/sequelize)

   c. [Express](https://www.npmjs.com/package/express)

   d. [Dotenv](https://www.npmjs.com/package/dotenv)

   e. [Insomnia](https://insomnia.rest/)

## Installation

- Before cloning the repository, please ensure you have node.js installed since we will have to install node.js packages. If you do not have node.js installed, start with steps 1 and 2. If you have node.js installed and confirmed, you can skip steps 1 and 2 and begin on step 3.

  1.  [Node.js Download Page](https://nodejs.org/en/download/)

  2.  After install, check with command line to ensure setup is correct.

      a. Open your terminal

      b. Type the below command. If you see a version it means you have installed node.js correctly.

      ```bash
      node -v
      ```

  3.  Clone repository and open in VS Code.

  4.  Open Terminal in VS Code

      a. Shortcut = CTRL + `

  5.  Install all the dependencies by typing the below command.

      ```bash
      npm install
      ```

  6.  Once you hit enter, the correct dependencies for allowing you to use this application will be automatically installed.

  7.  The final step is to update the .env.EXAMPLE file with your MySQL password and user info. Please ensure you also remove the ".EXAMPLE" from the file path.

  ## Usage

  - Once you've completed the installation section guidelines, you'll need to first create the database in MySQL before running the application. Follow the below steps and use the image at the end of this section for guidance.

  1.  Open Terminal in VS Code

      a. Shortcut = CTRL + `

  2.  Navigate to the folder called 'db'.

  3.  Log into your MySQL and type the below command.

      ```bash
      source schema.sql
      ```

  4.  When you've received confirmation that the database has been created, exit MySQL so that you can run the application. Type the below command to exit MySQL.

      ```bash
      quit
      ```

  5.  Now that the database has been created, we want to seed the database using the data stored in the seeds folder. To do this, you'll need to navigate back to the main folder and type the below command.

      ```bash
      npm run seeds
      ```

  6.  To run the application, type the below command.

      ```bash
      node server.js
      ```

## Video

[Link To GIF ](https://github.com/mmehr1988/verbose-parakeet/blob/main/gif/ecommerce-backend.gif)

![alt text](./gif/ecommerce-backend.gif)

## Contributing

Please open a Github issues request and I’ll review and respond as soon as I can. See below image for where to find the Issue page.

![alt text](./img/contribute-img.png)

## License

<a href="https://choosealicense.com/licenses/mit" target="_blank">MIT License</a>

## Questions

Github Portfolio Link: [Mehdi Mehrabani](https://github.com/mmehr1988)<br>
Email Contact: tatash.my@gmail.com
