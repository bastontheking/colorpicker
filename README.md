# Color Picker

This is a simple yet extremely useful project I created to facilitate color selection and visualization for my personal projects. I currently use this tool in my daily work, and it is available online on my website: [https://baston.dev/colorpicker](https://baston.dev/colorpicker).

## Description

The **Color Picker** is a web application that offers the following features:

- **Interactive Color Wheel:** Intuitively select a color using the [iro.js](https://iro.js.org/) library.
- **Transparency Control:** A custom slider allows you to adjust the color's transparency (alpha channel). This slider can be enabled or disabled as needed.
- **Color Preview:** A preview area displays the selected color in real time.
- **Display of Color Values:** The color values are shown in three formats:
  - **HTML:** Hexadecimal representation of the color.
  - **RGB[A] (0-255):** RGB values, and optionally the alpha value on a scale from 0 to 255.
  - **RGB[A] (Float):** RGB values in float format (between 0 and 1), and optionally the alpha value.

Additionally, simply click on any of the text fields to copy the corresponding value to the clipboard, with visual feedback via a tooltip.

## Technologies Used

- **HTML5 & CSS3:** Page structure and style customization, featuring a dark theme.
- **Bootstrap 5.3.0:** For creating a responsive and stylish layout.
- **iro.js:** Implementation of the interactive color wheel.
- **JavaScript:** For dynamic interaction with the page elements, such as updating the color, controlling the alpha slider, and copying values to the clipboard.

## How It Works

1. **Select a Color:** Use the color wheel to choose your desired color.
2. **Adjust Transparency:** If needed, enable the alpha slider by checking "Enable Alpha" and adjust the transparency level.
3. **Preview:** The selected color is displayed in the preview area.
4. **Copy Values:** Click on any field (HTML, RGB[A] 0-255, or RGB[A] Float) to copy the corresponding value to the clipboard.

## Personal Use

I personally use this Color Picker because of its practicality and efficiency when choosing colors for my projects. It has proven to be an indispensable tool in my workflow, and therefore, I decided to make it available online on my website: [https://baston.dev/colorpicker](https://baston.dev/colorpicker).

## How to Run

To run the project locally:

1. Download or clone the repository.
2. Open the `index.html` file in your preferred browser.
