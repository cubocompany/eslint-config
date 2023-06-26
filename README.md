# CuboCompany ESLint config

## Whats included?

- AirBNB config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies
```
npm i -D eslint eslint-config-cubocompany
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "eslint-config-cubocompany/react"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.