# My Default ESLint config

Usage:

Run this command to complete installation:

```
npx install-peerdeps --dev -o --yarn @sigmagf/eslint-config
```

Insert this lines in package.json:

```json
"eslintConfig": {
  "extends": "@sigmagf/eslint-config"
}
```

Or create `.eslintrc.js` with paste this code:

```javascript
// .eslintrc.js
const config = require('@sigmagf/eslint-config')

module.exports = config;
```