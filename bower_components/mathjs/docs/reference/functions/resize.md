# Function resize

Resize a matrix


## Syntax

```js
math.resize(x, size)
math.resize(x, size, defaultValue)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | * &#124; Array &#124; Matrix | Matrix to be resized
`size` | Array &#124; Matrix | One dimensional array with numbers
`defaultValue` | Number &#124; String | Undefined by default, except in case of a string, in that case defaultValue = ' '

### Returns

Type | Description
---- | -----------
* &#124; Array &#124; Matrix | A resized clone of matrix `x`


## Examples

```js
math.resize([1, 2, 3, 4, 5], [3]); // returns Array  [1, 2, 3]
math.resize([1, 2, 3], [5], 0);    // returns Array  [1, 2, 3, 0, 0]
math.resize(2, [2, 3], 0);         // returns Matrix [[2, 0, 0], [0, 0, 0]]
math.resize("hello", [8], "!");    // returns String 'hello!!!'
```


## See also

[size](size.md),
[squeeze](squeeze.md),
[subset](subset.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->