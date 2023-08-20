# ESLint SetupJr

## Uso

### Instalação

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

### Configuração

Adicione o arquivo ```.eslintrc``` com o seguinte código

```json
{
  "extends": [
    "setupjr"
  ]
}
```

Adicione o arquivo ```.prettierrc``` com o seguinte código

```json
{
  "semi": false,
  "singleQuote": true
}

```

## License

[MIT License](./license.md)
