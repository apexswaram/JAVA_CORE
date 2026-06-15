# CSS Complete Notes — Topics 1 to 50

> Prepared for JFS Batch students. Each topic includes: **Definition**, **HTML snippet**, and **Corresponding CSS**.

---

## 1. Color Property

**Definition:** The `color` property sets the text (foreground) color of an element.

```html
<p class="color-demo">This text is red.</p>
```

```css
.color-demo {
  color: red;
}
```

---

## 2. Background Color

**Definition:** The `background-color` property sets the background color of an element.

```html
<div class="bg-demo">Background Color Example</div>
```

```css
.bg-demo {
  background-color: yellow;
}
```

---

## 3. Font Family

**Definition:** The `font-family` property specifies the typeface used for text.

```html
<p class="font-family-demo">Times New Roman Font</p>
```

```css
.font-family-demo {
  font-family: 'Times New Roman';
}
```

---

## 4. Font Size

**Definition:** The `font-size` property controls the size of the text.

```html
<p class="font-size-demo">Font Size 30px</p>
```

```css
.font-size-demo {
  font-size: 30px;
}
```

---

## 5. Font Weight

**Definition:** The `font-weight` property controls the thickness/boldness of text.

```html
<p class="font-weight-demo">Bold Text Example</p>
```

```css
.font-weight-demo {
  font-weight: bold;
}
```

---

## 6. Font Style

**Definition:** The `font-style` property is mainly used to set italic text.

```html
<p class="font-style-demo">Italic Text Example</p>
```

```css
.font-style-demo {
  font-style: italic;
}
```

---

## 7. Text Align

**Definition:** The `text-align` property sets the horizontal alignment of text inside an element.

```html
<div class="text-align-demo">Centered Text</div>
```

```css
.text-align-demo {
  text-align: center;
}
```

---

## 8. Text Decoration

**Definition:** The `text-decoration` property adds or removes decoration lines from text (underline, overline, line-through, none).

```html
<p class="underline">Underline</p>
<p class="overline">Overline</p>
<p class="line-through">Line Through</p>
<a href="#" class="none">Link Without Underline</a>
```

```css
.underline {
  text-decoration: underline;
}
.overline {
  text-decoration: overline;
}
.line-through {
  text-decoration: line-through;
}
.none {
  text-decoration: none;
}
```

---

## 9. Text Transform

**Definition:** The `text-transform` property changes the capitalization of text (uppercase, lowercase, capitalize).

```html
<p class="uppercase">hello world</p>
<p class="lowercase">HELLO WORLD</p>
<p class="capitalize">hello world css</p>
```

```css
.uppercase {
  text-transform: uppercase;
}
.lowercase {
  text-transform: lowercase;
}
.capitalize {
  text-transform: capitalize;
}
```

---

## 10. Letter Spacing

**Definition:** The `letter-spacing` property controls the space between individual characters.

```html
<p class="letter-spacing-demo">LETTER SPACING</p>
```

```css
.letter-spacing-demo {
  letter-spacing: 5px;
}
```

---

## 11. Word Spacing

**Definition:** The `word-spacing` property controls the space between words.

```html
<p class="word-spacing-demo">Word Spacing Example</p>
```

```css
.word-spacing-demo {
  word-spacing: 15px;
}
```

---

## 12. Line Height

**Definition:** The `line-height` property sets the height of a line of text, affecting spacing between lines.

```html
<p class="line-height-demo">
  Line 1<br>
  Line 2<br>
  Line 3
</p>
```

```css
.line-height-demo {
  line-height: 3;
}
```

---

## 13. Border Property

**Definition:** The `border` property sets the width, style, and color of an element's border. Styles include solid, dotted, dashed, and double.

```html
<div class="border-demo">Solid Border</div>
<div class="dotted">Dotted Border</div>
<div class="dashed">Dashed Border</div>
<div class="double">Double Border</div>
```

```css
.border-demo {
  border: 3px solid red;
}
.dotted {
  border: 3px dotted blue;
}
.dashed {
  border: 3px dashed green;
}
.double {
  border: 5px double black;
}
```

---

## 14. Border Radius

**Definition:** The `border-radius` property rounds the corners of an element's border. A value of `50%` on an equal width/height element creates a circle.

```html
<div class="radius-demo">Rounded Corners</div>
<div class="circle">Circle</div>
```

```css
.radius-demo {
  border: 2px solid black;
  border-radius: 20px;
  padding: 20px;
}
.circle {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  background-color: lightblue;
  text-align: center;
  line-height: 150px;
}
```

---

## 15. Width and Height

**Definition:** The `width` and `height` properties set the dimensions of an element's content box.

```html
<div class="size-demo">300 x 100</div>
```

