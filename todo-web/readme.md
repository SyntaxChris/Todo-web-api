## Getting Started

Clone Repo

````
git clone https://github.com/SyntaxChris/Todo-Web-Api
````

npm install dependencies

````
cd todo-web

npm install
````

### Start development server with hot reloading

````
npm run dev
````

### Testing

Run test once

````
npm run test
````

Test watch

````
npm run test:watch
````

### Linting

Eslint with Airbnb Eslint configuration

````
npm run lint
````

### Production

Build for production

````
npm run build
````

Start production server

````
npm run start
````

Note: pm2 is used for production server, you should install it on server via 'npm install pm2 -g'.
if you don't want to use pm2, just change pm2 with node in package.json file in scripts section.


