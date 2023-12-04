# DosSantosDev ESLint config

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
npm i -D eslint @dossantosdev/eslint-dossantosdev
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@dossantosdev/eslint-dossantosdev/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @dossantosdev/eslint-dossantosdev
```
Inside `.eslintrc.json`
```
{
  "extends": "@dossantosdev/eslint-dossantosdev/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @dossantosdev/eslint-dossantosdev
```
Inside `.eslintrc.json`
```
{
  "extends": "@dossantosdev/eslint-dossantosdev/node"
}
```