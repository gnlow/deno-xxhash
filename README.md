# deno-xxhash
Fork of [Jason3S/xxhash](https://github.com/Jason3S/xxhash) for deno
## What has changed from the [original](https://github.com/Jason3S/xxhash)?
I just changed module names.  
`import toUtf8 from './toUtf8';` -> `import toUtf8 from './toUtf8.ts';`
## Usage
```ts
import {xxHash32} from "https://raw.githubusercontent.com/gnlow/deno-xxhash/master/mod.ts";

let seed = 0;
let str = 'My text to hash 😊';
let hashNum = xxHash32(str, seed);
console.log(hashNum.toString(16));
```
