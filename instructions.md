# Prompt:

Run a simple server with Node and Express

## Optional: 

Configure your project so that your server automatically updates upon changes

### solution

install nodemon
`npm i nodemon --save-dev`

Add the following script to your "scripts" object in your package.json file.

`"dev": "nodemon src/server.js"`

run the following command on your command line.
`npm run dev`