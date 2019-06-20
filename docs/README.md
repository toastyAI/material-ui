# Material-UI docs

This is the documentation website of Material-UI.

To start the docs site in development mode, from the project root, run:

```sh
yarn && yarn start
```

If you do not have yarn installed, select your OS and follow the instructions on the [Yarn website](https://yarnpkg.com/lang/en/docs/install/#mac-stable).

*DO NOT USE NPM, use Yarn to install the dependencies.*

## Build settings for Toasty UI deployment using netlify

```sh
Repository: github.com/toastyAI/material-ui
Base directory: Not set
Build command: yarn docs:build && yarn docs:export
Publish directory: docs/export
```

## How can I add a new demo to the documentation?

[You can follow this guide](https://github.com/mui-org/material-ui/blob/master/CONTRIBUTING.md)
on how to get started contributing to Material-UI.

## How do I help improve to the translations?

Please visit https://translate.material-ui.com/ where you will be able to select a language and edit the translations.
Please don't submit pull requests directly.
