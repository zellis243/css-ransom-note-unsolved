# The Ransom Note Assignment

The CSS text styling assignment.

## Introduction

Welcome to the intriguing world of typography and design with CSS! In this assignment, we challenge you to unleash your creative genius by crafting a captivating ransom note with unique styles for each letter. Your task is to bring harmony to chaos, ensuring every character shines with its individuality. Embrace the power of typography and let your imagination run wild as you transform a simple note into a mesmerizing visual masterpiece. Get ready to captivate the eye and impress us with your distinctive approach to letter styling.

Best of luck on this typographic adventure!

To preview the app, simply click the "Go Live" button found in the VSCODE status bar. This will open your webpage in your browser.

If you are not using VSCode you can install and run the "live-server" npm package following the list of commands:

- Use `npm i live-server` to install the live-server package
- Use `npm run live-server` or `npx live-server --port=5551` to run the live-server. The port number should be 5551 strictly.

The live-server installation video: Video
The live-server NPM package page: Link

## Learning objectives

This assignment should prove that a student is able to:

- Use the color CSS property to set the color of the text
- Change the text (font) styles using CSS rules to specify:
  - the size of the characters
  - parameters of the font
  - text transformations
  - text decorations
- Include and apply a custom font or a collection of fonts from Google Fonts

## Standard requirements

- [ ] Fork the project to your github account
- [ ] Clone the project to your computer
- [ ] Open the project in VSCode with `code <cloned_repo_folder_name>`
- [ ] **This Assignment is NOT tested. You can use all the desired creativity!**
- [ ] All the tasks of the "Specific requirements" section MUST be solved
- [ ] **The project's file/folder structure should NOT be edited!**
- [ ] **The index.html file should NOT be edited!** The only acceptable change are additional classes added to elements.
- [ ] VSCode IDE MUST have 0 problems listed
- [ ] The code of the index.html and styles.css should pass the W3C validation (Feel free to use either the "[w3c web validator](https://marketplace.visualstudio.com/items?itemName=CelianRiboulet.webvalidator)" VSCode extension or the "[Online w3c Markup Validation Service](https://validator.w3.org/#validate_by_input)")
- [ ] The code MUST be formatted with Prettier.
- [ ] Push the changes to the Github repo, when finished.
- [ ] Submit a .txt file with the Github repo url.

## Specific requirements

- [ ] Check out the sample image of a completed assignment to see the expected outcome in /assets/images/. You don't need to imitate it exactly, feel free to use any desired letter styles.
- [ ] You should have at least 10 different styles for the letters. A "unique" style means a distinct combination of:
  - Font size
  - Font color
  - Font weight
  - Font decoration
  - Font transformation
  - Font family
- [ ] Set the font size using fixed pixel values.
- [ ] Use at least two color systems of your choice for setting the color (hex, rgb, hsl, etc.).
- [ ] Ensure each font weight value from the given list is used at least once:
  - Bold
  - Normal
  - 400
  - 700
- [ ] Each text decoration value from the provided list should be used at least once:
  - Underline
  - Line-through
  - Overline
  - None
- [ ] Include capitalized letters.
- [ ] Style every letter in the message.
- [ ] Group selectors with the same styles.

  You can group the letter selectors by the common styles:

  ```CSS
  .letter-one,
  .letter-two {
    color: yellow;
  }
  ```

  You can also add classes to target a group of HTML elements to apply the same set of styles:

  ```CSS
  .yellow-letter {
    color: yellow;
  }
  ```

  ```HTML
  <div class="yellow-letter letter-one">L</div>
  <div class="yellow-letter letter-two">W</div>
  ```

- [ ] The HTML document should NOT have inline styles.
- [ ] There are 3 Google Fonts connected to the project. Find and connect 3 more random fonts from Google fonts. Feel free to use [this article](https://www.webdesignerdepot.com/2021/09/21-exceptional-google-fonts-you-probably-havent-discovered-yet/) or the [Google Fonts](https://fonts.google.com/) platform for the fonts inspiration.
