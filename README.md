
# Web Packers - Weback

## 1. Steps to init a Weback project

  ```bash
    git init
    npm init -y
    npm install webpack webpack-cli -D
  ```

## 2. Create the following files
  * webpack.config.js
  * src/index.js
  * public/index.html

## 3. Add plugins

  ```bash
    npm i html-webpack-plugin copy-webpack-plugin @babel/core babel-loader - D
    npm install webpack-dev-server -D
```

## 4. Add scripts in package.json file

  ```bash
    "build": "webpack --mode production",
    "start": "webpack-dev-server --open --mode development"
  ```

## 5. Deploy on Github Pages

  * Installation
  ```bash
    npm install gh-pages -D
  ```

  * Script on package.json file
  ```bash
    "deploy": "gh-page -d dist"
  ```

