Initial Steps
This is a boilerplate

- Make sure node is installed on the machine where it is executing
	Windows: 		https://nodejs.org/en/ (Download and execute)
	Linux(Centos): 	sudo yum install nodejs npm

- Create a boilerplate folder and files for the application (/public/index.html)

- Make sure to ignore node_modules folder
	- Create .gitignore file(content): node_modules

- Create package.json file with node command=> npm init

- Create a server for the application
	- install expressjs dependency globally=> npm install -g express
	- install expressjs dependency (within package.json)=> npm install express --save
	- create file to execute the server: server.js (to load a server)
	- Execute command=> node server.js
	- Cehck in the browser: localhost:3000 (you must see inde.html content)

- Installing bootstrap =>npm install --save bootstrap

- Installing angular =>npm install --save angular

- Installing angular-ui-router => npm install --save angular-ui-router

- Installing angular-resource => npm install --save angular-resource

- Installing webpack => npm install webpack --save-dev
	
- Upload changes to Repo