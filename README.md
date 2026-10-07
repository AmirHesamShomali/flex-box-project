# Flex Box Project

A responsive web page built as a front-end practice project using **HTML5, CSS3, and CSS Flexbox**.

The main goal of this project was to understand how Flexbox can be used to create structured, responsive, and flexible web page layouts without relying on complex frameworks or layout libraries.

## Overview

This project is a practical exercise focused on modern CSS layout techniques, especially **Flexbox**.

The page contains several different sections, including:

- Navigation / Menu
- Header section
- Content sections
- Image-based layout
- Flexible containers
- Footer section

The main layout of the website is created using CSS Flexbox, allowing the different elements to adapt to different screen sizes.

## Features

- Responsive web page layout
- Flexbox-based positioning
- Flexible rows and columns
- Responsive navigation layout
- Structured header section
- Image grid layout
- Responsive footer
- Clean HTML structure
- CSS-based styling
- No external CSS framework required

## Technologies Used

### HTML5

HTML5 is used to create the structure and semantic elements of the web page.

Main concepts used include:

- HTML document structure
- Containers
- Navigation elements
- Images
- Sections
- Footer
- Semantic HTML elements

### CSS3

CSS3 is used to style the page and create the responsive layout.

The project focuses mainly on:

- Flexbox
- `display: flex`
- `flex-direction`
- `justify-content`
- `align-items`
- `flex-wrap`
- `gap`
- `flex`
- Width and height management
- Margins and padding
- Responsive styling
- Media queries

## Flexbox Concepts

One of the main purposes of this project was practicing the CSS Flexbox layout system.

### Display Flex

The project uses:

```css
display: flex;
```

to turn containers into flexible layouts.

This allows child elements to be positioned dynamically inside their parent container.

### Flex Direction

Different sections can use:

```css
flex-direction: row;
```

or:

```css
flex-direction: column;
```

depending on the required layout.

### Justify Content

The horizontal or main-axis positioning of elements is controlled using properties such as:

```css
justify-content: center;
justify-content: space-between;
justify-content: space-around;
```

### Align Items

Elements can be aligned along the cross-axis using:

```css
align-items: center;
```

and other alignment values.

### Flex Wrap

For responsive layouts, elements can move to another row when there is not enough available space:

```css
flex-wrap: wrap;
```

This is especially useful for image and content sections.

## Responsive Design

The project was designed with responsive behavior in mind.

The layout uses flexible dimensions and CSS techniques so that page sections can adapt to different screen sizes.

Media queries can also be used to modify the layout for smaller devices such as tablets and mobile phones.

Example:

```css
@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
}
```

This allows a row-based layout to become a column-based layout on smaller screens.

## Project Structure

```text
flex-box-project/
│
└── flex-project/
    │
    ├── index.html
    ├── style.css
    └── ...
```

The exact project structure may vary depending on the files included in the project.

## How to Run

You don't need to install any package or dependency to run this project.

### 1. Clone the repository

```bash
git clone https://github.com/AmirHesamShomali/flex-box-project.git
```

### 2. Open the project

Navigate to the project directory:

```bash
cd flex-box-project
```

### 3. Run the project

Open the HTML file in your browser.

You can also use **Visual Studio Code** with the **Live Server** extension for easier development.

## Learning Objectives

This project was created to practice and understand:

- How CSS Flexbox works
- Creating layouts with rows and columns
- Positioning elements without excessive absolute positioning
- Building flexible containers
- Creating responsive layouts
- Organizing HTML and CSS
- Understanding the relationship between parent and child elements
- Improving front-end layout skills

## What I Learned

While working on this project, I practiced using Flexbox to solve common layout problems.

In particular, I learned how to:

- Build navigation layouts using Flexbox
- Align elements horizontally and vertically
- Distribute available space between elements
- Create flexible image layouts
- Make sections adapt to different screen sizes
- Combine Flexbox with media queries
- Create cleaner and more maintainable CSS layouts

## Future Improvements

Possible improvements for future versions include:

- Adding more responsive breakpoints
- Improving mobile navigation
- Adding animations and transitions
- Improving accessibility
- Adding semantic HTML improvements
- Adding JavaScript interactions
- Improving the visual design
- Deploying the project online

## Purpose

This project is part of my front-end development practice and demonstrates my understanding of **HTML, CSS, Flexbox, and responsive web design**.

It is also part of my growing portfolio of web development projects.

## Author

**Amir Hesam Shomali**

GitHub:

https://github.com/AmirHesamShomali

## Repository

The source code for this project is available on GitHub:

https://github.com/AmirHesamShomali/flex-box-project
