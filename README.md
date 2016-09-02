# griddy.css

> Responsive 12 column based grid in 311 Bytes when gzipped.

<img src="https://dl.dropboxusercontent.com/u/100463011/griddy-css.gif" width="600" />

## Install

```bash
npm i griddy.css --save
```

or 

```html
<link rel="stylesheet" href="https://unpkg.com/griddy.css@1.0.0/dist/griddy.min.css" type="text/css" />
```

## Examples

**2 different columns**

```html
<div class="griddy">
    <div class="griddy-col griddy-col-4">.col.col-4</div>
    <div class="griddy-col griddy-col-8">.col.col-8</div>
</div>
```

**1 column with offset**

```html
<div class="griddy">
    <div class="griddy-col griddy-col-4 griddy-offset-6">.col.col-4.offset-6</div>
</div>
```

### List of classes

- `.griddy`
- `.griddy-col`
- `.griddy-col-right`
- `.griddy-col-{COLUMN NUMBER}`
- `.griddy-offset-{OFFSET NUMBER}`

---

**MIT Licensed**
