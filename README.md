Practice repository for Coursera course - Full-Stack Web Development with React (https://www.coursera.org/learn/front-end-react)

This read me file will cover instructions for all packages which are needed to be installed and fixes, if any issues are found.

Install
--------------------------------------------------
Install yarn: sudo npm install --global yarn --force
yarn --version
yarn init
yarn global add create-react-app@1.5.2

Install create react app : sudo npm install -g create-react-app@1.5.2

create-react-app --help
create-react-app confusion

add following to package.json
,
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test --env=jsdom",
    "eject": "react-scripts eject"
  }
There are issues following Professor's instructions.
///////////////////////////////////////

Using following, fixed the issue:
sudo npm rm -g create-react-app
sudo npm install -g create-react-app
npx create-react-app confusion
cd confusion

yarn start
or 
npm start
