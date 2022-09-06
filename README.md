# KrunkScript Deobfuscator

Deobfuscate and beautify compiled KrunkScript

## Screenshot

![screenshot](https://user-images.githubusercontent.com/55899582/188719075-d5121171-07dc-49b0-9da7-b292de39d131.png)

## Usage

1. Install [Tampermonkey](http://www.tampermonkey.net) for your browser
2. Add the [userscript](https://github.com/j4k0xb/krunkscript-deobfuscator/raw/master/script.user.js).
3. Open the browser console and join a map with scripts
4. The deobfuscated code will be logged

## API

Base URL: https://krunkscript-deobfuscator.netlify.app

POST [/api/convert](https://krunkscript-deobfuscator.netlify.app/api/convert)

The body has to contain the js client script of a hosted game (usually starts with `"use strict";`)

See [here](./script.user.js) for an example.
