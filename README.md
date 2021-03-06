easy-ts
=======

easy-ts cli

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/easy-ts.svg)](https://npmjs.org/package/easy-ts)
[![Downloads/week](https://img.shields.io/npm/dw/easy-ts.svg)](https://npmjs.org/package/easy-ts)
[![License](https://img.shields.io/npm/l/easy-ts.svg)](https://github.com/DustarMao/easy-ts/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g easy-ts
$ easy-ts COMMAND
running command...
$ easy-ts (-v|--version|version)
easy-ts/0.0.1 win32-x64 node-v14.15.3
$ easy-ts --help [COMMAND]
USAGE
  $ easy-ts COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`easy-ts hello [FILE]`](#easy-ts-hello-file)
* [`easy-ts help [COMMAND]`](#easy-ts-help-command)

## `easy-ts hello [FILE]`

describe the command here

```
USAGE
  $ easy-ts hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ easy-ts hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/DustarMao/easy-ts/blob/v0.0.1/src/commands/hello.ts)_

## `easy-ts help [COMMAND]`

display help for easy-ts

```
USAGE
  $ easy-ts help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
