## Installation
```shell
yarn add config-slash-prettier
```
## Usage
Create `.prettierrc.js` and place the below content
```js
module.exports = require('config-slash-prettier');
```

## Override Configuration
Update `.prettierrc.js` with the below content
```js
module.exports = {
  ...require('config-slash-prettier'),
  singleQuote: false,
}
```
