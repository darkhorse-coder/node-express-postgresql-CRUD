 # Node Js Project Structure
 
 Recently I have started working on a new project and the issue that I faced was spending a lot of time building the project structure based on the best practices, especially with javascript that has a lot of approaches and bad parts, I couldn't find any place that wraps the best practices into a single project ,so I decided to make it on my own.
 
in this repository, I don't aim to provide an optimal solution as each project have its own necessity but to help anyone that is starting with a node js project and can't find any inspiration on how to start building the project to take this project as the starting point.
 
 some of the good practices followed in this repository:
 - Async/Await support 
 - WinstonJs Logger Implementation
 - Error Handling
 - Sequelize Support 
 - Basic Joi Validation
 - Open Api Specification implemented through swagger-jsdocs and swagger-ui
 - Jwt implementation 
 - Enviroment variables to hold configuration values .env file
 - OOP (object oriented programming)
 - i've followed [airbnb](https://github.com/airbnb/javascript) Coding standard with a eslint ,help to keep thing into prespective.
 
 # How to start the project 
 
 first you clone the project using the following command :
 ```bash
 git clone https://github.com/darkhorse-coder/node-express-postgresql-CRUD.git
 ```
 install node version 8.11.0 or use nvm to downgrade your node version 
 
 delete the existing package.lock.json and run `npm install`
 
 then you create a postgres database Named `iLrn` with the following credintials 
 
 username : `postgres` 
 
 password : `password`
 
 run the migration using the following command :
 ```bash
 npx sequelize-cli db:migrate
 ```
 Finally you run 
 ```bash
 npm start 
 ```

Future improvements utilize compenent based structe

please feel free to :star:  happy programming :v: 
