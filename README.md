# html-vue-translator
Create a web translator using vue, but not woring, console shows no error

Forked from
[wordtranslator](https://github.com/bradtraversy/wordtranslator)

## deloy the vue project

```
npm run build
```
on project created by `vue init webpack myproject`
Then copy the files in `dist` folder to root directory

## stackoverflow answers

https://stackoverflow.com/questions/42936588/how-to-deploy-vue-app

the right answer is 


> the answer should be "the content of the dist folder is all you need. You do not need to copy `/index.html` but only the `index.html` in the `dist` folder is needed. In addition, prior to running npm run build you should configure your production path in `config/index.js`

not the "right answer" one.

## webpack

This file used ES6 code, cannot be drectly uploaded to server, use `vue-cli` to create and build the app instead.
