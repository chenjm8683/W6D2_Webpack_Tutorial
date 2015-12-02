Webpack Tutorial Example
http://webpack.github.io/docs/tutorials/getting-started/

Requirement:
1. node.js
2. npm install webpack -g
3. npm install css-loader style-loader


In BINDING LOADERS:
- May need to add escape before !, as some terminal will try to run bash without escaping !
- i.e. $ webpack ./entry.js bundle.js --module-bind "css=style\!css"
