# CSS Questions and Answers

## Part 1: CSS Selectors and Specificity

### Q1. What is the specificity of a type selector such as `div`?

**Answer:** `0-0-1` (one type selector).

**Explanation:** Type selectors have lower specificity than class selectors and ID selectors. In the common four-part notation, the value is `0-0-0-1`.

### Q2. Which pseudo-class selects a checked checkbox or radio button?

**Answer:** `:checked`

**Explanation:** The `:checked` pseudo-class selects checked checkboxes, radio buttons, and selected options where applicable.

### Q3. Which selector selects every `<p>` element that is a direct child of a `<div>`?

**Answer:** `div > p`

**Explanation:** The `>` combinator selects only direct children, not deeper descendants.

### Q4. What does the selector `div p` select?

**Answer:** All `<p>` elements that are descendants of a `<div>`.

**Explanation:** The space between selectors is the descendant combinator. It selects matching elements at any nesting depth.

### Q5. Which pseudo-class targets an element when it is the only child of its parent?

**Answer:** `:only-child`

**Explanation:** It selects an element that has no sibling elements within its parent.

### Q6. Which selector targets every `<p>` element?

**Answer:** `p`

**Explanation:** `p` is a type selector that selects all paragraph elements.

### Q7. Which selector has the lowest specificity?

**Answer:** The universal selector `*` has zero specificity.

**Explanation:** The universal selector matches all elements but contributes nothing to specificity. In general, inline styles, IDs, classes/attributes/pseudo-classes, and type selectors have progressively lower specificity.

### Q8. Which pseudo-class selects an element that has no children, including no text nodes?

**Answer:** `:empty`

**Explanation:** The `:empty` pseudo-class selects elements that have no child elements or text nodes. Whitespace text nodes also count as content.

### Q9. Which selector groups `h1` and `h2` under the same declarations?

**Answer:** `h1, h2`

**Explanation:** A comma separates selectors in a selector list, allowing the same CSS declarations to apply to both headings.

## Part 2: Overflow, Positioning and Layout

### Q10. Which overflow value hides content that extends outside the element?

**Answer:** `overflow: hidden`

**Explanation:** It clips overflowing content and does not show scrollbars for that overflow.

### Q11. Which CSS property controls whether overflowing content is clipped or scrollable?

**Answer:** `overflow`

**Explanation:** The `overflow` property controls how content outside an element's box is handled. Common values include `visible`, `hidden`, `scroll`, and `auto`.

### Q12. Which position value positions an element relative to the viewport?

**Answer:** `position: fixed`

**Explanation:** A fixed element is normally positioned relative to the viewport and remains in place when the page scrolls. Certain ancestor properties can change its containing block.

### Q13. Which position value removes an element from the normal document flow and positions it relative to a containing block?

**Answer:** `position: absolute`

**Explanation:** An absolutely positioned element is removed from normal flow and is positioned relative to its containing block, often established by a positioned ancestor.

### Q14. Which CSS property adds space between flex or grid items?

**Answer:** `gap`

**Explanation:** The `gap` property adds spacing between rows and/or columns in flex and grid layouts.

### Q15. Which property is used to move an element to the left or right and allow content to wrap around it?

**Answer:** `float`

**Explanation:** The `float` property moves an element to the left or right, allowing surrounding inline content to wrap around it.

### Q16. Which CSS property controls how an element is rendered in the layout?

**Answer:** `display`

**Explanation:** The `display` property determines the element's layout behavior, such as `block`, `inline`, `flex`, or `grid`.

### Q17. Which CSS property controls whether flex items move onto multiple lines?

**Answer:** `flex-wrap`

**Explanation:** `flex-wrap: wrap` allows flex items to move onto additional lines when necessary.

### Q18. Which CSS position value keeps an element in the normal document flow while allowing top, right, bottom, and left adjustments?

**Answer:** `position: relative`

**Explanation:** A relatively positioned element remains in normal flow and can be visually offset from its original position.

