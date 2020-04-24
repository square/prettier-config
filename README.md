# @square/prettier-config

Square's shared [Prettier](https://prettier.io) configuration.

## Usage

**Install**:

```sh
$ yarn add --dev @square/prettier-config
```

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@square/prettier-config"
}
```

[Read more on sharing configurations.](https://prettier.io/docs/en/configuration.html#sharing-configurations)

## Philosophy

> By far the biggest reason for adopting Prettier is to stop all the on-going debates over styles.
>
> – [Prettier's Option Philosophy](https://prettier.io/docs/en/option-philosophy.html)

This minimal configuration is intended to provide consistent, automatic formatting throughout a project and pairs well with [eslint-plugin-square](https://github.com/square/eslint-plugin-square).
