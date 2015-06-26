# Linter

[![Slack Badge](https://img.shields.io/badge/chat-atom.io%20slack-blue.svg?style=flat-square)](http://atom-slack.herokuapp.com/)
[![Build Status](https://img.shields.io/travis/AtomLinter/Linter.svg?style=flat-square)](https://travis-ci.org/AtomLinter/Linter)
[![Plugin installs!](https://img.shields.io/apm/dm/linter.svg?style=flat-square)](https://atom.io/packages/linter)
[![Package version!](https://img.shields.io/apm/v/linter.svg?style=flat-square)](https://atom.io/packages/linter)
[![Dependencies!](https://img.shields.io/david/AtomLinter/Linter.svg?style=flat-square)](https://david-dm.org/AtomLinter/linter)

> Lint your code with ease in [Atom Editor](http://atom.io)
>
> The idea is to stop the linter plugins war, by providing a top level API for linters to parse and display errors in the Atom editor.

![Preview](http://g.recordit.co/5LNJjOgLos.gif)

## How to / Installation

Install package through Atom or use CLI:

* `$ apm install linter`

## Configuration

You can customize shortcuts to Linter commands:

* `linter:next-error` (jump to next error line)
* `linter:next-warning` (jump to next warning line)
* `linter:toggle` (disable / enable linters)

Atom -> Open You Keymap:

```
'atom-workspace':
  'linter:next-error': 'ctrl-alt-e'
  'linter:next-warning': 'ctrl-alt-w'
  'linter:toggle': 'ctrl-alt-t'
  'linter:set-bubble-transparent': 'alt'
```

## Availables linters

[Full linters list](http://atomlinter.github.io/)

## API Documentation

[Linter API wiki](https://github.com/AtomLinter/Linter/wiki/Linter-API)

## Contribute

Stick to imposed codestyle:

* `$ npm i -g coffeelint eslint`
* `$ npm run lint`
