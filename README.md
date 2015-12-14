# lz4.js

LZ4 for browser

## Install and Use

console

```
bower install lz4
```

html

```html
<script src="bower_components/lz4/lz4.js"></script>
```

## High Level API

### lz4.compress(source, compressLevel)

* source `Uint8Array`
* compressLevel `number` (`0-16`)
* return `Uint8Array`

### lz4.decompress(source)

* source `Uint8Array`
* return `Uint8Array`

## Development

### Require

* latest emscripten
* nodejs v5.0~

### Init

Get repos.

```
git clone git@github.com:ukyo/lz4.js.git
```

If you don't install the grunt-cli run below.

```
npm install -g grunt-cli
```

Install dev dependencies

```
cd path/to/lz4.js
npm install
```

Download original LZ4 repos and compile for development.

```
grunt init
```

### Write codes

Watch codes update and test.

```
grunt watch
```

### Release

Release build.

```
grunt release
```
