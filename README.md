# WebWormhole Binaries

Weekly builds of [https://github.com/saljam/webwormhole](https://github.com/saljam/webwormhole).

![Go CI](https://github.com/pojntfx/webwormhole-binaries/workflows/Go%20CI/badge.svg)

## Installation

Binaries are built weekly and uploaded to [GitHub releases](https://github.com/pojntfx/webwormhole-binaries/releases).

On Linux, you can install them like so:

```shell
$ curl -L -o /tmp/ww https://github.com/pojntfx/bofied/releases/download/latest/ww.linux-$(uname -m)
$ sudo install /tmp/ww /usr/local/bin
```

On macOS, you can use the following to install:

```shell
$ curl -L -o /tmp/ww https://github.com/pojntfx/bofied/releases/download/latest/ww.darwin-$(uname -m)
$ sudo install /tmp/ww /usr/local/bin
```

On Windows, the following should work:

```shell
Invoke-WebRequest https://github.com/pojntfx/bofied/releases/download/latest/ww.windows-x86_64.exe -OutFile \Windows\System32\ww.exe
```

## License

webwormhole-binaries (c) 2021 Felix Pojtinger and contributors

SPDX-License-Identifier: BSD-2-Clause
