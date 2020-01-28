Download this file;
Answer all questions;
Create new repository, push this file with answers and send me a like;

### 1. How to init NPM to new project?

 1. Add new terminal
 2. Write: npm init 

### 2. How to install and save npm packages? 

 Write npm install (package name) --save-dev OR Write name of the package directly in package.json file and write npm install in terminal


### 3. How to install webpack to your project and where to wright configurations? 

1. Install: npm i webpack --save-dev 2. Write configurations: webpack.config.js


### 4. How and where need to add webpack build and watch command? 

1. Describe these commands in package.json file as scripts. For example:

"scripts": {
    "build": "webpack",
    "watch": "webpack --watch"

2. Write in terminal: npm run build / npm run watch to initiate command


### 5. How to specify entry point in webpack configuration?

 entry: './file_name'


### 6. How to specify entry file output in webpack configuration?

output: {
    filename: 'file_name'
  }


### 7. How to specify entry file output path in webpack configuration?

Write in webpack.config.js file: 

module.exports = {
  entry: './src/index.js',
  mode: 'development',
  output: {
    filename: 'main.js',
    path: path.resolve(__dirname, 'public'),
  },


### 8. How to create new repository in Github?

github.com -> your repositories -> new


### 9. How to init GIT in project?

write in terminal: git init OR write in terminal: git clone (url of repository) if repository is already created in GitHub.com


### 10. How to add all changes/files to git index?

write in terminal: git add OR git add (file_name where the changes have been made)

for example: git add index.html


### 11. How to commit message for new changes?

write in terminal: git commit -m “initial commit for website”


### 12. How to add remote URL to GIT project?



### 13. How to push changes to master?

write in terminal: git push