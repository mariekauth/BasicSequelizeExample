# BasicSequelizeExample
Setup and Use Sequelize with Stored Procedure - Node 14, Sequelize 6, MS-SQL, Tedious, Stored Procedure

To demonstrate using NodeJS with Sequelize and Tedious to read from an MS-SQL database that uses a stored procedure that takes a User Defined Table Type as a Parameter we are going to walk through the setup.

Requirements: 
- npm must be installed
- node version must be ~14
- sequelize must be ^6.19.2 (Remove sql injection vulnerability)
- must have connection to ms-sql database
- must have table in database with at least one field as an integer, and one field as a string
- database must have user defined table type that with one integer field that will allow us to parameterize our query
- database must have one stored procedure that takes the user defined table type as an arguement
- node project will use .js and not .ts files for this example

Assumptions
- npm, node, and database are already installed (with correct versions)
- You already know how to write code in the above languages

Get Started
- To setup the database, we will use an example from: https://transition.fcc.gov/oet/info/maps/census/fips/fips.txt

This file will be updated when the examples and instructions are ready.
