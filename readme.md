# HI THERE

This is my 

# React Gulp Browserify Boilerplate

Its basically a template development environment with all of my favorite dependencies. It also might be useful to look at, if you are learning how to use Elm.

How to get going..
```
> git clone https://github.com/Chadtech/react-gulp-browserify-boilerplate new-project
> cd new-project
> npm install
> gulp

then open up http://localhost:2980
```


This repo is organized as ..
```
dist/                     -- Your production-ready app
development/                      -- Your development app
  index.html
source/                   -- Source files
  app.jsx                  -- Loads your elm file, and handles ports
  Actions/
    Field.jsx
  Styles/
    Main.styl          
    point.styl
    input-field.styl
server/
  app.js
gulpFile.js
