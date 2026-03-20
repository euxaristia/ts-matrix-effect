# ts-matrix-effect

A clean, responsive TypeScript implementation of the classic "Digital Rain" effect from The Matrix, designed to run smoothly on an HTML5 `<canvas>`.

## Features
- **TypeScript**: Fully typed for modern web development.
- **Responsive**: Automatically handles window resizing and adapts to the viewport.
- **Throttled rendering**: Uses `requestAnimationFrame` with a simple time-check to run at ~30 FPS, keeping it lightweight.
- **Fade effect**: Characters fade correctly to create the trailing visual effect.
- **Unlicensed**: Released into the public domain. Do whatever you want with it!

## Usage
Simply drop a `<canvas>` element in your HTML with the ID `matrix-canvas`:

```html
<canvas id="matrix-canvas" style="display: block; position: fixed; top: 0; left: 0; z-index: -1;"></canvas>
```

And run the compiled TypeScript:
```javascript
import './src/matrix'; // or the compiled JS
```

## License
Released under the [Unlicense](https://unlicense.org/) (Public Domain).
