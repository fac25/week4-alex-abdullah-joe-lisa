# [Petsagram](https://petstagram-fac.herokuapp.com/)

A place to post about your pet :)

## Roles

- Joe: Scrum Facilitator
- Alex: QA
- Lisa: Dev-ops
- Abdullah: UX/UI

## Setup

Make sure you have Git and Node (v18) installed.

Clone this repo and cd into the directory

Run ```npm install``` to install all the dependencies

Run ```npm run seed (npm run seedWindow for Windows)``` to seed the local database. 

Run ```npm run dev (npm run devWindow for Windows)``` to start the server.

This uses the nodemon library to auto-restart the server when you save changes.

## User Stories
- [ ] As a user I want to post about my cute pet.
- [ ] As a user I want to comeback to your site and see what I posted is still there.
- [ ] As a user I want to Sign up.
- [ ] As a user I want to log in and log out.
- [ ] As a user I want to be able to add my posts either to my page or to the public page 

## Acceptance Criteria
- [ ] Express server
- [ ] Well-organised modular codebase
- [ ] SQLite database
- [ ] Hosted on Heroku
- [ ] One of the spike topics
- [ ] Validate user-submitted data on the server
- [ ] Handle errors and inform the user
- [ ] Styled appropriately


## Communication
Throughout our project we used pair-programming method to write the code and rosolve issues. We met in-person, as well as had online meetings to discuss and work together. We would gather for 5-10 minutes for a quick huddle to discuss the progress so far, and if we faced any issues.

### Tools Used
Discord
VS Code Live Share extension
Github Project Board
Software Methodologies
During our planning stage, we identified there were functions and components that would be reused in the project. As a result, we decided to include modularization and attempted to follow the DRY principle.

Examples of that can be found in server.js, helpers.js and user-page.js
