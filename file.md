# HTML Complete Notes - Day 2

# Advanced HTML

## Topics Covered

1. HTML Attributes
2. Global Attributes
3. Hyperlinks Advanced
4. Absolute vs Relative Paths
5. Images Advanced
6. Tables Advanced
7. Rowspan and Colspan
8. Semantic HTML
9. HTML Entities
10. Audio Tag
11. Video Tag
12. iframe
13. Meta Tags
14. Mini Projects
15. Practice Tasks
16. Interview Questions

---

# What are Attributes?

Attributes provide additional information about HTML elements.

Syntax:

```html
<tag attribute="value">
```

Example:

```html
<a href="https://www.google.com">Google</a>
```

Here `href` is an attribute.

---

# Global Attributes

## id

Used to uniquely identify an element.

```html
<h1 id="heading1">Frontend</h1>
```

## class

Used to group multiple elements.

```html
<p class="student">Rahul</p>
<p class="student">Kiran</p>
```

## title

Shows tooltip on hover.

```html
<p title="Student Name">Rahul</p>
```

## hidden

Hides content.

```html
<p hidden>This is hidden</p>
```

## contenteditable

Allows editing.

```html
<p contenteditable="true">Edit me</p>
```

## draggable

Makes element draggable.

```html
<img src="image.jpg" draggable="true">
```

---

# Hyperlinks Advanced

## External Link

```html
<a href="https://www.google.com">Google</a>
```

## Internal Link

```html
<a href="about.html">About</a>
```

## Open in New Tab

```html
<a href="https://google.com" target="_blank">
Google
</a>
```

## Email Link

```html
<a href="mailto:test@gmail.com">
Send Mail
</a>
```

## Telephone Link

```html
<a href="tel:9876543210">
Call Now
</a>
```

## Download Link

```html
<a href="resume.pdf" download>
Download Resume
</a>
```

## Bookmark Link

```html
<a href="#contact">
Go To Contact
</a>
```

Destination:

```html
<h2 id="contact">
Contact Section
</h2>
```

---

# Absolute vs Relative Paths

## Absolute Path

```html
<img src="https://picsum.photos/200">
```

## Relative Path

```html
<img src="images/profile.jpg">
```

---

# Images Advanced

```html
<img
src="profile.jpg"
alt="Student Image"
title="Profile"
width="200"
height="200">
```

### alt

Alternative text when image fails.

### width

Controls image width.

### height

Controls image height.

### title

Tooltip on hover.

---

# Tables Advanced

## Table Structure

```html
<table border="1">

<tr>
<th>Name</th>
<th>Marks</th>
</tr>

<tr>
<td>Rahul</td>
<td>95</td>
</tr>

</table>
```

## caption

```html
<table>
<caption>Student Details</caption>
</table>
```

## thead

Header section.

## tbody

Body section.

## tfoot

Footer section.

---

# Rowspan

```html
<td rowspan="2">Rahul</td>
```

Used to merge rows vertically.

---

# Colspan

```html
<th colspan="2">
Student Details
</th>
```

Used to merge columns horizontally.

---

# Semantic HTML

## Why Semantic HTML?

Semantic tags clearly describe their meaning.

### header

```html
<header>
Website Header
</header>
```

### nav

```html
<nav>
Home About Contact
</nav>
```

### main

```html
<main>
Main Content
</main>
```

### section

```html
<section>
Course Information
</section>
```

### article

```html
<article>
Blog Content
</article>
```

### aside

```html
<aside>
Latest Updates
</aside>
```

### footer

```html
<footer>
Copyright 2026
</footer>
```

---

# HTML Entities

## Less Than

```html
&lt;
```

## Greater Than

```html
&gt;
```

## Copyright

```html
&copy;
```

## Registered

```html
&reg;
```

## Rupee

```html
&#8377;
```

## Non Breaking Space

```html
&nbsp;
```

---

# Audio Tag

```html
<audio controls>
<source src="song.mp3" type="audio/mp3">
</audio>
```

Attributes:

- controls
- autoplay
- loop
- muted

---

# Video Tag

```html
<video width="500" controls>
<source src="video.mp4" type="video/mp4">
</video>
```

Attributes:

- controls
- autoplay
- muted
- loop

---

# iframe

## YouTube

```html
<iframe
width="500"
height="300"
src="https://www.youtube.com/embed/VIDEO_ID">
</iframe>
```

## Google Maps

```html
<iframe src="MAP_URL"></iframe>
```

---

# Meta Tags

```html
<meta charset="UTF-8">
```

```html
<meta
name="viewport"
content="width=device-width, initial-scale=1.0">
```

```html
<meta
name="description"
content="Frontend Course">
```

