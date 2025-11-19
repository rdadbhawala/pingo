# Requirements for "Pingo", the image Bingo generator.

## Overview
Pingo is an html page that generates a given number of Bingo cards using images. All necessary stuff should be present in a single html file itself, including the stylesheets and javascript code.

## HTML Layout
The pingo layout consists of 2 vertical sections. A smaller left section for user inputs and a larger right section for displaying the generated Bingo cards.

### Left Section (User Inputs)
- Input field to specify the number of Bingo cards to generate (default: 1, max: 100).
- Input field to specify the number of rows and columns for each Bingo card (default: 5x5).
- Image upload area to upload multiple images.
- Input field to specify the title of the Bingo Card as the header.
- Input field to specify the footer text of the Bingo Card.
- A button labeled "Generate" to trigger the generation process.
- A button labeled "Print" to print the generated Bingo cards.
- Include error handling to manage cases where there are insufficient images or invalid inputs.
- Errors should be displayed clearly to the user above the input fields.

### Right Section (Bingo Cards Display)
- This is the area to display the generated Bingo cards in a grid format.
- Each Bingo card should have the specified title at the top and footer text at the bottom.
- Each cell in the Bingo card should contain a randomly selected image from the uploaded images.
- When the Print button is pressed, the page should be formatted for printing, ensuring that each Bingo card fits on a separate page.
- The layout should be responsive and visually appealing.
- Use CSS to style the Bingo cards, buttons, and input fields for a clean and user-friendly interface.
- Ensure that the generated Bingo cards are clearly visible and well-organized.
- The images should be scaled appropriately to fit within the cells of the Bingo cards without distortion.

## Functionality
- The "Generate" button should validate the inputs and generate the specified number of Bingo cards using the uploaded images.
- Each Bingo card should be unique, with images randomly placed in the grid.
- The "Print" button should open the browser's print dialog and format the page for printing.
- Ensure that the generated Bingo cards are printable and maintain their layout when printed.
- Implement error handling to manage cases where there are insufficient images or invalid inputs, displaying appropriate messages to the user.
- Optimize the performance to handle the generation of multiple Bingo cards efficiently.
- Ensure compatibility with major web browsers.
- Include comments in the code for clarity and maintainability.
- Note that this entire functionality is to be implemented within a single HTML file, without relying on external resources or a server.

# Additional Requirements

## Iteration 1

- The name of the file, without the path and the extension, should appear at the bottom of each image.
- The page should be formatted for A4 size.
- On clicking the "Generate" button, specified number of Bingo cards should be randomly generated in the right section, such that each card appears as a separate page when printing.
- In the footer, add a page number for each Bingo card.
- Scale the image in the aspect ratio to fit within the square it belongs.
- After the print and generate buttons, add simple instructions on how to use this file.
