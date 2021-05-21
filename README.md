# Customize Grid System

> Use Bootstrap 4.4.1

## Usage Classes

### Container

```css
.container {
  margin-right: auto;
  margin-left: auto;
  padding-right: 15px;
  padding-left: 15px;
  width: 100%;
}

@media (min-width: 576px) {
    .container {
      max-width: 540px;
    } 
}

@media (min-width: 768px) {
    .container {
      max-width: 720px;
    }
}

@media (min-width: 992px) {
    .container {
      max-width: 960px;
    }
}

@media (min-width: 1200px) {
    .container {
      max-width: 1140px;
    }
}
```

### Row

```css
.row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}
```

### no-gutters

```html
<div class="row no-gutters">
    <div class="col"></div>
</div>
```

```css
.no-gutters {
    margin-right: 0;
    margin-left: 0;
}

.no-gutters > .col,
.no-gutters > [class*="col-"] {
    padding-right: 0;
    padding-left: 0;
}
```

### Column

- `.col`
- `.col-[ sm | md | lg | xl ]`
- `.col-[ 1-12 ]`
- `.col-[ sm | md | lg | xl ]-[ 1-12 ]`

### Order

- `.order-first`
- `.order-[ sm | md | lg | xl ]-first`
- `.order-last`
- `.order-[ sm | md | lg | xl ]-last`
- `order-[ 0-12 ]`
- `order-[ sm | md | lg | xl ]-[ 0-12 ]`

### Offset

- `.offset-[ 1-11 ]`
- `.offset-[ sm | md | lg | xl ]-[ 0-11 ]`
