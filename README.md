# Avengers Glowing Cube Documentation

## Introduction
This project creates a visually appealing glowing cube animation and enhances it by playing the Avengers theme song when the page loads or is clicked.

## HTML

The HTML structure for this project defines the entire layout of the glowing cube animation. It uses:
- A `<!DOCTYPE html>` declaration to specify the document type.
- The `<html>` element to define the root of the document, with `lang="en"` to specify the language as English.
- The `<head>` section for meta-information, including:
  - `<meta charset="UTF-8">` to set the character encoding.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` for responsive design.
  - `<title>` element to define the document title as "Avengers Glowing Cube".
  - `<link rel="stylesheet" href="index.css">` to link to the external CSS stylesheet.
- The `<body>` element containing:
  - A `<div>` with class `cube` to act as the wrapper for the animation.
  - Six `<span>` elements representing the faces of the cube, each containing an image.
  - An `<audio>` element with the ID `song` for playing the Avengers theme song.
  - A `<script>` element to link to the external JavaScript file.

## CSS

The CSS styles:
- Include a global reset for margin, padding, and box-sizing to ensure consistent rendering across browsers.
- Define styles for the `<body>` to center content, set a minimum height, and apply a background color.
- Style the `.cube` class to set its dimensions, apply 3D transformations, and animate the rotation.
- Use `@keyframes` for defining the rotation animation.
- Style individual divs and span elements within the cube to position them correctly and apply background gradients.
- Add a glowing effect to the top face of the cube using box-shadow and transformations.
- Ensure all embedded images fit perfectly within the cube faces.

## JavaScript

The JavaScript:
- Adds a `click` event listener to the `window` object to play the Avengers theme song when the window is clicked.
- Defines a function named `playAudio` that plays the audio element with the ID `song`.
- Adds a `load` event listener to the `window` object to automatically play the song when the page is loaded.

## Conclusion

Combining HTML, CSS, and JavaScript, this project creates an engaging glowing cube animation, complemented by the Avengers theme music. The HTML structure sets up the layout, the CSS styles control the visual aspects and animation, while the JavaScript ensures the audio plays as intended.

Feel free to reach out if you have any questions or need further assistance with the project.
