# Setup ESLint and Prettier on a React app with a precommit

## Install ESLint

Install dependencies eslint and eslint-plugin-react@latest
**Note: Use the eslint cli to install eslint-plugin-react@latest**

```bash
yarn add eslint --dev
```

## Configure ESLint

Use eslint cli.

```bash
yarn eslint --init
```

Example:
? How would you like to use ESLint? To check syntax and find problems
? What type of modules does your project use? JavaScript modules (import/export)
? Which framework does your project use? React
? Does your project use TypeScript? No
? Where does your code run? Browser
? What format do you want your config file to be in? JSON
The config that you've selected requires the following dependencies:
eslint-plugin-react@latest
? Would you like to install them now with npm? Yes

### Include jest key to .eslintrc.json

```json
 "env": {
    "jest": true
  },
```

### Include eslint scripts to package.json

```json
  "scripts": {
    "lint": "eslint .",
    "lint:fix": "eslint --fix ."
  },
```

## Install Prettier

## Configure Prettier

## Integrate Prettier with ESLint

## Lint and format at each commit
