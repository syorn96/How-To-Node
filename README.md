# How to Node
Node is a platform that allows JavaScript to be run on a server.

## [Setting up a Node Project] (https://gasei.gitbook.io/sei/05-node-express/00readme/01intro-to-node)
1. Create a new folder

``` mkdir my-first-node-proj ```

2. Initialize NPM inside the project folder.

``` npm init ```

3. a) Make an entry point.

``` touch index.js ```

3. b) Write some code and run it to see Node work!

``` console.log('Hello World!') ```

4. Run the program in terminal!

``` node index.js or [js file name] ```

## [Node Modules] (https://gasei.gitbook.io/sei/05-node-express/00readme/02modules)
1. Create a Module and add the following code:

``` touch myModule.js ```
``` module.exports.beBasic = () => console.log("That's so fetch!") ```

2. Import the Module. Add the following code to index.js:

``` const myModule = require('./myModule.js'); ``` 
``` myModule.beBasic(); ```

3. Write more code in myModule.js, just make sure to add ``` module.exports. ``` and then import it into index.js file.

## [Node Packages Modules] (https://gasei.gitbook.io/sei/05-node-express/00readme/03packages)
1. Visit (https://www.npmjs.com/) and search for NPM's you'd like to use.

EX: (https://www.npmjs.com/package/meow)

2. a) To install an NPM local to a repo type ``` npm install meow or (NPM name) ``` into the terminal associated to the repo.

2. b) To install an NPM globally type ``` npm install -g meow or (NPM name) ```

3. Read through the selected NPM's Features and Usage.