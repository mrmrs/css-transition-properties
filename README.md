# css-transition-properties

Functional CSS for transition-properties

## Filesize

| File | Size |
|------|------|
| `dist/transition-properties.css` | 2425 bytes |
| `dist/transition-properties.min.css` | 1763 bytes (314 Gzipped) |

## Install

```sh
npm install css-transition-properties
```

## Usage

### Import

```css
@import "css-transition-properties";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-transition-properties/dist/transition-properties.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-transition-properties/dist/transition-properties.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.tp-n` | `transition-property: none;` |
| `.tp-all` | `transition-property: all;` |
| `.tp-i` | `transition-property: inherit;` |
| `.tp-c` | `transition-property: color;` |
| `.tp-bc` | `transition-property: background-color;` |
| `.tp-w` | `transition-property: width;` |
| `.tp-h` | `transition-property: height;` |
| `.tp-l` | `transition-property: left;` |
| `.tp-r` | `transition-property: right;` |
| `.tp-t` | `transition-property: top;` |
| `.tp-b` | `transition-property: bottom;` |
| `.tp-o` | `transition-property: opacity;` |
| `.tp-n-s` | `transition-property: none;` |
| `.tp-all-s` | `transition-property: all;` |
| `.tp-i-s` | `transition-property: inherit;` |
| `.tp-c-s` | `transition-property: color;` |
| `.tp-bc-s` | `transition-property: background-color;` |
| `.tp-w-s` | `transition-property: width;` |
| `.tp-h-s` | `transition-property: height;` |
| `.tp-l-s` | `transition-property: left;` |
| `.tp-r-s` | `transition-property: right;` |
| `.tp-t-s` | `transition-property: top;` |
| `.tp-b-s` | `transition-property: bottom;` |
| `.tp-o-s` | `transition-property: opacity;` |
| `.tp-n-m` | `transition-property: none;` |
| `.tp-all-m` | `transition-property: all;` |
| `.tp-i-m` | `transition-property: inherit;` |
| `.tp-c-m` | `transition-property: color;` |
| `.tp-bc-m` | `transition-property: background-color;` |
| `.tp-w-m` | `transition-property: width;` |
| `.tp-h-m` | `transition-property: height;` |
| `.tp-l-m` | `transition-property: left;` |
| `.tp-r-m` | `transition-property: right;` |
| `.tp-t-m` | `transition-property: top;` |
| `.tp-b-m` | `transition-property: bottom;` |
| `.tp-o-m` | `transition-property: opacity;` |
| `.tp-n-l` | `transition-property: none;` |
| `.tp-all-l` | `transition-property: all;` |
| `.tp-i-l` | `transition-property: inherit;` |
| `.tp-c-l` | `transition-property: color;` |
| `.tp-bc-l` | `transition-property: background-color;` |
| `.tp-w-l` | `transition-property: width;` |
| `.tp-h-l` | `transition-property: height;` |
| `.tp-l-l` | `transition-property: left;` |
| `.tp-r-l` | `transition-property: right;` |
| `.tp-t-l` | `transition-property: top;` |
| `.tp-b-l` | `transition-property: bottom;` |
| `.tp-o-l` | `transition-property: opacity;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.tp-n-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/transition-properties.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/transition-properties.css` — formatted
- `dist/transition-properties.min.css` — minified

## License

MIT
