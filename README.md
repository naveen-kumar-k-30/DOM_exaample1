# DOM_exaample1
# README

## Overview

This project is a simple interactive webpage that demonstrates switching a bulb image between "on" and "off" states, along with changing a cat image and some text based on the bulb's state. The webpage uses HTML, Tailwind CSS for styling, and vanilla JavaScript for interactivity.

## File Structure

- `index.html`: Contains the HTML structure of the webpage.
- `README.md`: This file provides information about the project.

## Dependencies

- Tailwind CSS: A utility-first CSS framework for rapidly building custom user interfaces.
- Google Fonts: Specifically, the "Poppins" font family.

## Getting Started

To view and interact with the webpage, simply open the `index.html` file in a web browser.

## HTML Structure

The HTML file includes the following key sections:

1. **Head Section**:
    - Meta tags for character set and viewport settings.
    - Title of the webpage.
    - Tailwind CSS CDN link.
    - Google Fonts link for the "Poppins" font family.

2. **Body Section**:
    - A main `div` container with a black background, arranged in a flex row with centered content.
    - Images for the bulb and cat.
    - A paragraph to display the bulb state text.
    - Buttons to switch the bulb on and off.

## CSS Classes

The webpage uses Tailwind CSS classes for styling:

- `bg-black`: Sets the background color to black.
- `flex`, `flex-row`, `justify-center`: Flexbox utilities to center content.
- `space-y-4`: Adds vertical spacing between child elements.
- `h-dvh`: Sets the height relative to the viewport height.
- `text-white`, `border-2`, `w-40`, `font-['Poppins']`: Styles for text color, border, width, and font.
- `bg-green-500`, `bg-red-500`: Background colors for the buttons.
- `w-16`, `rounded-lg`: Width and rounded corners for buttons.
- `ml-7`: Margin-left spacing for elements.

## JavaScript Functionality

The JavaScript code handles the interactivity of the webpage:

- **Selecting Elements**:
    - `btn1`: The "Bulb On" button.
    - `btn2`: The "Bulb Off" button.
    - `bulb`: The bulb image.
    - `cat1`: The cat image.
    - `para`: The paragraph displaying the bulb state text.

- **Event Listeners**:
    - When `btn1` is clicked, the bulb image changes to the "on" state, the cat image remains the same, and the text changes to "Switched On".
    - When `btn2` is clicked, the bulb image changes to the "off" state, the cat image changes to show only the cat's eyes, and the text changes to "Switched Off".

## How to Use

1. Open the `index.html` file in a web browser.
2. Click the "Bulb On" button to switch the bulb image to the "on" state, and see the cat image and text update accordingly.
3. Click the "Bulb Off" button to switch the bulb image to the "off" state, and see the cat image and text update accordingly.

## Image Links

The images are hosted online and linked directly in the HTML and JavaScript:

- Bulb on: `https://ik.imagekit.io/4z8covdo9/Full%20stack/bulb-go-on-img.png?updatedAt=1702818139573`
- Bulb off: `https://ik.imagekit.io/4z8covdo9/Full%20stack/bulb-go-off-img.png?updatedAt=1702818065200`
- Cat normal: `https://ik.imagekit.io/4z8covdo9/Full%20stack/cat-img.png?updatedAt=1702818167774`
- Cat eyes: `https://ik.imagekit.io/4z8covdo9/Full%20stack/cat-eyes-img.png?updatedAt=1702818102345`

## Notes

- Ensure you have an internet connection to load the images and Tailwind CSS from the CDN.
- The `h-dvh` class used in the main container sets the height relative to the dynamic viewport height, which may require a modern browser for proper support.
