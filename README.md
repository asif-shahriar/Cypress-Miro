# Cypress page object model automation project
## Test Cases
* Sign up with valid email
* Attempt to sign up with invalid email
* Attempt to sign up with empty email
* Attempt to sign up with empty name
* Attempt to sign up with empty password
* Attempt to sign up without accepting terms and conditions

## Prerequisites
* Install Nodejs latest version
* Stable internet connection

## How to run this project
* Clone the repo
* Enter your email in the [informations.json](https://github.com/asif-shahriar/Cypress-Miro/blob/main/cypress/fixtures/informations.json "informations.json") file
* Open cmd in the root folder
* Give following command
```
npm install
```
```
npx cypress run --spec ./cypress/integration/Pages/* --headed --browser=chrome
```
**Enter a new email in the "informations.json" file each time you run this project**
