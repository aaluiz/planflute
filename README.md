panflute
========

Fast Developing  Framework For Flutter

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/panflute.svg)](https://npmjs.org/package/panflute)
[![Downloads/week](https://img.shields.io/npm/dw/panflute.svg)](https://npmjs.org/package/panflute)
[![License](https://img.shields.io/npm/l/panflute.svg)](https://github.com/aaluiz/panflute/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g panflute
$ panflute COMMAND
running command...
$ panflute (-v|--version|version)
panflute/0.0.1 darwin-x64 node-v14.17.1
$ panflute --help [COMMAND]
USAGE
  $ panflute COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`panflute hello [FILE]`](#panflute-hello-file)
* [`panflute help [COMMAND]`](#panflute-help-command)

## `panflute hello [FILE]`

describe the command here

```
USAGE
  $ panflute hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ panflute hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/aaluiz/panflute/blob/v0.0.1/src/commands/hello.ts)_

## `panflute help [COMMAND]`

display help for panflute

```
USAGE
  $ panflute help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
