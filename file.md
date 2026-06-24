
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
# Full Code 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Responsive Design using Bootstrap 12 Grid System</title>

    <!-- Bootstrap CSS -->
    <link rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css">

    <style>
        *{
            background-color: beige;
        }

        .green{
            background-color: green;
            border-radius: 7px;
            border-style: none;
            padding:10px;
            color:white;
            text-align:center;
            min-height:60px;
        }

        .red{
            background-color: red;
            border-radius: 7px;
            border-style: none;
            padding:10px;
            color:white;
            text-align:center;
            min-height:60px;
        }

        .container1{
            background-color: rgb(202, 234, 245);
            padding-top:10px;
            padding-bottom:10px;
        }

        h1,h2,h3,h4,p{
            background:transparent;
        }

        .note{
            background:white;
            padding:20px;
            border-radius:10px;
            margin:20px;
        }
    </style>
</head>

<body>

<div class="container">

    <div class="note">

        <h1>Responsive Design using Bootstrap 12 Grid System</h1>

        <hr>

        <h3>Bootstrap Grid System</h3>

        <p>
            Bootstrap divides every row into 12 equal columns.
        </p>

        <pre>
|1|2|3|4|5|6|7|8|9|10|11|12|
        </pre>

        <hr>

        <h3>Bootstrap Breakpoints</h3>

        <table class="table table-bordered">
            <thead>
                <tr>
                    <th>Class</th>
                    <th>Screen Size</th>
                    <th>Device</th>
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>col</td>
                    <td>All Devices</td>
                    <td>Mobile</td>
                </tr>

                <tr>
                    <td>col-sm</td>
                    <td>&gt;=576px</td>
                    <td>Tablet</td>
                </tr>

                <tr>
                    <td>col-md</td>
                    <td>&gt;=768px</td>
                    <td>Laptop</td>
                </tr>

                <tr>
                    <td>col-lg</td>
                    <td>&gt;=992px</td>
                    <td>Desktop</td>
                </tr>

                <tr>
                    <td>col-xl</td>
                    <td>&gt;=1200px</td>
                    <td>TV</td>
                </tr>

                <tr>
                    <td>col-xxl</td>
                    <td>&gt;=1400px</td>
                    <td>Large TV</td>
                </tr>
            </tbody>
        </table>

        <hr>

        <h3>Column Widths</h3>

        <pre>
col-12 = 100%
col-6  = 50%
col-4  = 33.33%
col-3  = 25%
col-2  = 16.66%
col-1  = 8.33%
        </pre>

        <hr>

        <h3>Example 1 : col-6 + col-6</h3>

        <div class="row container1">

            <div class="col-6 green">
                Left
            </div>

            <div class="col-6 red">
                Right
            </div>

        </div>

        <p>
            Formula : 6 + 6 = 12
        </p>

        <hr>

        <h3>Example 2 : col-4 + col-4 + col-4</h3>

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

        <p>
            Formula : 4 + 4 + 4 = 12
        </p>

        <hr>

        <h3>Example 3 : col-3 + col-3 + col-3 + col-3</h3>

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

        <p>
            Formula : 3 + 3 + 3 + 3 = 12
        </p>

        <hr>

        <h3>Example 4 : col-5 + col-5 + col-2</h3>

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

        <p>
            Formula : 5 + 5 + 2 = 12
        </p>

        <hr>

        <h3>Example 5 : col-7 + col-3 + col-2</h3>

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

        <p>
            Formula : 7 + 3 + 2 = 12
        </p>

        <hr>

        <h3>Example 6 : 12 Individual Columns</h3>

        <div class="row container1">

            <div class="col-1 green">1</div>
            <div class="col-1 red">2</div>
            <div class="col-1 green">3</div>
            <div class="col-1 red">4</div>
            <div class="col-1 green">5</div>
            <div class="col-1 red">6</div>
            <div class="col-1 green">7</div>
            <div class="col-1 red">8</div>
            <div class="col-1 green">9</div>
            <div class="col-1 red">10</div>
            <div class="col-1 green">11</div>
            <div class="col-1 red">12</div>

        </div>

        <hr>

        <h3>Responsive Example 1</h3>

        <p>
            Mobile = col-6
            <br>
            Laptop = col-md-4
        </p>

        <div class="row">

            <div class="col-6 col-md-4 red">
                Red
            </div>

            <div class="col-6 col-md-4 green">
                Green
            </div>

        </div>

        <hr>

        <h3>Responsive Example 2</h3>

        <p>
            Mobile = Full Width
            <br>
            Laptop = Half Width
        </p>

        <div class="row">

            <div class="col-12 col-md-6 red">
                Red Section
            </div>

            <div class="col-12 col-md-6 green">
                Green Section
            </div>

        </div>

        <hr>

        <h3>Responsive Example 3</h3>

        <div class="row">

            <div class="col-12 col-sm-6 col-md-5 col-lg-4 col-xl-3 col-xxl-2 red">
                Responsive Box
            </div>

            <div class="col-12 col-sm-6 col-md-5 col-lg-4 col-xl-3 col-xxl-2 green">
                Responsive Box
            </div>

        </div>

        <br>

        <pre>
