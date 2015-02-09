# flexbox-prefixes
Sass file with flexbox prefixes as mixins for Safari 

## Support 

Supports current and 1 back on Safari and browsers that support standard flexbox
CSS.

## Use

`+displayFlex()` will output the `display: flex`

`+flexDirection()` defaults to row, but you can pass in column as well 

`+flex()` requires a value to pass in, such as `+flex(1 0 auto)`

`+order()` requires an integer

`+justifyContent()` defaults to `flex-start` but can be passed other values

`+alignItems()` defaults to `flex-start` but can take other values

`+flexWrap()` defaults to `wrap` but can take other values
