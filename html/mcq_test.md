# HTML Questions and Answers

## Part 1: HTML Tags and Elements

### Q1. Which HTML tag creates a horizontal thematic break?

**Answer:** `<hr>`

**Explanation:** The `<hr>` tag represents a thematic break between sections of content. It is usually displayed as a horizontal line.

### Q2. Which tag is used to connect an external CSS file to an HTML document?

**Answer:** `<link>`

**Explanation:** The `<link>` tag is placed inside `<head>` and connects an external stylesheet.

Example: `<link rel="stylesheet" href="style.css">`

### Q3. Which element defines a term in a description list?

**Answer:** `<dt>`

**Explanation:** The `<dt>` tag defines the term or name in a description list.

### Q4. Which tag is used to display an image?

**Answer:** `<img>`

**Explanation:** The `<img>` tag embeds an image. The `src` attribute specifies the image path, and `alt` provides alternative text.

Example: `<img src="photo.jpg" alt="Photo">`

### Q5. Which attribute displays video controls such as play and pause?

**Answer:** `controls`

**Explanation:** The `controls` attribute displays built-in video controls.

Example: `<video controls src="video.mp4"></video>`

### Q6. Which HTML element is used to create a clickable button?

**Answer:** `<button>`

**Explanation:** The `<button>` element creates a clickable button that can perform actions or submit forms.

### Q7. Which element defines the description of a term in a description list?

**Answer:** `<dd>`

**Explanation:** The `<dd>` tag contains the description or definition of a term introduced by `<dt>`.

### Q8. Which HTML element is commonly used to group related content?

**Answer:** `<div>`

**Explanation:** The `<div>` element is a generic block-level container used to group elements for styling or layout. It has no special semantic meaning.

### Q9. Which element represents a date or time value?

**Answer:** `<time>`

**Explanation:** The `<time>` element represents a date or time in a machine-readable format when appropriate.

Example: `<time datetime="2026-10-17">October 17, 2026</time>`

### Q10. Which element groups the main body rows of a table?

**Answer:** `<tbody>`

**Explanation:** The `<tbody>` element groups the main data rows of an HTML table.

### Q11. Which element represents a scalar measurement within a known range?

**Answer:** `<meter>`

**Explanation:** The `<meter>` element represents a measurement within a defined range, such as disk usage or a score.

### Q12. Which attribute provides a tooltip-like advisory title for many elements?

**Answer:** `title`

**Explanation:** The `title` attribute provides additional advisory information, often displayed as a tooltip when the user hovers over an element.

### Q13. Which element groups self-contained media or content with an optional caption?

**Answer:** `<figure>`

**Explanation:** The `<figure>` element groups self-contained content, such as an image, diagram, or illustration. A `<figcaption>` element can provide its caption.

### Q14. Which attribute gives a form control its submission key?

**Answer:** `name`

**Explanation:** The `name` attribute identifies a form control when its data is submitted. The submitted data generally uses a name-value pair.

### Q15. Which element is a generic inline container with no special semantic meaning?

**Answer:** `<span>`

**Explanation:** The `<span>` element is an inline container commonly used to style or target a small part of text.

### Q16. Which semantic element is used for related thematic content?

**Answer:** `<section>`

**Explanation:** The `<section>` element groups thematically related content, usually with a heading.

### Q17. Which element creates a table header cell?

**Answer:** `<th>`

**Explanation:** The `<th>` element defines a header cell in an HTML table.

### Q18. Which element provides the visible label for a details disclosure widget?

**Answer:** `<summary>`

**Explanation:** The `<summary>` element provides the visible heading that users click to expand or collapse a `<details>` element.

### Q19. Which attribute stores custom data on an HTML element using the `data-` prefix?

**Answer:** `data-*`

**Explanation:** Custom data attributes store extra information on HTML elements.

Example: `<div data-id="10"></div>`

### Q20. Which element represents contact information for a person or organization?

**Answer:** `<address>`

**Explanation:** The `<address>` element represents contact information for the relevant person, organization, or content.

### Q21. Which input attribute specifies a regular expression the value must match?

**Answer:** `pattern`

**Explanation:** The `pattern` attribute specifies a regular expression used to validate an input's value.

Example: `<input pattern="[A-Za-z]+">`

### Q22. Which input type hides typed characters, commonly for passwords?

**Answer:** `type="password"`

**Explanation:** An input with `type="password"` masks the characters entered by the user.

Example: `<input type="password">`

### Q23. Which attribute specifies where form data is sent?

**Answer:** `action`

**Explanation:** The `action` attribute of a `<form>` specifies the URL where the form data is submitted.

Example: `<form action="/submit">`

### Q24. Which element represents a thematic break?

**Answer:** `<hr>`

**Explanation:** The `<hr>` element represents a thematic break between paragraphs or sections. It is the same element as the one used to create a horizontal thematic break.

### Q25. Which element is used to mark up a citation or title of a work?

**Answer:** `<cite>`

**Explanation:** The `<cite>` element identifies the title of a cited creative work, such as a book, film, or research paper.

### Q26. Which element is intended for a longer block quotation?

**Answer:** `<blockquote>`

**Explanation:** The `<blockquote>` element represents an extended quotation from another source.

### Q27. Which meta declaration helps a page adapt to the device width?

**Answer:** The viewport meta tag.

Example: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`

**Explanation:** It helps the browser set the page's viewport width to the device width, which is important for responsive web design.

### Q28. Which attribute connects a label to a control by matching the control's `id`?

**Answer:** `for`

**Explanation:** The `for` attribute of a `<label>` connects it to a form control whose `id` matches the attribute's value.

Example: `<label for="email">Email</label>`

### Q29. Which attribute on a script element loads a JavaScript file?

**Answer:** `src`

**Explanation:** The `src` attribute specifies the path to an external JavaScript file.

Example: `<script src="script.js"></script>`

### Q30. Which element creates a hyperlink?

**Answer:** `<a>`

**Explanation:** The `<a>` element creates a hyperlink. Its `href` attribute specifies the destination.

Example: `<a href="https://example.com">Visit</a>`

### Q31. Which attribute displays built-in audio or video controls?

**Answer:** `controls`

**Explanation:** The `controls` attribute displays built-in playback controls such as play, pause, and volume. It works with both `<audio>` and `<video>`.

### Q32. Which tag is used to display a block of code?

**Answer:** `<pre>` and `<code>` are commonly used together.

Example:

```html
<pre><code>print("Hello")</code></pre>
```

**Explanation:** `<code>` identifies computer code. `<pre>` preserves whitespace and line breaks, making the combination useful for displaying a formatted block of code.