col-12 col-sm-6 col-md-6 col-lg-4 col-xl-3

Mobile   = 1 Item

Tablet   = 2 Items

Laptop   = 2 Items

Desktop  = 3 Items

TV       = 4 Items
        </pre>

        <hr>

        <h3>Important Points</h3>

        <pre>
Container
    ↓
Row
    ↓
Column

One Row = 12 Columns

6 + 6 = 12

4 + 4 + 4 = 12

3 + 3 + 3 + 3 = 12

5 + 5 + 2 = 12

7 + 3 + 2 = 12
        </pre>

    </div>

</div>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
```
---

# Assignment 1: Responsive Restaurant Website

## Objective

Design a modern restaurant website.

### Sections

#### Navbar

* Logo
* Home
* Menu
* About
* Contact

#### Hero Section

* Restaurant Name
* Tagline
* Order Now Button

#### Popular Dishes

Minimum 6 Food Cards

Each Card Contains:

* Food Image
* Food Name
* Price
* Order Button

#### About Restaurant

* Restaurant Description
* Restaurant Image

#### Contact Section

* Address
* Phone Number
* Email

#### Footer

* Social Media Icons
* Copyright

---

## Responsive Requirement

```html
col-12 col-md-6 col-lg-4
```

### Mobile

```text
Food 1

Food 2

Food 3

Food 4

Food 5

Food 6
```

### Tablet

```text
Food 1     Food 2

Food 3     Food 4

Food 5     Food 6
```

### Desktop

```text
Food 1    Food 2    Food 3

Food 4    Food 5    Food 6
```

---

# Assignment 2: Responsive E-Commerce Product Page

## Objective

Build an Amazon/Flipkart-style product showcase page.

### Sections

#### Navbar

* Logo
* Home
* Products
* Cart
* Contact

#### Banner

* Promotional Banner

#### Product Section

Minimum 8 Products

Each Product Card

* Product Image
* Product Name
* Price
* Buy Now Button

#### Footer

* Quick Links
* Contact Information

---

## Output Structure

### Mobile

```text
----------------
Navbar
----------------

Banner

Product 1

Product 2

Product 3

Product 4

Product 5

Product 6

Product 7

Product 8

Footer
```

---

### Tablet

```text
Product 1   Product 2

Product 3   Product 4

Product 5   Product 6

Product 7   Product 8
```

---

### Desktop

```text
Product1 Product2 Product3 Product4

Product5 Product6 Product7 Product8
```

Use

```html
col-12 col-sm-6 col-lg-3
```

---

# Assignment 3: Responsive College Website

## Objective

Build a professional college landing page.

### Sections

#### Header

* College Logo
* College Name

#### Navbar

* Home
* About
* Courses
* Placements
* Contact

#### Hero Section

* College Banner
* Admission Open Button

#### Courses Section

Minimum 6 Courses

* CSE
* ECE
* EEE
* Civil
* Mechanical
* AI & DS

#### Placement Statistics

Display

* Students Placed
* Highest Package
* Companies Visited

#### Footer

* Address
* Phone
* Email

---

## Output Structure

### Desktop

```text
----------------------------------
Header
----------------------------------

Navbar

----------------------------------
Hero Banner
----------------------------------

Course1  Course2  Course3

Course4  Course5  Course6

----------------------------------
Placement Statistics
----------------------------------

Students   Package   Companies

----------------------------------
Footer
----------------------------------
```

---

### Mobile

```text
Header

Navbar

Hero Banner

Course1

Course2

Course3

Course4

Course5

Course6

Placement Statistics

Footer
```

Use

```html
col-12 col-md-6 col-lg-4
```
---
```html
col-12
col-sm-6
col-md-6
col-lg-4
col-xl-3
```



