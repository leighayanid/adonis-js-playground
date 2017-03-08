# adonis-js-test
Playing around with this Nodejs MVC framework

Day 1 of coding with AdonisJS - March 6, 2017
- Reading the official documentation to know more about the basics of the framework
- Installed the adonis-cli on my development machine
- Digging more to the documentation before to scaffold a project
- [Link to the docs](http://www.adonisjs.com/docs/3.2/overview)

Day 2 of coding with AdonisJS - March 8, 2017
- Scaffold a new project using adonis-cli
- Learned ace commands
- Encountered problems during installation/running web server
  - Creating project using adonis-cli throws an error when using yarn and won't install dependencies. Found out the cli has bug and already reported on its github page. The problem was solved by changing to directory to project directory and running yarn command to successfully install dependencies. 
  - Running the dev server will throw an error due to the .env.example file. This will be solved by changing the .env.example file to .env
  - Running ./ace command inside windows command prompt won't work, git bash will do
- Creating a project by running this command
  - adonis new [project name]
- Running the server
  - npm run server:dev

