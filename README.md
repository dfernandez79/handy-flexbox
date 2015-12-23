# handy-flexbox

Handy flexbox CSS classes, for easier HTML layouts.

## Installation

Include the `handy-flexbox.css` in your styles. There are multiple ways to get the CSS file:

[NPM](http://www.npmjs.org/):
```
npm install handy-flexbox
```

[Bower](http://bower.io/):
```
bower install dfernandez79/handy-flexbox
```

Download from GitHub:
```
curl -L -O https://raw.githubusercontent.com/dfernandez79/handy-flexbox/master/handy-flexbox.css
```

## CSS Class Reference

### Flex containers

Class       | Description
----------  | -----------
flex-row    | Container using display flex, and row direction.
flex-column | Container using display flex, and column direction.

### Item size

Class       | Description
----------  | -----------
flex-auto   | Uses `flex: auto`.
flex-none   | Uses `flex: none`.
flex-grow   | Uses `flex: 1 0 auto` (like auto, but doesn't shrink the item bellow the base width).

### Item alignment

Class                 | Description
--------------------- | -------------------------------
flex-align-center     | Uses `align-items: center`.
flex-align-start      | Uses `align-items: flex-start`.
flex-align-end        | Uses `align-items: flex-end`.
flex-align-baseline   | Uses `align-items: baseline`.

### Item justification

Class                      | Description
-------------------------- | -------------------------------
flex-justify-start         | Uses `justify-content: flex-start`.
flex-justify-end           | Uses `justify-content: flex-end`.
flex-justify-center        | Uses `justify-content: center`.
flex-justify-space-between | Uses `justify-content: space-between`.
flex-justify-space-around  | Uses `justify-content: space-around`.
flex-wrap                  | Uses `flex-wrap: wrap`
