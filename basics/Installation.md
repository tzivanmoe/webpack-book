# Initialization and Installation

![So it begins](http://i3.kym-cdn.com/photos/images/original/000/288/697/3fa.jpg)

## Initialization

If your are starting a new project start by creating some files as follows

```
project/
-- index.html
-- index.js
-- webpack.config.js
```

Then initialize `npm` in your project folder

```
npm init
```


## Installation

## Webpack



Start by installing Webpack globally

```
npm install -g webpack
```

When developing, it is good practice to add Webpack as a dependency to your project.

```
npm install --save-dev webpack
```

## WebpackDevServer

Webpack comes with a package for use while developing. 

It allows you to build and serve your files on the fly with auto rebuild when you update your files and some other lovely things!
Go ahead and install it.

```
npm install --save-dev webpack-dev-server
```

