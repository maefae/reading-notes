# 201 Reading Notes - Class 08: CSS Layout
This topic is important because 

# Reading Questions:
[Learn CSS - Flexbox](https://web.dev/learn/css/flexbox/)

1. Flexbox is designed for one-dimensional content. Explain what this means.
It excels at taking a bunch of one-dimensional items (paragraphs, etc.) which have different sizes, and returning the best layout for those items.

2. Explain the difference between the main axis and cross axis.
he main axis is the one set by your flex-direction property. If that is row your main axis is along the row, if it is column your main axis is along the column.

3. How can using certain properties of flexbox negatively impact accessibility?
You should be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The row-reverse and column-reverse values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.

[CSS Layout - Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

## Read up to “Flex-Flow Shorthand”

4. What are some advantages of using flexbox over float?


5. How does this topic connect with your long term goals?


## Bookmark and Review
[Learn CSS - Layout](https://web.dev/learn/css/layout/)

## Things I wanna know more about
