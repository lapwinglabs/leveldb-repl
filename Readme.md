
# level-repl

  Super simple REPL for leveldb. Supports get globs.

## Example

  ![view](https://cldup.com/ufKEFH-snQ.png)

## Features

- Glob keys when getting a value
- Support up to Supports up to node 0.11.14 using [level-11](npmjs.org/package/level-11)
- Supports JSON formatting and utf-8 encoding
- Pretty colors

## Usage

```bash
$ level [dbpath]
# example: level db/

> level help

  usage:

      get <key>
      put <key> <value>
      del <key>

> get *
# get all

> get user*
# get all keys starting with "user"

> put fruit apple
> get fruit
# "fruit => apple"

> del fruit
# delete fruit key
```

## License

(The MIT License)

Copyright (c) 2014 Matthew Mueller &lt;matt@lapwinglabs.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
