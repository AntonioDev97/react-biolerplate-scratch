# React Boilerplate From Scratch
### _This is a boilerplate to create a new react app from scratch_

All features, tool and steps are going to be included here to achieve a good result.
This can be taken as a base for you projects when your objective is to create a agile React project without use ```create-react-app``` instead of it create from scratch.

## Tools
- IDE (VSCode reommended).
- Git and repository.
- Node & NPM
- React & Dependencies

## Packages / Dependencies
All version here can be updated.

| Dependency | Version |
| ------ | ------ |
| NodeJS | 18.15.0 |
| React | 18.2.0 |
| react-dom | 18.2.0 |
| sass | 1.59.2 |
| prop-types | 15.8.1 |
| webpack | 5.76.1 |
| dev dependencies | review package.json |

## Steps
1. Create your project in a new git repository then clone it in your local machine i.e.
    ``` sh
    git clone https://github.com/AntonioDev97/react-boilerplate-scratch.git
    ```
2. Open project folder and execute ```npm init``` and configure your project package.
3. Install project dependencies: ```npm install react react-dom react-router-dom sass prop-types --save```.
4. Install Project dev dependencies: ```npm install @babel/core @babel/preset-env @babel/preset-react babel-loader babel-plugin-transform-class-properties css-loader html-loader html-webpack-plugin react-hot-loader sass-loader style-loader webpack webpack-cli webpack-dev-server --save-dev```
5. Create project file structure and set initial settings:
    📦react-boilerplate-scratch
     ┣ 📂public
     ┃ ┣ 📜+favicon.ico
     ┃ ┗ 📜index.html
     ┣ 📂src
     ┃ ┣ 📂components
     ┃ ┣ 📂hooks
     ┃ ┣ 📂pages
     ┃ ┣ 📂utils
     ┃ ┣ 📜App.jsx
     ┃ ┣ 📜App.scss
     ┃ ┣ 📜App.test.jsx
     ┃ ┣ 📜index.jsx
     ┃ ┗ 📜index.scss
     ┣ 📜.babelrc
     ┣ 📜.gitignore
     ┣ 📜.prettierrc
     ┣ 📜LICENSE
     ┣ 📜README.md
     ┣ 📜package-lock.json
     ┣ 📜package.json
     ┗ 📜webpack.config.js
6. Configure ```App.jsx```, ```index.jsx```, ```webpack.config.js``` and corresponding settings files to start running the project (you can find all required files and settings in the repository plase take base on them).
7. Add the ```build``` and ```start``` scripts to ```package.json```:
    ```json
    "scripts": {
        "start": "webpack serve --mode development",
        "build": "webpack --mode production"
    }
    ```
8. Execute ```npm start``` and watch the magic.

## Conclution
Thanks for read all instruction I hope this serve to you as a guide for future projects & enjoy to create a react app without ```create-react-app``` tool, now you can enjoy all the advantages of pure react.
Best Regards!


## License
MIT
**Free Software, Hell Yeah!**