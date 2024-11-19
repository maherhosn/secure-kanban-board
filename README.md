# Secure Kanban Board

## Description:
The Kanban Board Application allows a userr to login useing a pre-existing- user account. After which new tickets can be created in the "ToDo" "In-Progress" and "Done" cards.<br>The user can also track the progresss of the tickets as well as edit and delete them.<br>The login parameters are generated with a JWT secure token in order to hide the password that was saved in the database.<br>The JWT token is also saved to local storage to allow the user to browse for 1 hour after login.

## Table Of Contents:
- [Installation Guide](#installation-guide)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation Guide:
Make sure that you have node/npm, as well as postgres SQL server running.<br>1- Clone this repository to your server. using gitbash.<br>2-Go to the main directory and run an<br> "npm install" <br>"npm run build"<br>"cd server, && npm run build"<br>"npm run seed"<br>"npm run start:dev"... <br> Or you can use the following link active on Render:

## Usage: 
The following snapshots show how the running app looks like:<br> 1) How the seeded user login credentials look in the database.<br> 2) Login-Page.<br> 3) Main Kanban Board.<br> 4) Wrong Username Or Password pop-up alert.<br> 5) Authentication key after login.<br> 6) Authentication key after logout.<br> 7) "auth-routes.ts" showing that the key is valid for only 1 hour.

## Licence: <br>
### MIT <br>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) <br>
https://opensource.org/licenses/MIT


## Contributing:
No Contributions can be made to this code!

## Tests:
Perform the steps shown in the snapshot above to test the application, if you are looking for username and password that pre-exist, you can find it under:<br> "server --> src --> seeds --> user-seeds.ts"

## Questions:
If you have any question please contact: <br>
name: maherhosn <br>
email: maherhosn@hotmail.com
  