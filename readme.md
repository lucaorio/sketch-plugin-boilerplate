## Sketch Plugin Boilerplate

> An ultra-minimal boilerplate to get up and running with a Sketch plugin

## Contents

- [Rationale](#rationale)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contacts](#contacts)

## Rationale

[skpm](https://github.com/skpm/skpm) does an amazing job at scaffolding, building, and publishing Sketch plugins. In fact, this boilerplate itself uses it. However, I often find myself copy/pasting files and configurations between different plugins, and I needed a repo to clone on the fly.

- This is **not** a Sketch plugin. It's a boilerplate to quickly **build** one
- The project could not necessarily address, nor fit all your needs
- Some features offered out-of-the-box by skpm are not included, as I don't use them

## Features

- Temporary shortcut set to `ctrl+cmd+z`
- Customizable linting via [ESLint](https://eslint.org/), and [Prettier](https://prettier.io/)
- [Sketch Runner](https://sketchrunner.com/) integration already included

## Requirements

```shell
yarn global add skpm
yarn global add eslint
yarn global add babel-eslint
yarn global add prettier
```

Install the proper plugins ([ESLint](https://eslint.org/), [Prettier](https://prettier.io/), [EditorConfig](https://editorconfig.org)) to directly validate code in the text-editor (optional).

## Installation

```shell
git clone git@github.com:lucaorio/sketch-plugin-boilerplate.git
cd sketch-plugin-boilerplate
yarn start
```

## Usage

```shell
# lint and build
yarn build

# lint
yarn lint

# build with hot reload
yarn watch

# symlink the plugin
yarn start
```

## License

![https://github.com/lucaorio/sketch-styles-generator/blob/master/license](https://img.shields.io/badge/license-MIT-blue.svg)

---

## Contacts

- 🐦 Twitter [@lucaorio\_](http://twitter.com/@lucaorio_)
- 🕸 Website [lucaorio.com](http://lucaorio.com)
- 📬 Email [luca.o@me.com](mailto:luca.o@me.com)
