# R+D linters

Based on https://github.com/airbnb/javascript/ and https://github.com/airbnb/css/ linting style guides.

## Installation

1. Issue the following command:

```
yarn add -D rd-linters
```

2. In your node project, add a `.eslintrc` file with the following content:

```
{
  "extends": "rd"
}
```

3. In your VueJS project, add a `.eslintrc` file with the following content:

```
{
  "extends": "rd-vue"
}
```

4. In your project, add a `.stylelintrc` file with the following content:

```
{
  "extends": "stylelint-config-rd"
}
```

5. Run the following commands from your project root

```
cp ./node_modules/rd-linters/.editorconfig ./
cp ./node_modules/rd-linters/.prettierrc ./
```

6. Install the following VSCode extensions:

```
ext install eslint
ext install stylelint
```

> Note: You may have to restart VSCode in order for the changes to take effect
