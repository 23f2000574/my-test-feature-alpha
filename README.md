# Simple Web Interaction App

## Overview
This project provides a basic demonstration of client-side JavaScript interaction, featuring two functional buttons. The primary button changes its displayed text upon interaction, and the adjacent 'Reset' button allows the user to restore the primary button's text to its default state.

## Setup
This application is contained within a single HTML file:
1. Save the provided code content into a file named `index.html`.
2. Open `index.html` using any modern web browser (Chrome, Firefox, Edge, etc.).

## Usage
1. Click the blue primary button (labeled 'Click Me'). Its text will change to 'Clicked!'.
2. Click the red 'Reset' button. The text of the primary button will immediately revert back to 'Click Me'.

## Improvements (Round 2)
In Round 2, the application was significantly enhanced to introduce interaction between multiple elements:

1. **Second Button Implementation:** A new button labeled 'Reset' was added next to the main action button.
2. **Inter-Element Communication:** A JavaScript event listener was implemented on the 'Reset' button. When activated, this listener targets the primary button and programmatically resets its `textContent` back to the stored original state ('Click Me').
3. **Improved Styling:** CSS was updated to better differentiate the buttons (blue for primary action, red for resetting) and enhance the overall visual appeal within a contained structure.

## License
This repository adheres to the standard MIT License.