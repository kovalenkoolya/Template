**Project template**
  What is it?
  -----------------
This template will help you save time when creating a project. It contains: the main empty file serverjs;  the configuration file  .editorconfig; a file with installed dependencies -package.json; files for the extension checking errors - eslint; .gitignore for git; files for the extension that can prevent bad git commit git push and more -  huskyrc.

Dependencies installation
--------------------------------------
npm i express
npm i nodemon
npm i eslint
npm i eslint-config-airbnb-base
npm i eslint-plugin-import
npm i  husky

Used scripts
--------------------
  "start": "node app/server.js",
    "start:dev": "nodemon app/server.js",
    "test": "echo 'run all tests'",
    "lint": "eslint ./app/server.js",
    "lint:fix": "eslint ./app/server.js --fix"

  Contacts
  ---------------
If you have any questions please text to okovalenko.dev@gmail.com
