# eslint-config-adpeda

A shareable eslint config for Innovatetech's projects.

## Install

```bash
npm install --save-dev adpeda/eslint-config
```

### Installing peerDependencies

```bash
npm install --save-dev babel-eslint eslint-plugin-import
```

## Usage

Add the following to your `.eslintrc.js`.

```
{
  'extends': '@adpeda/eslint-config'
}
```

### Additional

If you want to enforce `jsdoc` rules used by adpeda.

```bash
npm install --save-dev eslint-plugin-jsdoc
```

```
{
  'extends': [
    '@adpeda/eslint-config',
    '@adpeda/eslint-config/jsdoc'
  ]
}
```

If you are using `react`.

```bash
npm install --save-dev eslint-plugin-react
```

```
{
  'extends': [
    '@adpeda/eslint-config',
    '@adpeda/eslint-config/react'
  ]
}
```

If you are using `typescript`:

```bash
 npm install --save-dev @typescript-eslint/eslint-plugin @typescript-eslint/parser
```

```
{
  'extends': [
    '@adpeda/eslint-config',
    '@adpeda/eslint-config/typescript'
  ]
}
```
