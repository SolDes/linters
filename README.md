# R+D linters

Based on https://github.com/airbnb/javascript/ and https://github.com/airbnb/css/ linting style guides.

## Installation

1. Issue the following command:

```
yarn add -D rd-linters
```

2. In your project, add a `.eslintrc` file with the following content:

```
{
  "extends": "rd"
}
```

3. Runn the following command from your project root

```
cp ./node_modules/rd-linters/{.editorconfig,.prettierignore,.prettierrc.js} ./
```

4. Install the following VSCode extensions:

```
ext install eslint
ext install prettier-vscode
```

> Note: You may have to restart VSCode in order for the changes to take effect

## VSCode Plugins

- [Sass Lint](https://marketplace.visualstudio.com/items?itemName=glen-84.sass-lint)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
