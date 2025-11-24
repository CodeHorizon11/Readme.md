# HTML & CSS Labs - Complete Guide

A comprehensive collection of web development labs covering HTML fundamentals and CSS styling techniques.

---

## 📋 Table of Contents

- [Lab 1: Creating a Basic HTML Page](#lab-1-creating-a-basic-html-page)
- [Lab 2: HTML Tables and Lists](#lab-2-html-tables-and-lists)
- [Lab 3: CSS Types, Selectors, and Colors](#lab-3-css-types-selectors-and-colors)
- [Lab 4: Advanced CSS Styling](#lab-4-advanced-css-styling)
- [Lab 5: CSS Box Model & Layouts](#lab-5-css-box-model--layouts)

---

## Lab 1: Creating a Basic HTML Page

### 🎯 Objective
Learn to create a basic HTML webpage with headings, paragraphs, and links.

### 📚 Theory Overview
HTML (Hypertext Markup Language) is the standard markup language used to create web pages. It structures web content using tags.

### 🏷️ Common Tags Used

| Tag | Purpose |
|-----|---------|
| `<html>` | Defines the HTML document |
| `<head>` | Holds metadata and the title |
| `<body>` | Contains visible content |
| `<h1>`, `<h2>`, `<h3>` | Headings (h1 is largest) |
| `<p>` | Defines paragraphs |
| `<a>` | Creates hyperlinks |

### 📝 Steps to Create a Basic HTML Page

1. Open a text editor like Notepad or Visual Studio Code
2. Save the file as `index.html`
3. Write the HTML code
4. Save and open the file in a browser to see the result

### ✅ Lab Tasks

**Task 1:** Create a webpage similar to the example. Change the headings and add three links.

**Task 2:** Write a short paragraph about yourself under the "About Me" section.

**Task 3:** Add another heading like "Hobbies" and describe your favorite activities.

**Task 4:** Add your favorite website link that opens in a new tab using `target="_blank"`.

**Task 5 (Optional):** Add basic CSS styling.

**Task 6:** Save your file and submit it as instructed.

### 💻 Sample Code

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Webpage</title>
    <style>
        body {background-color: lightblue;}
        h1 {color: darkblue;}
        p {font-size: 18px;}
    </style>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <h2>About Me</h2>
    <p>This is a paragraph about me.</p>
    
    <h2>My Links</h2>
    <a href="https://www.example.com" target="_blank">Visit Example</a>
</body>
</html>
```

---

## Lab 2: HTML Tables and Lists

### 🎯 Objective
Understand and practice HTML tables and lists for displaying structured data.

### 📚 Theory Overview

Lists and tables help organize content on web pages effectively.

| Element | Tag | Description |
|---------|-----|-------------|
| Ordered List | `<ol>` | Shows items with numbers |
| Unordered List | `<ul>` | Shows items with bullets |
| Description List | `<dl>` | Pairs terms with descriptions |
| Table | `<table>` | Displays data in rows and columns |

### 📝 Steps

1. Open a text editor and create a new file named `lab2_tables_lists.html`
2. Add the basic HTML structure
3. Write the code for lists and tables

### ✅ Lab Tasks

1. Create an HTML page titled "Lab 2: Tables and Lists"
2. Use ordered, unordered, and description lists to display:
   - Daily Routine
   - Hobbies
   - Subjects with short details
3. Create a class timetable using a table with columns: Day, Subject, Teacher Name, Time

### 💻 Sample Code

```html
<!DOCTYPE html>
<html>
<head>
    <title>Lab 2: Tables and Lists</title>
</head>
<body>
    <h1>My Daily Routine</h1>
    <ol>
        <li>Wake up at 6 AM</li>
        <li>Exercise</li>
        <li>Breakfast</li>
    </ol>

    <h2>My Hobbies</h2>
    <ul>
        <li>Reading</li>
        <li>Coding</li>
        <li>Gaming</li>
    </ul>

    <h2>Class Timetable</h2>
    <table border="1">
        <tr>
            <th>Day</th>
            <th>Subject</th>
            <th>Teacher Name</th>
            <th>Time</th>
        </tr>
        <tr>
            <td>Monday</td>
            <td>Math</td>
            <td>Mr. Smith</td>
            <td>9:00 AM</td>
        </tr>
    </table>
</body>
</html>
```

### 🔍 Observation
- Lists organize data in readable form
- Tables are ideal for structured data presentation

---

## Lab 3: CSS Types, Selectors, and Colors

### 🎯 Objective
Practice using different types of CSS, selectors, and color properties such as hue, saturation, and opacity.

### 📚 Theory Overview

CSS (Cascading Style Sheets) controls the presentation of HTML elements.

### 🎨 Three Main Types of CSS

1. **Inline CSS:** Applied directly inside HTML tags
2. **Internal CSS:** Written inside the `<style>` tag in the `<head>` section
3. **External CSS:** Written in a separate `.css` file and linked with `<link>`

### 🎯 CSS Selectors

| Selector | Syntax | Example |
|----------|--------|---------|
| Element | `elementname` | `p { color: red; }` |
| ID | `#id` | `#main { color: blue; }` |
| Class | `.classname` | `.highlight { color: orange; }` |

### ✅ Task 1: Types of CSS

Create two files: `css_lab.html` and `style.css`

**css_lab.html:**
```html
<!DOCTYPE html>
<html>
<head>
    <title>Types of CSS</title>
    <link rel="stylesheet" href="style.css">
    <style>
        h2 { color: green; }
    </style>
</head>
<body>
    <h1 style="color: blue;">Inline CSS Example</h1>
    <h2>Internal CSS Example</h2>
    <p class="external">External CSS Example</p>
</body>
</html>
```

**style.css:**
```css
.external {
    color: red;
    font-weight: bold;
}
```

### ✅ Task 2: CSS Selectors

```css
p { color: brown; } /* element selector */
#main { color: blue; } /* id selector */
.highlight { color: orange; } /* class selector */
```

```html
<p id="main">ID Selector Example</p>
<p class="highlight">Class Selector Example</p>
<a href="#">Hover over this link</a>
```

### ✅ Task 3: Colors, Hue, Saturation, Opacity

```html
<div style="background:hsl(0,100%,50%); width:100px;height:100px;">Hue 0°</div>
<div style="background:hsl(120,100%,50%); width:100px;height:100px;">Hue 120°</div>
<div style="background:hsl(240,100%,50%); width:100px;height:100px;">Hue 240°</div>
<div style="background:rgba(255,0,0,0.5); width:100px;height:100px;">Opacity 0.5</div>
```

### 🔍 Observation
- **Hue** changes the color tone (0-360 degrees)
- Lower **saturation** makes colors appear grayish
- **Opacity** controls transparency (0-1)

---

## Lab 4: Advanced CSS Styling

### 🎯 Objective
Master advanced CSS styling techniques including pseudo-classes, color systems, and visual effects.

### 📚 Key Concepts

**CSS Priority:**
The code demonstrates how inline, internal, and external CSS work together, showing style priority and cascade rules.

**Advanced Selectors:**
Learn to use element (`p`), id (`#main`), and class (`.highlight`) selectors effectively for precise styling control.

**Color Systems:**
Understand HSL (Hue, Saturation, Lightness) and RGBA (Red, Green, Blue, Alpha) color models for creating dynamic color schemes.

### 💻 Complete Implementation

```html
<!DOCTYPE html>
<html>
<head>
    <title>Advanced CSS Styling</title>
    <link rel="stylesheet" href="advanced.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        
        h1 {
            color: #2c3e50;
            text-align: center;
        }
        
        .color-box {
            display: inline-block;
            margin: 10px;
            text-align: center;
            padding: 10px;
            color: white;
            font-weight: bold;
        }
        
        a:hover {
            color: #e74c3c;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <h1>Advanced CSS Styling Demo</h1>
    
    <h2>CSS Selectors in Action</h2>
    <p id="main">This uses ID selector styling</p>
    <p class="highlight">This uses class selector styling</p>
    <a href="#">Hover over this link to see effects</a>
    
    <h2>Color Systems</h2>
    <div class="color-box" style="background:hsl(0,100%,50%);">Red (Hue 0°)</div>
    <div class="color-box" style="background:hsl(120,100%,50%);">Green (Hue 120°)</div>
    <div class="color-box" style="background:hsl(240,100%,50%);">Blue (Hue 240°)</div>
    <div class="color-box" style="background:rgba(255,0,0,0.5); color: black;">Semi-transparent Red</div>
</body>
</html>
```

**advanced.css:**
```css
p { 
    color: #34495e;
    line-height: 1.6;
}

#main { 
    color: #3498db;
    font-size: 18px;
    font-weight: bold;
}

.highlight { 
    color: #e67e22;
    background-color: #fff3cd;
    padding: 5px;
    border-radius: 4px;
}

a {
    color: #2980b9;
    text-decoration: none;
    transition: all 0.3s ease;
}
```

### 🎨 Practice Areas
- Experiment with different color combinations using HSL and RGBA
- Create hover effects using pseudo-classes
- Combine multiple selectors for complex styling
- Adjust transparency levels for layered designs

---

## Lab 5: CSS Box Model & Layouts

### 🎯 Objective
Master the CSS box model and create responsive layouts using modern CSS techniques.

### 📚 Theory Overview

The CSS box model is fundamental to understanding how elements are sized and spaced on a webpage.

### 📦 Box Model Components

```
┌─────────────────────────────────┐
│         Margin (outside)        │
│  ┌──────────────────────────┐  │
│  │    Border                │  │
│  │  ┌───────────────────┐  │  │
│  │  │   Padding         │  │  │
│  │  │  ┌────────────┐  │  │  │
│  │  │  │  Content   │  │  │  │
│  │  │  └────────────┘  │  │  │
│  │  └───────────────────┘  │  │
│  └──────────────────────────┘  │
└─────────────────────────────────┘
```

### ✅ Task 1: Box Model Exploration

Experiment with the box model properties:

```css
.box {
    width: 200px;
    height: 100px;
    padding: 20px;        /* Space inside the border */
    margin: 15px;         /* Space outside the border */
    border: 3px solid #333;
    background-color: #3498db;
    color: white;
}
```

**Practice:**
- Change `padding` values and observe how content space increases
- Adjust `margin` to see spacing between boxes
- Modify `border` width and style

### ✅ Task 2: Outline Properties

```css
.outlined-box {
    width: 200px;
    height: 100px;
    border: 2px solid #2c3e50;
    outline: 3px dashed #e74c3c;
    outline-offset: 5px;
}
```

**Experiment with:**
- `outline-style: solid | dotted | dashed | double`
- `outline-offset` to move the outline away from the border
- Different outline colors

### ✅ Task 3: Complete Card Layout

Create a professional card component:

```html
<!DOCTYPE html>
<html>
<head>
    <title>CSS Box Model</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ecf0f1;
            padding: 40px;
        }
        
        .card {
            width: 300px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        
        .card h2 {
            margin-top: 0;
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        
        .card p {
            color: #555;
            line-height: 1.6;
        }
        
        .box-demo {
            display: inline-block;
            width: 150px;
            height: 100px;
            margin: 10px;
            padding: 15px;
            border: 3px solid #3498db;
            background-color: #ebf5fb;
            text-align: center;
        }
        
        .outlined {
            outline: 2px dashed #e74c3c;
            outline-offset: 5px;
        }
    </style>
</head>
<body>
    <h1 style="text-align: center;">CSS Box Model Demo</h1>
    
    <div class="card">
        <h2>Profile Card</h2>
        <p>This card demonstrates the box model with padding, border, and margin working together.</p>
        <p>Notice the shadow effect and rounded corners created using modern CSS properties.</p>
    </div>
    
    <div style="text-align: center;">
        <div class="box-demo">
            <strong>Box 1</strong><br>
            Standard Box
        </div>
        <div class="box-demo outlined">
            <strong>Box 2</strong><br>
            With Outline
        </div>
    </div>
</body>
</html>
```

### 🎨 Challenge Tasks

**Customize the Card:**
- Change background colors and borders
- Adjust padding to make content more spacious
- Add hover effects with transitions
- Create multiple cards with different styles

**Box Model Experiments:**
- Create a grid of boxes with consistent spacing
- Build a navigation bar using the box model
- Design a photo gallery layout

### 🔍 Key Observations

- **Padding** increases the space inside an element, affecting its total size
- **Margin** creates space between elements without affecting their size
- **Border** adds a visible edge and contributes to total element size
- **Outline** appears outside the border and doesn't affect layout
- Use `box-sizing: border-box` to include padding and border in width calculations

---

## 🚀 Getting Started

1. Clone this repository
2. Open any lab file in your browser
3. Experiment with the code
4. Modify and create your own variations

## 📖 Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [W3Schools](https://www.w3schools.com/)
- [CSS-Tricks](https://css-tricks.com/)

## 🤝 Contributing

Feel free to fork this repository and submit pull requests with improvements or additional labs!

## 📝 License

This project is open source and available for educational purposes.

---

**Happy Coding! 💻✨**