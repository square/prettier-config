# @square/prettier-config

Square's shared [Prettier](https://prettier.io) configuration.

## Usage

### Install

```sh
npm install --save-dev @square/prettier-config
```

```sh
yarn add --dev @square/prettier-config
```

```sh
pnpm install --dev @square/prettier-config
```

### Configure

Reference the shared configuration in your `package.json` file:

```jsonc
{
  "name": "my-cool-library",
  "version": "9000.0.1",
  "prettier": "@square/prettier-config"
}
```

If you don’t want to use `package.json`, you can use any of the supported extensions to export a string, e.g. `.prettierrc.json`:

```json
"@square/prettier-config"
```

[Read more on Prettier configuration.](https://prettier.io/docs/en/configuration.html)

## Philosophy

> By far the biggest reason for adopting Prettier is to stop all the on-going debates over styles.
>
> – [Prettier's Option Philosophy](https://prettier.io/docs/en/option-philosophy.html)

This minimal, practically nonexistent, configuration is intended to provide consistent, automatic formatting throughout a project.