### Q19. Which CSS position value keeps an element in the normal document flow and offsets it relative to its usual position?

**Answer:** `position: relative`

**Explanation:** Relative positioning preserves the element's original space in the layout.

### Q20. Which position value normally fixes an element relative to the viewport?

**Answer:** `position: fixed`

**Explanation:** Fixed positioning normally keeps the element in the same viewport position while scrolling.

### Q21. Which property controls the alignment of flex items on the cross axis individually?

**Answer:** `align-self`

**Explanation:** `align-self` overrides the container's `align-items` setting for an individual flex item.

### Q22. Which property sets a flex container's items to wrap in reverse cross-axis order?

**Answer:** `flex-wrap: wrap-reverse`

**Explanation:** `wrap-reverse` creates additional flex lines in the reverse cross-axis direction.

### Q23. Which property aligns multiple flex lines along the cross axis when there is extra cross-axis space?

**Answer:** `align-content`

**Explanation:** `align-content` controls the spacing and alignment of multiple flex lines. It is useful when a flex container has extra cross-axis space.

### Q24. Which flex property allows an item to take a share of positive free space?

**Answer:** `flex-grow`

**Explanation:** `flex-grow` specifies how much a flex item can grow relative to other items when extra space is available.

### Q25. Which flex property sets the main axis direction?

**Answer:** `flex-direction`

**Explanation:** Common values include `row`, `row-reverse`, `column`, and `column-reverse`.

### Q26. Which display value makes the element itself inline while its children use flex layout?

**Answer:** `display: inline-flex`

**Explanation:** `inline-flex` makes the container behave like an inline-level element while its children are laid out using Flexbox.

### Q27. Which display value lets an element flow inline while accepting width and height?

**Answer:** `display: inline-block`

**Explanation:** An inline-block element flows alongside inline content but can have its own width, height, padding, and margins.

### Q28. Which CSS property changes the visual order of flex items without changing source order?

**Answer:** `order`

**Explanation:** The `order` property changes the visual ordering of flex items without changing their order in the HTML source.

## Part 3: Text and Fonts

### Q29. Which CSS property controls whether text can be selected by the user?

**Answer:** `user-select`

**Explanation:** For example, `user-select: none` prevents ordinary text selection through user interaction.

### Q30. Which CSS property can change the mouse cursor when it is over an element?

**Answer:** `cursor`

**Explanation:** Example: `cursor: pointer` displays a pointer cursor, commonly used for clickable elements.

### Q31. Which CSS property controls the spacing between words?

**Answer:** `word-spacing`

**Explanation:** `word-spacing` adjusts the space between words in a line of text.

### Q32. Which CSS property is used to change text to uppercase, lowercase, or capitalize it?

**Answer:** `text-transform`

**Explanation:** Common values include `uppercase`, `lowercase`, and `capitalize`.

### Q33. Which CSS property controls the spacing between lines of text?

**Answer:** `line-height`

**Explanation:** `line-height` controls the height of a line box and helps determine the vertical spacing between lines of text.

### Q34. Which CSS property is used to change text to uppercase, lowercase, or title case?

**Answer:** `text-transform`

**Explanation:** It can change the displayed capitalization without changing the original text in the HTML.

### Q35. Which property specifies the space between words?

**Answer:** `word-spacing`

**Explanation:** It adjusts the spacing between words, not the spacing between individual letters. `letter-spacing` controls the latter.

### Q36. Which property determines whether an element's text can be selected by the user?

**Answer:** `user-select`

**Explanation:** It controls whether the user can select text through normal selection interactions.

### Q37. Which unit is relative to the font size of the current element?

**Answer:** `em`

**Explanation:** For font sizes and many other properties, `1em` is based on the computed font size of the relevant element. By contrast, `rem` is based on the root element's font size.

## Part 4: Backgrounds, Borders and Visual Effects

### Q38. Which value prevents a background image from repeating?

**Answer:** `background-repeat: no-repeat`

**Explanation:** The `no-repeat` value displays the background image without tiling it.

