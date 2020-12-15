# Combining Selectors

SwordCSS provides simple properties to combine the CSS of certain selectors.

## Combining Classes

With `sw-class` you copy the CSS of certain classes.

### Input

```css
.elem {
    sw-class: elem2;
}
.elem2 {
    width: 20px;
}
```

### Output

```css
.elem {
    width: 20px;
}
.elem2 {
    width: 20px;
}
```

## Combining IDs

With `sw-id` you can copy the CSS of IDs.

### Input

```css
.elem {
    sw-id: elem2;
}
#elem2 {
    width: 20px;
}
```

### Output

```css
.elem {
    width: 20px;
}
#elem2 {
    width: 20px;
}
```

## Combining with Queries

With `sw-query` you can copy the CSS of valid DOM queries.

### Input

```css
.elem {
    sw-query: #elem2 .elem3;
}
#elem2 {
    width: 20px;
}
.elem3 {
    height: 30px;
}
```

### Output

```css
.elem {
    width: 20px;
    height: 30px;
}
#elem2 {
    width: 20px;
}
.elem3 {
    height: 30px;
}
```