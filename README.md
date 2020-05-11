# `@elunic/ecs-tslint`

[![Build Status](https://travis-ci.org/elunic/ecs-tslint.svg?branch=master)](https://travis-ci.org/elunic/ecs-tslint)

The elunic coding styles for TSlint

## Table of Contents

- [`@elunic/ecs-tslint`](#elunicecs-tslint)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
    - [`tslint`](#tslint)
  - [License](#license)

## Installation

```bash
$ npm i -D @elunic/ecs-tslint
```

## Usage

### `tslint`

Note that `tslint` is deprecated with an expected EOL at the end of 2020.

Currently, the `tslint` configurations for **Angular** are still in use because Angular has
not yet switched to `eslint`.

- `tslint.json`
- `tslint.fix.json`
- `tslint-angular7.json`
- `tslint-angular7.fix.json`
- `tslint-angular8.json`
- `tslint-angular8.fix.json`
- `tslint-angular9.json`
- `tslint-angular9.fix.json`
- `tslint-react16.json`
- `tslint-react16.fix.json`

Example usage for your `/tslint.json`:

```json
{
  "extends": "@elunic/ecs-tslint/tslint.json",
  "rules": {}
}
```

## License

MIT License

Copyright (c) 2020 elunic AG/William Hefter <wh@elunic.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
