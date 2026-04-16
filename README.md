# README

![](./promo-001.png)
![](./promo-002.png)

The project uses [@wryrych/design-tokens-example](https://www.npmjs.com/package/@wryrych/design-tokens-example) *npm* *npm* package as a dependency. Each `scss` file has an access to design tokens.

```js
module.exports = {
  pluginOptions: {
    "style-resources-loader": {
      preProcessor: "scss",
      patterns: [
        path.resolve(
          __dirname,
          "node_modules/@wryrych/design-tokens-example/dist/scss/_variables.scss"
        ),
      ],
    },
  },
  …
```

This repository ~~is~~ was originally used as an example for the article [Od design tokenów do zmiennych, czyli Style Dictionary w akcji](https://www.pgs-soft.com/pl/blog/od-design-tokenow-do-zmiennych-czyli-style-dictionary-w-akcji/) (in *Polish*) published on the *PGS software blog*.

## How to run

```sh
yarn
yarn serve
```
