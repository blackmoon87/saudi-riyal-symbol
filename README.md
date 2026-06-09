# Saudi Riyal Symbol ﷼

The new Saudi Riyal (SAR) currency symbol as a web font.

## Quick Start

```html
<style>
  @font-face {
    font-family: 'SaudiRiyal';
    src: url('dist/saudiriyalsymbol.woff2') format('woff2');
  }
  .sar { font-family: 'SaudiRiyal', sans-serif; }
</style>

<span class="sar">&#xea;</span> 199.99
```

## Files

```
dist/           → Font files (woff2, woff, ttf, otf)
examples/       → Usage demo (index.html)
```

## Unicode

The symbol uses Unicode `U+00EA` — HTML entity: `&#xea;`

## SAMA Guidelines

- Place the symbol **left** of the number
- Keep a space between symbol and number
- Symbol height should match surrounding text

Full guide: [SAMA Guidelines](https://www.sama.gov.sa/ar-sa/Currency/SRS/Documents/Guidelines.pdf)

## License

MIT
