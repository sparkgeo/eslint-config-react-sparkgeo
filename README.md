## Eslint Config Sparkgeo React

A series of linter rules for the Sparkgeo frontend development team. Ideally, it will be a less strict version of eslint-config-airbnb that allows us to live with prettier and other tools.

## Setup

```sh
$ npm i -D @sparkgeo/eslint-config-react
```

Then replace your eslint config with the following:

```js
{
    "extends": ["@sparkgeo/eslint-config-react"]
}

```

## Contributing

If you're a member of Sparkgeo, bug either @brian or @joe or bring up your issue in #spk-processing-tools. All PR's to remove specific rules are welcome.