```html
<meta
name="keywords"
content="HTML,CSS,JavaScript">
```

```html
<meta
name="author"
content="Maheswaram">
```

---

# Mini Project 1

Student Details Table

# Mini Project 2

College Timetable

# Mini Project 3

Semantic Webpage Layout

Header + Nav + Main + Footer

---

# Practice Tasks

1. Create Employee Table.
2. Create Student Result Sheet.
3. Create Bookmark Navigation.
4. Add Image Hyperlink.
5. Embed YouTube Video.
6. Create Semantic Layout.
7. Add Audio and Video.

---

# Interview Questions

## What is an attribute?

Additional information provided to an HTML element.

## Difference between id and class?

id → unique

class → reusable

## What is rowspan?

Merges rows vertically.

## What is colspan?

Merges columns horizontally.

## What is semantic HTML?

HTML tags that describe their purpose.

## What is iframe?

Used to embed another webpage.

## What is alt attribute?

Alternative text displayed when image fails.

---

# Day 2 Summary

Topics Covered:

- Attributes
- Hyperlinks
- Paths
- Images
- Tables
- Rowspan
- Colspan
- Semantic HTML
- HTML Entities
- Audio
- Video
- iframe
- Meta Tags


Save as:

```text
day2.html
```

```html
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0">

    <meta
        name="description"
        content="Advanced HTML Day 2">

    <meta
        name="keywords"
        content="HTML,CSS,JavaScript">

    <meta
        name="author"
        content="Maheswaram">

    <title>Advanced HTML - Day 2</title>

</head>

<body>

    <!-- =============================== -->
    <!-- HEADER -->
    <!-- =============================== -->

    <header>

        <h1 align="center">
            HTML Advanced Concepts
        </h1>

        <p align="center">
            Complete Day 2 Demonstration File
        </p>

    </header>

    <hr>

    <!-- =============================== -->
    <!-- ATTRIBUTES -->
    <!-- =============================== -->

    <section>

        <h2>1. Global Attributes</h2>

        <p title="Tooltip Example">
            Hover over me
        </p>

        <p contenteditable="true">
            Edit this content
        </p>

        <p hidden>
            Hidden Paragraph
        </p>

        <img
            src="https://picsum.photos/150"
            draggable="true">

    </section>

    <hr>

    <!-- =============================== -->
    <!-- HYPERLINKS -->
    <!-- =============================== -->

    <section>

        <h2>2. Hyperlinks</h2>

        <a href="https://www.google.com">
            Open Google
        </a>

        <br><br>

        <a
            href="https://www.flipkart.com"
            target="_blank">

            Open Flipkart New Tab

        </a>

        <br><br>

        <a href="mailto:test@gmail.com">

            Send Email

        </a>

        <br><br>

        <a href="tel:9876543210">

            Call Now

        </a>

        <br><br>

        <a href="resume.pdf" download>

            Download Resume

        </a>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- BOOKMARK LINKS -->
    <!-- =============================== -->

    <section>

        <h2>3. Bookmark Navigation</h2>

        <a href="#contact">

            Go To Contact Section

        </a>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- ABSOLUTE PATH -->
    <!-- =============================== -->

    <section>

        <h2>4. Absolute Path Image</h2>

        <img
            src="https://picsum.photos/200"
            width="200"
            height="200">

    </section>

    <hr>

    <!-- =============================== -->
    <!-- RELATIVE PATH -->
    <!-- =============================== -->

    <section>

        <h2>5. Relative Path Example</h2>

        <img
            src="images/profile.jpg"
            alt="Local Image"
            width="200">

    </section>

    <hr>

    <!-- =============================== -->
    <!-- IMAGE ATTRIBUTES -->
    <!-- =============================== -->

    <section>

        <h2>6. Image Attributes</h2>

        <img
            src="https://picsum.photos/250"
            alt="Sample Image"
            title="Profile Picture"
            width="250"
            height="250">

    </section>

    <hr>

    <!-- =============================== -->
    <!-- IMAGE HYPERLINK -->
    <!-- =============================== -->

    <section>

        <h2>7. Image Hyperlink</h2>

        <a href="https://www.google.com">

            <img
                src="https://picsum.photos/300"
                width="300">

        </a>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- TABLE BASIC -->
    <!-- =============================== -->

    <section>

        <h2>8. Student Table</h2>

        <table border="1">

            <caption>

                Student Details

            </caption>

            <thead>

                <tr>

                    <th>ID</th>
                    <th>Name</th>
                    <th>Course</th>

                </tr>

            </thead>

            <tbody>

                <tr>

                    <td>101</td>
                    <td>Rahul</td>
                    <td>Java</td>

                </tr>

                <tr>

                    <td>102</td>
                    <td>Kiran</td>
                    <td>Python</td>

                </tr>

            </tbody>

            <tfoot>

                <tr>

                    <td colspan="3">

                        Total Students : 2

                    </td>

                </tr>

            </tfoot>

        </table>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- ROWSPAN -->
    <!-- =============================== -->

    <section>

        <h2>9. Rowspan Example</h2>

        <table border="1">

            <tr>

                <th>Name</th>
                <th>Subject</th>

            </tr>

            <tr>

                <td rowspan="2">

                    Rahul

                </td>

                <td>Java</td>

            </tr>

            <tr>

                <td>Python</td>

            </tr>

        </table>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- COLSPAN -->
    <!-- =============================== -->

    <section>

        <h2>10. Colspan Example</h2>

        <table border="1">

            <tr>

                <th colspan="2">

                    Student Information

                </th>

            </tr>

            <tr>

                <td>Name</td>
                <td>Rahul</td>

            </tr>

        </table>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- ROWSPAN + COLSPAN -->
    <!-- =============================== -->

    <section>

        <h2>11. Rowspan + Colspan</h2>

        <table border="1">

            <tr>

                <th rowspan="2">

                    Student

                </th>

                <th colspan="2">

                    Marks

                </th>

            </tr>

            <tr>

                <th>HTML</th>
                <th>CSS</th>

            </tr>

            <tr>

                <td>Rahul</td>
                <td>95</td>
                <td>90</td>

            </tr>

        </table>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- HTML ENTITIES -->
    <!-- =============================== -->

    <section>

        <h2>12. HTML Entities</h2>

        <p>Less Than : &lt;</p>

        <p>Greater Than : &gt;</p>

        <p>Copyright : &copy;</p>

        <p>Registered : &reg;</p>

        <p>Rupee : &#8377;</p>

        <p>Heart : &#10084;</p>

        <p>Hello&nbsp;&nbsp;&nbsp;World</p>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- AUDIO -->
    <!-- =============================== -->

    <section>

        <h2>13. Audio Tag</h2>

        <audio controls>

            <source
                src="sample.mp3"
                type="audio/mp3">

        </audio>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- VIDEO -->
    <!-- =============================== -->

    <section>

        <h2>14. Video Tag</h2>

        <video
            width="400"
            controls>

            <source
                src="sample.mp4"
                type="video/mp4">

        </video>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- IFRAME -->
    <!-- =============================== -->

    <section>

        <h2>15. YouTube iframe</h2>

        <iframe
            width="560"
            height="315"
            src="https://www.youtube.com/embed/tgbNymZ7vqY">

        </iframe>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- GOOGLE MAP -->
    <!-- =============================== -->

    <section>

        <h2>16. Google Maps iframe</h2>

        <iframe
            src="https://maps.google.com/maps?q=hyderabad&t=&z=13&ie=UTF8&iwloc=&output=embed"
            width="500"
            height="300">

        </iframe>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- SEMANTIC HTML -->
    <!-- =============================== -->

    <section>

        <h2>17. Semantic HTML Layout</h2>

        <header>

            <h3>Website Header</h3>

        </header>

        <nav>

            <a href="#">Home</a> |

            <a href="#">About</a> |

            <a href="#">Courses</a> |

            <a href="#">Contact</a>

        </nav>

        <main>

            <section>

                <h3>Frontend Course</h3>

                <p>
                    HTML CSS JavaScript
                </p>

            </section>

            <article>

                <h3>Blog Article</h3>

                <p>
                    This is article content.
                </p>

            </article>

            <aside>

                Latest Updates Section

            </aside>

        </main>

        <footer>

            <p>

                Copyright 2026

            </p>

        </footer>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- MINI PROJECT -->
    <!-- =============================== -->

    <section>

        <h2>18. College Timetable</h2>

        <table border="1">

            <tr>

                <th>Day</th>
                <th>9-10</th>
                <th>10-11</th>
                <th>11-12</th>

            </tr>

            <tr>

                <td>Monday</td>
                <td>HTML</td>
                <td>CSS</td>
                <td>JavaScript</td>

            </tr>

            <tr>

                <td>Tuesday</td>
                <td>Java</td>
                <td>SQL</td>
                <td>Spring</td>

            </tr>

        </table>

    </section>

    <hr>

    <!-- =============================== -->
    <!-- CONTACT -->
    <!-- =============================== -->

    <section id="contact">

        <h2>Contact Section</h2>

        <p>Email : support@gmail.com</p>

        <p>Phone : 9876543210</p>

    </section>

    <hr>

    <h2 align="center">

        Day 2 Advanced HTML Completed

    </h2>

</body>

</html>
```

