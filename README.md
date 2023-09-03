# Weekly test 3 (Jordan Shoe site)

## Global Styles
- `*`: Resets margin, padding, and box-sizing for all elements to ensure consistent styling.

## Header Section (`.offer` and `nav`)
### `.offer` Selector
- `background`: Creates a gradient background for the offer section.
- `padding`: Adds padding to the offer section for spacing.
- `color`: Sets text color to white.
- `text-align`: Centers text in the offer section.

### `nav` Selector (Navigation Bar)
- `background-color`: Sets the background color of the navigation bar.
- `text-align`: Aligns text in the navigation bar to the center.
- `padding-block`: Adds padding to the top and bottom of the navigation bar.
- `position: sticky; top: 0;`: Makes the navigation bar stick to the top of the viewport when scrolling.
- `color`: Sets text color to white.

#### Navigation Links (`nav h5`)
- `display: inline-block;`: Makes the navigation links display inline-block.
- `margin-inline`: Adds margin between navigation links.
- `cursor: pointer;`: Changes the cursor to a pointer on hover.

#### Search Input (`nav input`)
- `border`: Removes borders from the input field.
- `width`: Sets the width of the input field.
- `font-size`: Increases the font size of the input field.
- `outline`: Removes the outline when the input is focused.

#### Search Icon (`nav span`)
- `background-color`: Adds a background color to the search icon.
- `padding`: Adds padding to the search icon.
- `cursor: pointer;`: Changes the cursor to a pointer on hover.

## Sale Section (`.sale`)
- `background`: Sets a background image for the sale section.
- `background-position`, `background-repeat`, `background-size`: Controls background image properties.
- `padding`: Adds padding to the sale section.
- `color`: Sets text color to white.
- `font-size`: Sets the font size for the sale section header.

### Sale Header (`.sale header`)
- `width`: Styles the header within the sale section.
- `background-color`: Styles the background of the header.
- `padding`: Adds padding to the header.

## Trending Section (`.trending`)
- `padding`: Adds padding to the trending section.
- `background-color`: Sets the background color of the trending section.

### Trending Wrapper (`.trending-wrapper`)
- `padding`: Adds padding to the wrapper for trending items.
- `background-color`: Styles the background of the wrapper.
- `margin-block`: Adds margin to the wrapper.
- `color`: Sets the text color within the wrapper.

#### Trending Cards (`.trending-card`)
- `height`, `width`: Defines the size of individual cards.
- `display: inline-block;`: Makes cards display inline-block.
- `background-color`: Sets the background color of cards.
- `color`: Sets text color within cards.
- `padding`: Adds padding to cards.

##### Trending Card Images (`.trending-card img`)
- `width`, `height`: Styles images within the trending cards.

## Jordan History Section (`.jordan-history`)
- `background`: Creates a gradient background for the Jordan history section.

### Jordan History Container (`.container`)
- `width`, `height`: Styles the container for the Jordan history section.
- `position`: Sets the position of the container.
- `overflow`: Defines overflow behavior.

#### Jordan History Wrapper (`.wrapper`)
- `width`, `height`: Styles the wrapper within the container.
- `padding`: Adds padding to the wrapper.
- `margin`: Sets margins for the wrapper.
- `background`: Styles the background of the wrapper.
- `margin-top`: Sets top margin for the wrapper.
- `box-shadow`: Adds a shadow effect to the wrapper.

##### Description (`.description`)
- `max-width`: Sets the maximum width of the description.
- `color`: Sets text color within the description.

###### Description Headings (`.description h1`)
- `margin-bottom`: Adds margin at the bottom of headings.
- `font-size`: Sets the font size of headings.

###### Description Paragraphs (`.description p`)
- `font-size`: Sets the font size of paragraphs.
- `margin-bottom`: Adds margin at the bottom of paragraphs.
- `line-height`: Defines line height within paragraphs.

##### Shoe Image (`.shoe`)
- `position`: Sets the position of the shoe image.
- `right`, `top`: Defines the position of the shoe.
- `width`, `height`: Styles the dimensions of the shoe image.
- `border-radius`: Rounds the corners of the shoe image.
- `box-shadow`: Adds a shadow effect to the shoe image.

##### Hover Effect for Shoe Image (`.shoe:hover`)
- `width`: Increases the width of the shoe image on hover.
- `height`: Increases the height of the shoe image on hover.
- `right`: Adjusts the position of the shoe image to the right on hover.
- `top`: Adjusts the position of the shoe image downwards on hover.
