# Webpack Crash Course

## By :octocat: Traversy Media - https://www.youtube.com/watch?v=lziuNMk_8eQ

## What is Webpack?
 - Module bundler
 - Custom files or NPM installed
 - Generates static assets
 - Extends with Plugin & Loaders

## Properties of a Module
 - Discrete chunk of functionality 
 - Abstraction
 - Encapsulation
 - Usually a single task or responsibility
 - Reusable

## How is Webpack Different?
 - Code splitting
 - Loaders (CSS, SASS, JSX, etc)
 - Clever Parsing (reqiure("./templates/"+name+".jade"))
 - Plugins

## Example Loaders
   - CSS & Style
   - Sass & Less
   - Coffee
   - Typescript
   - JSX (React)
   - EJS, Pug, Handlebars
   - Babel
   - json
   - and more...

## Installation
 - We can install webpack using npm.
 ```javascript
        // Globally
    npm install -g webpack 

        // Locally
    npm install --save-dev webpack webpack-cli
 ```
 - If you want to keep building webpack use _--watch_
 

## More Info
 - https://webpack.js.org/guides/getting-started/
 - https://github.com/bradtraversy/webpack_app