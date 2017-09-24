# trannounce

Simple script for automatically re-announcing torrents that failed the last announce, with a configurable delay between each announcement.

## Requirements

* Python 3
* `transmissionrpc`
* `click`

## Usage

```shell
$ trannounce --address http://127.0.0.1:9091/transmission/rpc [--username NAME] [--password PASSWORD]
```

## Copyright

This is free and unencumbered software released into the public domain.

See LICENSE.txt or unlicense.org for more information.
