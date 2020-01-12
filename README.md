## SCSS Grid Helpers -- based on `display:grid`

[![NPM](https://nodei.co/npm/scss-next-grid.png?compact=true)](https://nodei.co/npm/scss-next-grid/)

### Example usage:
 
```scss 
// Create a grid with 3 equal columns
.element{
    @include grid(3)
}

// Create a 3 columns
// The grid has 2 fixed width columns and the middle column has flexible width
// Also set the gap between columns to 50px
.element{
    @include grid("200px 1fr 200px");
    @include gap(50px);
}
```
