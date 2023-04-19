# Class 5 Design Web Pages with CSS Notes

## General Notes

### What is CSS

CSS (Cascading Style Sheets) is used to provide style elements for websites. CSS allows us to define the rules specifying groups of styles that should be applied to particular elements or groups of elements on our web page.  We can check the MDN documentation for any specific CSS element to see which browsers are currently compatible as implementation is not uniformly deployed across all browsers.

### How to Add CSS

There are 3 ways of inserting a style sheet.  External, internal, and inline.  With external, your HTML must contain a reference to the external style sheet file (linked in the head section).  Internal style sheet may be used if one single HTML page has a unique style.  Internal styles are defined within the style element in the head section of the html page.

### CSS Color

The color property specifies the color of text. It can be set with HSL values, HSLA values, hex values, rgb values, or rgba values.

## Answer

- What is the purpose of CSS?

> We use CSS to provide the style elements to web pages.  HTML will format things with the default format settings of style elements.  CSS allows us to control exactly how HTML elements will appear on the page.

- What are the three ways to insert CSS into your project?

> - External CSS
> - Internal CSS
> - Inline CSS

- Write an example of a CSS rule that would give all \<p> elements red text.

> `p {color:red;}