```css
.size-demo {
  width: 300px;
  height: 100px;
  background-color: lightgreen;
}
```

---

## 16. Padding

**Definition:** The `padding` property creates space *inside* an element, between its content and its border.

```html
<div class="padding-demo">Padding Creates Space Inside Border</div>
```

```css
.padding-demo {
  border: 2px solid black;
  padding: 30px;
}
```

---

## 17. Margin

**Definition:** The `margin` property creates space *outside* an element, between its border and neighboring elements.

```html
<div class="margin-demo">Margin Creates Space Outside Border</div>
```

```css
.margin-demo {
  border: 2px solid red;
  margin: 40px;
}
```

---

## 18. Box Shadow

**Definition:** The `box-shadow` property adds a shadow effect around an element's frame.

```html
<div class="shadow-demo">Shadow Effect</div>
```

```css
.shadow-demo {
  padding: 20px;
  box-shadow: 0px 0px 15px gray;
}
```

---

## 19. Cursor Property

**Definition:** The `cursor` property sets the type of mouse cursor shown when hovering over an element.

```html
<button class="cursor-demo-1">Hover Mouse Here</button>
```

```css
.cursor-demo-1 {
  cursor: pointer;
}
```

---

## 20. Opacity

**Definition:** The `opacity` property sets the transparency level of an element (0 = fully transparent, 1 = fully opaque).

```html
<div class="opacity-demo">Opacity 0.5 Example</div>
```

```css
.opacity-demo {
  opacity: 0.5;
}
```

---

## 21. Display Property

**Definition:** The `display` property defines how an element is rendered in the document flow — `inline` (no line break, only content width), `block` (full width, line break before/after), or `inline-block` (sits inline but can have width/height).

```html
<span class="inline">Inline</span>
<span class="inline">Inline</span>

<div class="block">Block Element</div>

<div class="inline-block">Inline Block</div>
```

```css
.inline {
  display: inline;
  background: yellow;
}
.block {
  display: block;
  background: lightblue;
}
.inline-block {
  display: inline-block;
  background: lightgreen;
  width: 150px;
}
```

---

## 22. Hover Effect

**Definition:** The `:hover` pseudo-class applies styles when the user places the mouse pointer over an element.

```html
<button class="hover-btn">Hover Me</button>
```

```css
.hover-btn {
  padding: 10px 20px;
  border: none;
  background-color: blue;
  color: white;
}
.hover-btn:hover {
  background-color: red;
}
```

---

## 23. CSS Box Model

**Definition:** The Box Model describes how every HTML element is structured: **Content** (actual content) → **Padding** (space inside border) → **Border** (the border line) → **Margin** (space outside border).

```html
<div class="box-model">Content Area</div>
<p>
  Margin → Outside Space<br>
  Border → Border Area<br>
  Padding → Inside Space<br>
  Content → Actual Content
</p>
```

```css
.box-model {
  margin: 20px;
  border: 5px solid red;
  padding: 30px;
  background-color: lightyellow;
}
```

---

## 24. Inline CSS

**Definition:** Inline CSS is written directly inside an HTML tag using the `style` attribute. It applies only to that single element and has the highest priority among the three CSS types.

```html
<p style="color:purple; font-weight:bold;">
  This text is styled using Inline CSS.
</p>
```

```css
/* No separate CSS file/block needed —
   styles are written directly in the style="" attribute */
```

---

## 25. Internal CSS

**Definition:** Internal CSS is written inside a `<style>` tag in the `<head>` section of an HTML document. It applies to all matching elements within that single page only.

```html
<head>
  <style>
    .font-weight-demo {
      font-weight: bold;
    }
  </style>
</head>
<body>
  <p class="font-weight-demo">Styled using Internal CSS</p>
</body>
```

```css
/* This entire block, placed inside <head><style>...</style></head>,
   is an example of Internal CSS */
.font-weight-demo {
  font-weight: bold;
}
```

---

## 26. Text Shadow

**Definition:** The `text-shadow` property adds a shadow effect to text. Syntax: `horizontal-offset vertical-offset blur-radius color`.

```html
<h3 class="text-shadow-demo">Shadow Text Example</h3>
```

```css
.text-shadow-demo {
  text-shadow: 2px 2px 5px gray;
}
```

---

## 27. Background Image

**Definition:** The `background-image` property sets an image (or gradient) as the background of an element.

```html
<div class="bg-image-demo">Background Image Area</div>
```

```css
.bg-image-demo {
  height: 150px;
  background-image: linear-gradient(to right, lightblue, lightgreen);
}
```

---

## 28. List Style

**Definition:** The `list-style-type` property defines the marker style (bullet shape) for list items.

```html
<ul class="list-demo">
  <li>HTML</li>
  <li>CSS</li>
</ul>
```

