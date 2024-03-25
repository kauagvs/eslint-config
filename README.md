# Lemenov ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @lemenov/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@lemenov/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```
