
# Responsive Web Design Using Bootstrap 12-Column Grid System

## Introduction

Nowadays users access websites from different devices such as:

* Mobile Phones
* Tablets
* Laptops
* Desktop Computers
* Smart TVs

A website should automatically adjust its layout according to the screen size of the device.

This concept is called:

### Responsive Web Design

### Definition

Responsive Web Design is a technique used to make websites automatically adapt to different screen sizes and resolutions.

---

# Why Responsive Design?

Imagine creating a website on a laptop.

When opened on a mobile phone:

* Text becomes very small
* Images overflow outside the screen
* Horizontal scrolling appears
* Poor user experience

Responsive Design solves these problems by adjusting layouts based on device size.

---

# Viewport Meta Tag

Before creating responsive websites, always include:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### Purpose

* Matches website width to device width
* Enables proper responsive behavior
* Essential for mobile devices

---

# Bootstrap and Responsive Design

Bootstrap provides a responsive 12-column grid system.

Instead of writing complex CSS media queries manually, Bootstrap provides ready-made classes.

Examples:

```html
col-6
col-md-4
col-lg-3
```

These classes automatically change layout according to screen size.

---

# Bootstrap Setup

Include Bootstrap CSS inside the head section.

```html
<link rel="stylesheet"
href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css">
```

Include Bootstrap JavaScript before closing body tag.

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js"></script>
```

---

# Bootstrap Grid System

Bootstrap divides every row into 12 equal columns.

Visual Representation:

|1|2|3|4|5|6|7|8|9|10|11|12|

Think of it like a pizza divided into 12 slices.

Every row has a total of 12 columns.

---

# Grid Formula

```text
Total Columns = 12
```

Examples:

```text
6 + 6 = 12
```

```text
4 + 4 + 4 = 12
```

```text
3 + 3 + 3 + 3 = 12
```

```text
5 + 5 + 2 = 12
```

```text
7 + 3 + 2 = 12
```

---

# Bootstrap Structure

Always follow:

```html
Container
   ↓
Row
   ↓
Column
```

Example:

```html
<div class="container">
    <div class="row">
        <div class="col-6">
            Left
        </div>

        <div class="col-6">
            Right
        </div>
    </div>
</div>
```

---

# Understanding Column Widths

```text
col-12 = 100%
col-6  = 50%
col-4  = 33.33%
col-3  = 25%
col-2  = 16.66%
col-1  = 8.33%
```

---

# Example 1: Two Equal Sections

```html
<div class="row container1">

    <div class="col-6 green">
        left
    </div>

    <div class="col-6 red">
        right
    </div>

</div>
```

Calculation:

```text
6 + 6 = 12
```

Output:

```text
Left | Right
```

---

# Example 2: Three Equal Sections

```html
<div class="row container1">

    <div class="col-4 green">
        Container 1
    </div>

    <div class="col-4 red">
        Container 2
    </div>

    <div class="col-4 green">
        Container 3
    </div>

</div>
```

Calculation:

```text
4 + 4 + 4 = 12
```

---

# Example 3: Four Equal Sections

```html
<div class="row container1">

    <div class="col-3 green">
        Container 1
    </div>

    <div class="col-3 red">
        Container 2
    </div>

    <div class="col-3 green">
        Container 3
    </div>

    <div class="col-3 red">
        Container 4
    </div>

</div>
```

Calculation:

```text
3 + 3 + 3 + 3 = 12
```

---

# Example 4

```html
<div class="row container1">

    <div class="col-5 green">
        Container 1
    </div>

    <div class="col-5 red">
        Container 2
    </div>

    <div class="col-2 green">
        Container 3
    </div>

</div>
```

Calculation:

```text
5 + 5 + 2 = 12
```

---

# Example 5

```html
<div class="row container1">

    <div class="col-7 green">
        Container 1
    </div>

    <div class="col-3 red">
        Container 2
    </div>

    <div class="col-2 green">
        Container 3
    </div>

</div>
```

Calculation:

```text
7 + 3 + 2 = 12
```

---

# Bootstrap Breakpoints

Bootstrap provides different breakpoints for different screen sizes.

| Class   | Screen Size | Device             |
| ------- | ----------- | ------------------ |
| col     | All Devices | Mobile             |
| col-sm  | >= 576px    | Tablet             |
| col-md  | >= 768px    | Laptop             |
| col-lg  | >= 992px    | Desktop            |
| col-xl  | >= 1200px   | Large Desktop / TV |
| col-xxl | >= 1400px   | Ultra Wide Screens |

---

# Responsive Grid Example

```html
<div class="row">

    <div class="col-6 col-md-4 red">

    </div>

    <div class="col-6 col-md-4 green">

    </div>

</div>
```

### Mobile

```text
col-6
```

50% width

```text
Red | Green
```

### Laptop and Above

```text
col-md-4
```

Each takes 4 columns.

---

# Another Responsive Example

```html
<div class="row">

    <div class="col-12 col-md-6 red">

    </div>

    <div class="col-12 col-md-6 green">

    </div>

</div>
```

### Mobile

```text
Red
Green
```

### Laptop

```text
Red | Green
```

---

# Complete Responsive Example

```html
<div class="row">

    <div class="col-12 col-sm-6 col-md-5 col-lg-4 col-xl-3 col-xxl-2 red">

    </div>

    <div class="col-12 col-sm-6 col-md-5 col-lg-4 col-xl-3 col-xxl-2 green">

    </div>

</div>
```

---

# Understanding the Above Code

```html
col-12
```

Mobile = Full Width

```text
1 item per row
```

---

```html
col-sm-6
```

Tablet = Half Width

```text
2 items per row
```

---

```html
col-md-5
```

Laptop = 5 Columns

---

```html
col-lg-4
```

Desktop = 4 Columns

```text
3 items per row
```

---

```html
col-xl-3
```

Large Desktop

```text
4 items per row
```

---

```html
col-xxl-2
```

Ultra Wide Screens

```text
6 items per row
```

---

# Most Important Interview Question

## Why Bootstrap Uses 12 Columns?

Because 12 is highly divisible.

```text
12 ÷ 2 = 6
12 ÷ 3 = 4
12 ÷ 4 = 3
12 ÷ 6 = 2
```

This allows flexible layouts.

---


```html
col-12 col-sm-6 col-md-6 col-lg-4 col-xl-3
```

Meaning:

```text
Mobile  = 1 Item

Tablet  = 2 Items

Laptop  = 2 Items

Desktop = 3 Items

TV      = 4 Items
```

---

# CSS Used in Today's Examples

```css
*{
    background-color: beige;
}

.green{
    background-color: green;
    border-radius: 7px;
    border-style: none;
    padding:10px;
}

.red{
    background-color: red;
    border-radius: 7px;
    border-style: none;
    padding:10px;
}

.container1{
   background-color: rgb(202, 234, 245);
   padding-top:10px;
   padding-bottom:10px;
}
```

---

# Key Takeaways

1. Responsive Design makes websites work on all devices.
2. Bootstrap provides a 12-column grid system.
3. One row always contains 12 columns.
4. Use Container → Row → Column structure.
5. Bootstrap breakpoints help create responsive layouts.
6. Different column classes apply at different screen sizes.
7. The most commonly used responsive class combination is:

```html
col-12 col-sm-6 col-md-6 col-lg-4 col-xl-3
```

