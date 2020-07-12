# customizing-code-frame

A small library for displaying code frames

Usage

```js
import { createCodeFrame } from 'customizing-code-frame';

const str = `foo\nbar\nbob`;

const codeFrame = createCodeFrame(str, 1, 2);

console.log(codeFrame);

// Logs:
//   1 | foo
// > 2 | bar
//     |  ^
//   3 | bob
```

### License

`MIT`, see [the license file](./LICENSE).