# My Default ESLint config

Usage:

Run this command to complete installation:

```
npx install-peerdeps --dev -o --yarn @sigmagf/eslint-config
```

Insert this lines in package.json:

```json
"prettierConfig": "@sigmagf/eslint-config/prettier.config.js",
"eslintConfig": {
  "extends": "@sigmagf/eslint-config"
}
```

Or create `.eslintrc.js` with this code

```javascript
// .eslintrc.js
const config = require('@sigmagf/eslint-config')

module.exports = config;
```

and prettier.config.js with

```javascript
// .prettier.config.js
const config = require('@sigmagf/eslint-config/prettier.config.js')

module.exports = config;
```