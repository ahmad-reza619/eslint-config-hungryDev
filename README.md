# eslint-config-hungryDev

an eslint config for my own use case. You can use it too though :smile:

**Warning**: Currently this eslint config only support React. i will update it when i have the time

### How to install
```bash
npm i -D eslint eslint-config-hungrydev eslint-plugin-prettier eslint-plugin-import eslint-plugin-jsx eslint-plugin-react eslint-plugin-react-hooks
```

### Usage
create an `.eslintrc.js` and then write this:
```js
module.exports = {
  extends: ['hungrydev/react'],
  
  rules: {
    // ... add your own override here
  }
};
```
