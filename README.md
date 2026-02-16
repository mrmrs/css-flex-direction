# css-flex-direction

Functional CSS for flex-direction

## Filesize

| File | Size |
|------|------|
| `dist/flex-direction.css` | 1301 bytes |
| `dist/flex-direction.min.css` | 1017 bytes (197 Gzipped) |

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
| `.direction-row` | `flex-direction: row;` |
| `.direction-row-reverse` | `flex-direction: row-reverse;` |
| `.direction-column` | `flex-direction: column;` |
| `.direction-column-reverse` | `flex-direction: column-reverse;` |
| `.direction-inherit` | `flex-direction: inherit;` |
| `.direction-row-s` | `flex-direction: row;` |
| `.direction-row-reverse-s` | `flex-direction: row-reverse;` |
| `.direction-column-s` | `flex-direction: column;` |
| `.direction-column-reverse-s` | `flex-direction: column-reverse;` |
| `.direction-inherit-s` | `flex-direction: inherit;` |
| `.direction-row-m` | `flex-direction: row;` |
| `.direction-row-reverse-m` | `flex-direction: row-reverse;` |
| `.direction-column-m` | `flex-direction: column;` |
| `.direction-column-reverse-m` | `flex-direction: column-reverse;` |
| `.direction-inherit-m` | `flex-direction: inherit;` |
| `.direction-row-l` | `flex-direction: row;` |
| `.direction-row-reverse-l` | `flex-direction: row-reverse;` |
| `.direction-column-l` | `flex-direction: column;` |
| `.direction-column-reverse-l` | `flex-direction: column-reverse;` |
| `.direction-inherit-l` | `flex-direction: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.direction-row-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/flex-direction.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/flex-direction.css` — formatted
- `dist/flex-direction.min.css` — minified

## License

MIT