```css
.list-demo {
  list-style-type: square;
}
```

---

## 29. Overflow

**Definition:** The `overflow` property controls what happens when content is too big to fit inside its box. Values: `visible`, `hidden`, `scroll`, `auto`.

```html
<div class="overflow-demo">
  Overflow example Overflow example Overflow example Overflow example
</div>
```

```css
.overflow-demo {
  width: 250px;
  height: 80px;
  overflow: scroll;
  border: 1px solid black;
}
```

---

## 30. Max Width

**Definition:** The `max-width` property sets the maximum width an element can grow to, even if its container is larger.

```html
<div class="max-width-demo">Max Width Example</div>
```

```css
.max-width-demo {
  max-width: 400px;
  background: lightyellow;
  padding: 10px;
}
```

---

## 31. Min Width

**Definition:** The `min-width` property sets the minimum width an element must maintain, even if its content is smaller.

```html
<div class="min-width-demo">Min Width Example</div>
```

```css
.min-width-demo {
  min-width: 300px;
  background: lightblue;
  padding: 10px;
}
```

---

## 32. Max Height

**Definition:** The `max-height` property sets the maximum height an element can grow to. If content exceeds it, `overflow` controls how it's handled.

```html
<div class="max-height-demo">
  Line1<br>Line2<br>Line3<br>Line4<br>Line5
</div>
```

```css
.max-height-demo {
  max-height: 60px;
  overflow: auto;
  border: 1px solid black;
}
```

---

## 33. Min Height

**Definition:** The `min-height` property sets the minimum height an element must maintain.

```html
<div class="min-height-demo">Min Height Example</div>
```

```css
.min-height-demo {
  min-height: 100px;
  background: #eee;
}
```

---

## 34. Visibility

**Definition:** The `visibility` property hides an element, but unlike `display: none`, the element still takes up space in the layout.

```html
<p class="visibility-demo">Hidden Text</p>
<p>Space remains.</p>
```

```css
.visibility-demo {
  visibility: hidden;
}
```

---

## 35. Outline

**Definition:** The `outline` property draws a line around an element, outside the border. It does not affect layout/spacing like border does.

```html
<div class="outline-demo">Outline Example</div>
```

```css
.outline-demo {
  outline: 3px solid red;
  padding: 10px;
}
```

---

## 36. CSS Units

**Definition:** CSS units define measurement values. `rem` is relative to the root element's font size, making it useful for scalable/responsive design.

```html
<p class="units-demo">2rem Example</p>
```

```css
.units-demo {
  font-size: 2rem;
}
```

---

## 37. Cursor Types

**Definition:** The `cursor` property can take many values to change the mouse pointer shape — e.g. `crosshair`, `pointer`, `move`, `not-allowed`.

```html
<div class="cursor-demo">Move mouse here</div>
```

```css
.cursor-demo {
  cursor: crosshair;
}
```

---

## 38. Multiple Classes

**Definition:** An HTML element can have more than one class. CSS rules for all listed classes are applied together (combined).

```html
<p class="red bold">Red and Bold</p>
```

```css
.red {
  color: red;
}
.bold {
  font-weight: bold;
}
```

---

## 39. CSS Comments

**Definition:** Comments in CSS are written between `/* */`. They are ignored by the browser and used to explain code.

```html
<p>Use /* comment */ in CSS</p>
```

```css
/* This is a CSS comment.
   It does not affect the styling. */
p {
  color: black; /* sets text color */
}
```

---

## 40. Universal Selector

**Definition:** The `*` (universal selector) targets **all** elements on the page. Commonly used for resets (e.g. removing default margin/padding).

```html
<p>* selector targets all elements.</p>
```

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

---

## 41. Group Selector

**Definition:** A group selector applies the same CSS rule to multiple selectors at once, separated by commas.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
```

```css
h1, h2, h3 {
  color: blue;
}
```

---

## 42. Attribute Selector

**Definition:** An attribute selector targets elements based on the presence or value of an HTML attribute. Syntax: `element[attribute=value]`.

```html
<input type="text" placeholder="Text Input">
```

```css
input[type="text"] {
  background: #ffffcc;
}
```

---

## 43. Child Selector

**Definition:** The child selector (`>`) targets only the **direct children** of an element, not deeper descendants.

```html
<div class="child-demo">
  <p>Direct Child</p>
</div>
```

```css
.child-demo > p {
  color: red;
}
```

---

## 44. Descendant Selector

**Definition:** The descendant selector (space between selectors) targets **all** elements nested inside another element, at any depth.

```html
<div class="desc-demo">
  <div>
    <p>Descendant Paragraph</p>
  </div>
