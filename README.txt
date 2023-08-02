# Vasili Arkhipov Tribute Page

This project is a simple tribute page dedicated to Vasili Arkhipov, built as part of the FreeCodeCamp Responsive Web Design Certification. The project is coded in HTML and CSS.

## Overview

The HTML document contains structured information about Arkhipov's life and significant contributions. This includes an image, chronology of his life, and multiple quotes about his influence.

The CSS file is used to style and structure the content on the webpage. This includes styles for text, layout, images, and link hover effects.

## File Structure

This project consists of two files:

1. `index.html`: This file contains the HTML markup for the tribute page. It includes all the text and media displayed to the user, as well as metadata and links to external stylesheets.

2. `styles.css`: This file contains all the custom CSS styles used to layout and decorate the HTML elements on the page.

## HTML Structure

The main content of the page is contained within a `<main>` element, which contains the following:

- A title `<h1>` for the name of Vasili Arkhipov
- An `<img>` element wrapped in a `<figure>` which holds the picture of Vasili Arkhipov in naval uniform. The `figcaption` provides a description of the image.
- A `<div>` containing an overview and chronology of Arkhipov's life in a list format. The `id` tribute-info is used to style this section in CSS.
- Multiple `<p>` elements that contain quotes about Arkhipov's contributions and influence.
- A link `<a>` to Arkhipov's Wikipedia page for further reading.

## CSS Styles

The `styles.css` file contains various styles that control the appearance and layout of the page.

- The `*` selector is used to apply box-sizing to all elements on the page.
- The `main` selector is used to set the font size, padding, and background color of the main content area.
- The `#tribute-info` and `#img-div` selectors are used to style the section containing the image and tribute information.
- Several selectors are used to style the text elements (`h1`, `h2`, `h3`, `p`, `ul`, `li`, `.bold`).
- The `a` selector is used to style the link, including hover and active states.

## Usage

To view the project, open the `index.html` file in any modern web browser. The styles should be applied automatically as the CSS file is linked within the HTML.

**Note:** Make sure both `index.html` and `styles.css` are in the same directory for the CSS to work correctly.