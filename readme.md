# Sketch Plugin Boilerplate

> An ultra-minimal skpm template

## Contents

- [Rationale](#rationale)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contacts](#contacts)

## Rationale

I simply needed a [skpm](https://github.com/skpm/skpm) template to scaffold, and spin up a Sketch plugin on the fly.

- This is **not** a Sketch plugin. It's a boilerplate to quickly **build** one
- The template includes my personal name, and contacts. If you're not me... Make sure to edit them! 🙃
- This project could not necessarily address, nor fit all your needs
- This uses [yarn](https://yarnpkg.com/en/) only, no [npm](https://www.npmjs.com/)

## Features

- Temporary shortcut set to `ctrl+cmd+z`
- Customizable linting via [ESLint](https://eslint.org/), and [Prettier](https://prettier.io/)
- [Sketch Runner](https://sketchrunner.com/) integration-ready

## Requirements

```shell
yarn global add skpm
yarn global add eslint
yarn global add babel-eslint
yarn global add prettier
```

Install the proper plugins ([ESLint](https://eslint.org/), [Prettier](https://prettier.io/), [EditorConfig](https://editorconfig.org)) to validate the code directly in the text-editor (optional).

## Installation

```shell
skpm create <project-name> --name "<Project Name>" --template=lucaorio/sketch-plugin-boilerplate --install false
cd <project-name>
yarn install
```

## Usage

```shell
# lint and build
yarn build

# lint
yarn lint

# build with hot reload
yarn watch

# lint, build, and symlink the plugin
yarn postinstall
```

## License

![https://github.com/lucaorio/sketch-plugin-boilerplate/blob/master/license](https://img.shields.io/badge/license-MIT-blue.svg)

---

## Contacts

- 🐦 Twitter [@lucaorio\_](http://twitter.com/@lucaorio_)
- 🕸 Website [lucaorio.com](http://lucaorio.com)
- 📬 Email [luca.o@me.com](mailto:luca.o@me.com)
