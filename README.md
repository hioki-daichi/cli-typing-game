# splatoon2-weapons-typing

[![Build Status](https://travis-ci.com/hioki-daichi/splatoon2-weapons-typing.svg?branch=master)](https://travis-ci.com/hioki-daichi/splatoon2-weapons-typing)
[![codecov](https://codecov.io/gh/hioki-daichi/splatoon2-weapons-typing/branch/master/graph/badge.svg)](https://codecov.io/gh/hioki-daichi/splatoon2-weapons-typing)
[![Go Report Card](https://goreportcard.com/badge/hioki-daichi/splatoon2-weapons-typing)](https://goreportcard.com/report/github.com/hioki-daichi/splatoon2-weapons-typing)
[![GoDoc](https://godoc.org/github.com/hioki-daichi/splatoon2-weapons-typing?status.svg)](https://godoc.org/github.com/hioki-daichi/splatoon2-weapons-typing)

## Overview

This is a typing game that types weapon names of Splatoon2.

The time limit is 15 seconds. (You can also change it to 30 seconds by specifying `--timeout=30` etc.)

When tye type matches, "Splatted {weapon name}!" is displayed in the colored balloon.

At the end of the game, the following score will be displayed.

- Total number of hits
- Hits per second
- Number of hits per character

## How to try

```shell
$ make build
$ ./splatoon2-weapons-typing
```

## Options

| Option                   | Description                                                                                         |
| ---                      | ---                                                                                                 |
| `--timeout=15`           | Time limit in this typing game (default 15)                                                         |
| `--path="./weapons.txt"` | File path in which a list of words used for this typing game is described (default "./weapons.txt") |

## DEMO

![demo](https://raw.githubusercontent.com/wiki/hioki-daichi/splatoon2-weapons-typing/images/demo.gif)