</div>
```

```css
.desc-demo p {
  font-style: italic;
}
```

---

## 45. Link States

**Definition:** Pseudo-classes like `:hover`, `:visited`, `:active`, `:link` style hyperlinks based on their state.

```html
<a href="#" class="link-demo">Hover Link</a>
```

```css
.link-demo:hover {
  color: red;
}
```

---

## 46. Table Styling

**Definition:** `border-collapse` merges table cell borders into a single border. `th` and `td` can be styled individually for headers and data cells.

```html
<table>
  <tr>
    <th>Name</th>
    <th>Skill</th>
  </tr>
  <tr>
    <td>Mahesh</td>
    <td>CSS</td>
  </tr>
</table>
```

```css
table {
  border-collapse: collapse;
}
th, td {
  border: 1px solid black;
  padding: 8px;
}
th {
  background: lightblue;
}
```

---

## 47. Form Styling

**Definition:** Form elements like `<input>` can be styled using descendant selectors to add padding, margin, borders, etc.

```html
<form class="form-demo">
  <input placeholder="Name">
</form>
```

```css
.form-demo input {
  padding: 8px;
  margin: 5px;
}
```

---

## 48. Image Styling

**Definition:** Images can be styled like any other element — setting `width`, and using `border-radius: 50%` to create a circular image.

```html
<img class="img-demo" src="https://via.placeholder.com/120">
```

```css
.img-demo {
  width: 120px;
  border-radius: 50%;
}
```

---

## 49. Transition

**Definition:** The `transition` property animates changes to CSS property values smoothly over a specified duration, instead of changing instantly.

```html
<button class="transition-btn">Hover Me</button>
```

```css
.transition-btn {
  padding: 10px;
  transition: 0.4s;
}
.transition-btn:hover {
  background: red;
  color: white;
}
```

---

## 50. Transform

**Definition:** The `transform` property applies 2D/3D transformations like `scale()`, `rotate()`, `translate()` to an element.

```html
<div class="transform-box">Hover Scale</div>
```

```css
.transform-box {
  display: inline-block;
  padding: 15px;
  background: lightgreen;
}
.transform-box:hover {
  transform: scale(1.2);
}
```

---

## Quick Reference Table

| # | Topic | Property/Concept |
|---|-------|-------------------|
| 1 | Color | `color` |
| 2 | Background Color | `background-color` |
| 3 | Font Family | `font-family` |
| 4 | Font Size | `font-size` |
| 5 | Font Weight | `font-weight` |
| 6 | Font Style | `font-style` |
| 7 | Text Align | `text-align` |
| 8 | Text Decoration | `text-decoration` |
| 9 | Text Transform | `text-transform` |
| 10 | Letter Spacing | `letter-spacing` |
| 11 | Word Spacing | `word-spacing` |
| 12 | Line Height | `line-height` |
| 13 | Border | `border` |
| 14 | Border Radius | `border-radius` |
| 15 | Width & Height | `width`, `height` |
| 16 | Padding | `padding` |
| 17 | Margin | `margin` |
| 18 | Box Shadow | `box-shadow` |
| 19 | Cursor | `cursor: pointer` |
| 20 | Opacity | `opacity` |
| 21 | Display | `display: inline/block/inline-block` |
| 22 | Hover Effect | `:hover` |
| 23 | Box Model | margin → border → padding → content |
| 24 | Inline CSS | `style=""` attribute |
| 25 | Internal CSS | `<style>` in `<head>` |
| 26 | Text Shadow | `text-shadow` |
| 27 | Background Image | `background-image` |
| 28 | List Style | `list-style-type` |
| 29 | Overflow | `overflow` |
| 30 | Max Width | `max-width` |
| 31 | Min Width | `min-width` |
| 32 | Max Height | `max-height` |
| 33 | Min Height | `min-height` |
| 34 | Visibility | `visibility` |
| 35 | Outline | `outline` |
| 36 | CSS Units | `rem`, `px`, `%`, etc. |
| 37 | Cursor Types | `cursor: crosshair`, etc. |
| 38 | Multiple Classes | `class="a b"` |
| 39 | CSS Comments | `/* comment */` |
| 40 | Universal Selector | `*` |
| 41 | Group Selector | `h1, h2, h3 { }` |
| 42 | Attribute Selector | `input[type="text"]` |
| 43 | Child Selector | `parent > child` |
| 44 | Descendant Selector | `parent child` |
| 45 | Link States | `:hover`, `:visited`, `:active` |
| 46 | Table Styling | `border-collapse`, `th`, `td` |
| 47 | Form Styling | `.form-demo input` |
| 48 | Image Styling | `width`, `border-radius: 50%` |
| 49 | Transition | `transition` |
| 50 | Transform | `transform: scale()`, `rotate()` |
