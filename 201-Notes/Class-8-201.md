# Class 8 Reading Notes

These readings dive into positioning elements in CSS using flexbox.  Flexbox has many advantages over other forms of positioning which are detailed here.

## Learn CSS - Flexbox

- Flexbox is designed for one-dimensional content.  Explain what this means.

> This means that it will take items that have different sizes, and return the best layout for those items, given the constraints of the viewport.

- Explain the difference between the main axis and the cross axis.

> Flex items move as a group along the main axis.  The cross axis is perpendicular to the main axis.  You can move items individually or as a group along the cross axis.  The main axis is defined using the flex-direction property.

- How can using certain properties of flexbox negatively impact accessibility?

> If using row-reverse or column reverse, the reordering only happens visually.  A screen reader would still read the content in the logical order, not the visual order so it would be the opposite experience for a user using a screen reader.

## CSS Layout - Flexbox

- What are some advantages of using flexbox over float?

> It is very difficult to do layouts using floats and positioning.  Flexbox makes it much easier to do things like centering content inside of its parent, making children take up an equal amount of space, or making columns in a multiple column layout the same height.

- How does this topic connect with your long term goals?

> This topic connects with my long term goals because I want to be well rounded even if I don't see myself as a web designer.  These concepts can be applied to any visual interface that is created for things like apps or documentation.  Making layouts look good helps both aesthetically and with usability.

## Things I want to know more about

- What is the most common layout method to use when designing for mobile applications?