### Q39. Which value makes a background image fit inside the container while maintaining its aspect ratio?

**Answer:** `background-size: contain`

**Explanation:** `contain` scales the image so the entire image fits inside the container without changing its aspect ratio. Empty space may remain.

### Q40. Which property is used to create rounded corners?

**Answer:** `border-radius`

**Explanation:** `border-radius` rounds an element's corners.

Example: `border-radius: 10px;`

### Q41. Which CSS property is used to set an image as a background?

**Answer:** `background-image`

**Explanation:** Example: `background-image: url("image.jpg");`

### Q42. Which property applies visual effects such as blur or grayscale?

**Answer:** `filter`

**Explanation:** Examples include `filter: blur(5px)` and `filter: grayscale(100%)`.

### Q43. Which property sets how a background image is sized?

**Answer:** `background-size`

**Explanation:** Common values include `cover`, `contain`, and explicit dimensions.

### Q44. Which property rotates, scales, translates, or skews an element?

**Answer:** `transform`

**Explanation:** Functions include `rotate()`, `scale()`, `translate()`, and `skew()`.

## Part 5: Box Model and Visibility

### Q45. What does `padding: 10px 20px 30px 40px` mean?

**Answer:**
- Top: `10px`
- Right: `20px`
- Bottom: `30px`
- Left: `40px`

**Explanation:** Four-value padding shorthand follows the order **top, right, bottom, left** (clockwise).

### Q46. Which CSS property can control whether an element is visible while still occupying space?

**Answer:** `visibility`

**Explanation:** `visibility: hidden` hides an element but preserves its layout space. By contrast, `display: none` removes it from the layout.

### Q47. By default, which box-sizing value is used by browsers?

**Answer:** `content-box`

**Explanation:** With `content-box`, the specified `width` and `height` apply to the content box. Padding and borders are added outside those dimensions.

### Q48. In the default content-box model, what does `width` normally measure?

**Answer:** The content width.

**Explanation:** The specified width excludes padding and borders. The total rendered width also includes horizontal padding and borders, and may include margins outside the border box.

## Part 6: Responsive Design and Sizing

### Q49. Which CSS property can prevent a long word from overflowing by allowing breaks within it?

**Answer:** `overflow-wrap`

**Explanation:** `overflow-wrap: anywhere` allows long words or strings to break when needed to prevent overflow.

### Q50. Which CSS property controls whether flex items move onto multiple lines?

**Answer:** `flex-wrap`

**Explanation:** `flex-wrap: wrap` lets items continue on a new line when they do not fit on the current line.

## Part 7: Animation and Interaction

### Q51. Which property defines the keyframes animation an element should use?

**Answer:** `animation-name`

**Explanation:** It specifies the name of the `@keyframes` animation to apply.

Example:

```css
.box {
    animation-name: move;
}

@keyframes move {
    from { transform: translateX(0); }
    to { transform: translateX(100px); }
}
```

### Q52. Which property can preserve an animation's final keyframe styles after it ends?

**Answer:** `animation-fill-mode`

**Explanation:** `animation-fill-mode: forwards` preserves the styles from the final keyframe after the animation finishes.

### Q53. Which property can disable pointer interaction with an element?

**Answer:** `pointer-events`

**Explanation:** `pointer-events: none` prevents the element from being the target of pointer events. It does not automatically disable keyboard interaction.

## Part 8: Quick Revision of Repeated Concepts

### Q54. Which CSS property controls whether overflowing content is clipped or scrollable?

**Answer:** `overflow`

**Explanation:** It determines how content that exceeds an element's box is handled.

### Q55. Which property changes text to uppercase, lowercase, or title case?

**Answer:** `text-transform`

**Explanation:** It changes the visual capitalization of text.

### Q56. Which property specifies the space between words?

**Answer:** `word-spacing`

**Explanation:** It changes the amount of spacing between words.

### Q57. Which property determines whether an element's text can be selected by the user?

**Answer:** `user-select`

**Explanation:** It controls normal user text-selection behavior.