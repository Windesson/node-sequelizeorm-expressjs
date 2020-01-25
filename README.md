# node-sequelizeorm-expressjs

Install and Use Sequelize CLI
Overview
Many development tools have what's called a CLI, or command-line interface, which is a special piece of software that's used to aid in the development process. Sequelize is no different, it has a useful command-line interface for initializing and bootstrapping your database project, creating models, database configuration files and more. The CLI operates with many relational databases like PostgreSQL, MySQL, MSSQL, and Sqlite.

In this workshop, we'll once again use SQLite for our database. SQLite is easy-to-use and doesn't require you to install or configure anything on your system to use it, making it an ideal database for learning projects. Both Sequelize and SQLite are already installed as project dependencies.

Install Sequelize CLI and Initialize a Database Project
In your Terminal (or console app), run the command:

$ npm install sequelize-cli@^5.5.1
Most CLIs have a help command to provide more information about its set of commands and help you find which command to use if you're stuck. You can run the sequelize CLI with:

$ npx sequelize --help
This brings up all the commands you're able to run using the CLI. Start by using the init command to initialize the database project.

Make sure that you're in the project’s base root directory, and run the command:

$ npx sequelize init
If you're not familiar with the npx command, it's an npm utility that makes it easier to interact with CLIs and run packages, as well as install and manage npm dependencies. You can read more about npx in the "Resources" section of this instruction step.
Running npx sequelize init initializes all the configuration code, folders and helpers needed for the application. It sets up four directories: config, migrations, models, and seeders.

Note: The seeders folder usually contains "seed files", which hold data you can use to populate your database tables with sample or test data. You will not create or use seed files in this workshop, so feel free to delete the seeders folder.
