# Welcome to my react-node-template!
Why waste time starting a whole new project by setting everything up. Again. 

Git clone * slaps hood of project * this bad boy and save time today :)

Note: There will be an error stating: Store does not have valid reducer. Just update store.js in the Redux directory.

## Setting up locally?
- `git clone https://github.com/Philip-Mann/react-node-template.git`
- in root of folder, run `npm install`
- change directories into react-ui `cd react-ui`
- run `npm install`
- change directories back to root of project`cd ..`
- then create your .env file `touch .env`
- add your port number to .env file
- run `npm run build` in root of project
- after build has completed run `npm run dev`
- open second terminal and change directories into react-ui
- run `npm start`

## Dependencies used on server
- dotenv
- express 
- express-session
- pg
- sequelize
### Developer Dependencies on server
- nodemon
- sequelize-cli

## Dependencies in react-ui
- @redusjs/toolkit
- react-router-dom
- react-redux