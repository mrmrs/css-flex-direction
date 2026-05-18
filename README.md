# css-flex-direction

Functional CSS for flex-direction

## Filesize

| File | Size |
|------|------|
| `dist/flex-direction.css` | 1061 bytes |
| `dist/flex-direction.min.css` | 777 bytes (191 Gzipped) |

## Install

```sh
npm install css-flex-direction
```

## Usage

### Import

```css
@import "css-flex-direction";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-flex-direction/dist/flex-direction.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-flex-direction/dist/flex-direction.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.fd-row` | `flex-direction: row;` |
| `.fd-rev` | `flex-direction: row-reverse;` |
| `.fd-col` | `flex-direction: column;` |
| `.fd-colrev` | `flex-direction: column-reverse;` |
| `.fd-i` | `flex-direction: inherit;` |
| `.fd-row-s` | `flex-direction: row;` |
| `.fd-rev-s` | `flex-direction: row-reverse;` |
| `.fd-col-s` | `flex-direction: column;` |
| `.fd-colrev-s` | `flex-direction: column-reverse;` |
| `.fd-i-s` | `flex-direction: inherit;` |
| `.fd-row-m` | `flex-direction: row;` |
| `.fd-rev-m` | `flex-direction: row-reverse;` |
| `.fd-col-m` | `flex-direction: column;` |
| `.fd-colrev-m` | `flex-direction: column-reverse;` |
| `.fd-i-m` | `flex-direction: inherit;` |
| `.fd-row-l` | `flex-direction: row;` |
| `.fd-rev-l` | `flex-direction: row-reverse;` |
| `.fd-col-l` | `flex-direction: column;` |
| `.fd-colrev-l` | `flex-direction: column-reverse;` |
| `.fd-i-l` | `flex-direction: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.fd-row-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/flex-direction.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/flex-direction.css` — formatted
- `dist/flex-direction.min.css` — minified

## License

MIT
