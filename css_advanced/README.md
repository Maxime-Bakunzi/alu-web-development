# CSS Styles README

This README.md file provides a summary of the CSS styles used in the project.

## :root

- `--primary`: Sets the primary color to `hsla(214, 71%, 9%)`.
- `--secondary`: Sets the secondary color to `rgba(114, 108, 108, 0.4)`.

## body

- `margin: 0;`: Removes the default margin from the body element.
- `padding: 0;`: Removes the default padding from the body element.
- `font-family: Arial, Helvetica, sans-serif;`: Sets the font family for the body text.
- `background-image: url(images/BitmapReal.png);`: Sets the background image for the body element.
- `background-repeat: no-repeat;`: Specifies that the background image should not repeat.

## .overlay

- `position: absolute;`: Sets the positioning of the overlay element to absolute.
- `top: 0;`: Sets the top position of the overlay element to 0.
- `left: 0;`: Sets the left position of the overlay element to 0.
- `width: 100%;`: Sets the width of the overlay element to 100%.
- `height: 990px;`: Sets the height of the overlay element to 990 pixels.
- `background: linear-gradient(var(--secondary) 10px, var(--primary));`: Sets a linear gradient background for the overlay element.
- `z-index: -1;`: Sets the z-index of the overlay element to -1, placing it behind other elements.

## header

- `color: #fff;`: Sets the text color of the header element to white.
- `text-align: center;`: Centers the text content of the header element.
- `padding: 20px;`: Adds padding to the header element.
- `margin-top: 20px;`: Adds top margin to the header element.
- `margin-left: 120px;`: Adds left margin to the header element.
- `margin-right: 120px;`: Adds right margin to the header element.

## .logo

- `float: left;`: Floats the logo element to the left.

## .logo img

- `width: 150px;`: Sets the width of the logo image to 150 pixels.
- `height: auto;`: Sets the height of the logo image to auto, maintaining its aspect ratio.

## .pages

- `text-align: right;`: Aligns the content of the .pages element to the right.

## .pages a

- `color: #fff;`: Sets the text color of the links in the .pages element to white.
- `text-decoration: none;`: Removes the underline decoration from the links.
- `margin-left: 20px;`: Adds left margin to the links.
- `font-family: Verdana, Geneva, Tahoma, sans-serif;`: Sets the font family for the links.
- `font-weight: bold;`: Sets the font weight to bold for the links.

## .pages a:hover

- `transform: scale(2);`: Enlarges the size of the links on hover.

## .banner h1

- `font-size: 90px;`: Sets the font size of the heading inside .banner to 90 pixels.
- `color: #fff;`: Sets the text color of the heading to white.
- `text-align: center;`: Centers the text content of the heading.
- `margin-top: 150px;`: Adds top margin to the heading.
- `margin-bottom: 0;`: Removes bottom margin from the heading.

## .banner p

- `color: #fff;`: Sets the text color of the paragraph inside .banner to white.
- `text-align: center;`: Centers the text content of the paragraph.
- `font-size: 13px;`: Sets the font size of the paragraph to 13 pixels.
- `margin-bottom: 30px;`: Adds bottom margin to the paragraph.
- `margin-top: 10px;`: Adds top margin to the paragraph.

## .banner-people h2

- `font-size: 24px;`: Sets the font size of the heading inside .banner-people to 24 pixels.
- `color: #fff;`: Sets the text color of the heading to white.
- `text-align: center;`: Centers the text content of the heading.
- `margin-top: 210px;`: Adds top margin to the heading.
- `margin-bottom: 60px;`: Adds bottom margin to the heading.

## .banner button

- `display: block;`: Makes the button a block-level element.
- `width: 170px;`: Sets the width of the button to 170 pixels.
- `margin: 0 auto;`: Centers the button horizontally.
- `background-color: #C271FF;`: Sets the background color of the button.
- `padding: 10px 20px;`: Adds padding to the button.
- `border-radius: 20px;`: Rounds the corners of the button.
- `text-align: center;`: Centers the text content of the button.
- `text-decoration: none;`: Removes any text decoration from the button.
- `box-shadow: none;`: Removes any box shadow from the button.
- `font-size: 12px;`: Sets the font size of the button to 12 pixels.
- `color: #fff;`: Sets the text color of the button to white.

## .banner-people div

- `display: inline-block;`: Sets the display property of the div elements inside .banner-people to inline-block.
- `margin-left: 70px;`: Adds left margin to the div elements.
- `margin-right: 70px;`: Adds right margin to the div elements.

## .banner-people div div img

- `width: 120px;`: Sets the width of the images inside .banner-people div div to 120 pixels.
- `height: auto;`: Sets the height of the images to auto, maintaining their aspect ratio.
- `border-radius: 50%;`: Rounds the corners of the images.

## .banner-people div div h3

- `color: #fff;`: Sets the text color of the h3 elements inside .banner-people div div to white.
- `font-size: 16px;`: Sets the font size of the h3 elements to 16 pixels.
- `margin: 5px;`: Adds margin to the h3 elements.
- `padding: 0;`: Removes padding from the h3 elements.

## .banner-people div div p

- `color: #fff;`: Sets the text color of the p elements inside .banner-people div div to white.
- `font-size: 12px;`: Sets the font size of the p elements to 12 pixels.
- `text-align: center;`: Centers the text content of the p elements.
- `margin: 2px;`: Adds margin to the p elements.
- `padding: 0;`: Removes padding from the p elements.
- `font-style: italic;`: Sets the font style of the p elements to italic.

## .quotes

- `margin: 0;`: Removes margin from the .quotes element.
- `padding: 0;`: Removes padding from the .quotes element.
- `width: 100%;`: Sets the width of the .quotes element to 100%.
- `height: 300px;`: Sets the height of the .quotes element to 300 pixels.
- `background-color: #C271FF;`: Sets the background color of the .quotes element.

## .quotes-div

- `padding-left: 250px;`: Adds left padding to the .quotes-div element.
- `padding-top: 50px;`: Adds top padding to the .quotes-div element.

## .quotes div img

- `float: left;`: Floats the images inside .quotes div to the left.
- `padding-right: 20px;`: Adds right padding to the images.
- `border-radius: 50%;`: Rounds the corners of the images.

## .quotes div div blockquote

- `padding-top: 20px;`: Adds top padding to the blockquote elements.
- `width: 700px;`: Sets the width of the blockquote elements to 700 pixels.
- `color: #fff;`: Sets the text color of the blockquote elements to white.
- `line-height: 20px;`: Sets the line height of the blockquote elements to 20 pixels.
- `font-family: Verdana, Geneva, Tahoma, sans-serif;`: Sets the font family for the blockquote elements.

## .quotes div div p

- `color: #fff;`: Sets the text color of the p elements inside .quotes div div to white.
- `font-weight: bold;`: Sets the font weight of the p elements to bold.

