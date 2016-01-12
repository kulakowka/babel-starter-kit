# babel-starter-kit

My node.js starter-kit with [babel.js](http://babeljs.io)

#### Setup

Run this command in console to install project.

```
git clone git@github.com:kulakowka/babel-starter-kit.git && cd babel-starter-kit && npm install
```

Start script `npm start` use [require hook](https://babeljs.io/docs/usage/require/):

#### Manual install

```
npm install babel-register babel-preset-es2015 --save
```

#### Add scripts to package.json
```
"scripts": {
    "start": "node -r babel-register index.js"
}
```

#### Create .babelrc

```js
{
  "presets": ["es2015"]
}
```


