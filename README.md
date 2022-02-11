# FloatAssignment1

Assignment: Clone the given layout by only using Floats. Flexbox and Grid are not allowed.

Purpose of the assignment: To become more fluent in the box model, float property, and having DRY code. 

Reflection: Ultimately, I was floating my items by treating them like flex items in flexbox. I achieved this by labeling sections and articles with attributes such as "box1, box2, box3, article1,article2..." and so on. This has allowed me to provide borders to specific items based on their location on the page in order to mimic the "gap" property used in flexbox and grid. I also practiced using the "em" and "rem" units when creating my font-sizes in order to make the website more scalable when editing media queries for the layout to be viewed in smaller devices. 

This layout was made to been seen on devices with 1080 height x 1900 width +. Any smaller, the site begins to break. In order to solve this I would:
- provide media queries right before the page breaks 
- display: none on some of the nav links
- edit the root font-size because the font-size in all elements are in "em" and "rem"
- remove floats/change the width percentage of the section and boxes so they stack on top of each other instead of next to each other
