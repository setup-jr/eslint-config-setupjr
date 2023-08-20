# SetupJR ESLint config

## Usage

### Install peer dependencies

- #### npm

```bash
npm add -D @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-import-helpers eslint-plugin-prettier prettier typescript eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks eslint-config-setupjr
```

- #### yarn

```bash
yarn add -D @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-import-helpers eslint-plugin-prettier prettier typescript eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks eslint-config-setupjr
```

- #### pnpm

```bash
pnpm add -D @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-import-helpers eslint-plugin-prettier prettier typescript eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks eslint-config-setupjr
```

### Configuration

in our eslint config file

```json
{
  "extends": [
    "setup-jr"
  ]
}
```
