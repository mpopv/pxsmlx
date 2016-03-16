# pmtds

I like to nest media queries inside elements in SCSS, but I was sick of writing out media queries for small responsive changes. *pmtds* is a mixin designed to alleviate the stress of nested media queries.

```scss
  div.responsive {
    @include pmtds(width, 100px, 200px, 300px, 400px); 
  }
```

*pmtds* stands for *property*, *mobile*, *tablet*, *desktop*, *superwide*. It's a shorthand to help you remember the mixin arguments.
