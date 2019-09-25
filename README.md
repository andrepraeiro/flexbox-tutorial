# FlexBox Course

## Introduction

based on android layout

## Lesson #1

- use `display: flex` to activate flexbox

### flex-direction

- row (default): Children items will be positioned in a row.
- column: Children items will be positioned in a column.
- row-reverse: Children items will be positioned in a row, but will start on right side.
- column-reverse: Children items will be positioned in a column, but will start on the bottom side. To tihs happen, it's necessary to maake html and body use height: 100%.

## Lesson #2

### align-items and justify-content

- If flex-direction is equal row, align-items will align children elements on vertical position and justify-content will align children items in horizontal position.

- If flex-direction is equal column, align-items will align children elements on horizontal position and justify-content will align children items in vertical position.

#### Values if flex-direction is row

##### flex-start

Default value. Define items will positioned at the start of the parent.

##### flex-end

Define items will positioned at the end of the parent.

##### center

Define items will positioned at the center of the parent.

##### Other values for justify-content

###### space-between

Split the children elements in equal spaces between them, except in the first and last elements.

###### space-around

Split the children elements in equal spaces between them, include the first and last elements.

#### Values if flex-direction is column

Same values of flex-direction is row, but then behaviour is based in inverted axis.

## Lesson #3 - Resizing

### flex-grow

- if equal 1 (default ) allow to grow all the children elements to fit in container.
- if equal 0 don't allow to grow all the children elements to fit in container.

### flex-shrink

- if equal 1 (default) allow to shrink all the children elements to fit in container.
- if equal 0 dont allow to shrink all the children elements to fit in container.

### flex

- Unify flex-grow and flex-shrink in one attribute.
- `flex: 1 0;` will set flex-grow: 1 and flex-shrink: 0
