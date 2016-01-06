# babel-starter-kit

My node.js starter-kit with [babel.js](http://babeljs.io)

#### Setup

Run this command in console to install project.

```
git clone git@github.com:kulakowka/babel-starter-kit.git && cd babel-starter-kit && npm install
```

Start script `npm start` use [require hook](https://babeljs.io/docs/usage/require/):

#### package.json
```
"scripts": {
    "start": "node -r babel-register index.js"
}
```

#### .babelrc

```js
{
  "presets": ["es2015"]
}
```
