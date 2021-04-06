# srcset-parser

This is a tiny node.js wrapper around [sindresorhus/srcset](https://github.com/sindresorhus/srcset).

## Usage

```bash
srcset-parser 'banner-HD.jpg 2x, banner-phone.jpg 100w'
```

```json 
[{"url":"banner-HD.jpg","density":2},{"url":"banner-phone.jpg","width":100}]
```
