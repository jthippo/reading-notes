# css-layout

#### Flexbox is designed for one-dimensional content. Explain what this means.

All elements exist on two axes (x and y) on a single layer i.e. actually 2D but easier to understand as one-dimensional.

#### Explain the difference between the main axis and cross axis.

The main axis is defined by _flex-direction_ which has four possible values: row, row-reverse, column, column-reverse. The cross axis runs perpendicular to the main axis, therefore if your _flex-direction_ is set to row or row-reverse the cross axis runs down the columns.

#### How can using certain properties of flexbox negatively impact accessibility?

The row-reverse and column-reverse reordering only happens for the visual order, not the logical order. Logical order is the order that a screen reader will read out the content.

#### What are some advantages of using flexbox over float?

- Vertically centering a block of content inside its parent
- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available
- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content

#### How does this topic connect with your long term goals?

It opens up a whole new world of CSS - if I'd been able to use it for my application "About Me" page it would have been much quicker and easier to build!
