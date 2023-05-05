# Class 5 Reading Notes

These readings provide more information about how to add good content to our websites.  The first readings cover the different kinds of image files that can be used and their relative strengths and weaknesses.  The CSS readings provide information about how to add color to websites as well as how to select and style fonts that are provided.

## HTML Media

- What is a real world use case for the `alt` attribute being used in a website?

> It will display in the image space when the image cannot be displayed or if it takes a long time to render.

- How can you improve accessibility of images in an HTML document?

> You can improve accessibility by using descriptive alt text.  This will allow a screen reader to read out a description of the image.  Additionally, users can turn off images to reduce data transfer volume in places where bandwidth is expensive.

- Provide an example of when the `figure` element would be useful in an HTML document.

> Figure is useful because you can put an image inside of it and use the fig caption element to provide a caption for your image.  This is better semantically than just putting a p tag below an image element.  The fig caption element tells browsers that the caption describes the content contained in the figure image.

- Describe the difference between a `gif` image and an `svg` image, pretend you are explaining to an elder in your community.

> A gif image is a good choice for images that need to move like a simple animation.  These are commonly used by young people to send funny videos to each other when the image quality is not as important as the message it contains. SVG on the other hand are high quality images that can be shown either small or large with a high degree of detail.  These are used for diagrams or icons on websites that need to be shown at variable sizes and not look bad.

- What image type would you use to display a screenshot on your website and why?

> I would chose a png or webp because I want a lossless format to make sure the text is readable on my screenshot.

## Learn CSS

- Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

> Background color is the color that is applied to empty space where no content exists.  Foreground color is color that is applied to the content itself of whatever we put on the web page.

- Your friend asks you to give his colorless blog website a touch up.  How would you use color to give his blog some character?

> I would help chose a base color that works with the content they are trying to display.  We could base this on other similar websites that my friend likes.  Then I would flesh out the pallette using an online tool.  Then we would use the complementary colors to add interesting visual pop that draws the users attention where we want it to go o the screen.

- What should you consider when choosing fonts for an HTML document?

> I would want to consider whether or not the font I pick will be generally available across all browsers and computers.  I would want to select a web safe font that I can be confident is generally available and will render appropriately anywhere.

- What do `font size`, `font-weight`, and `font-style` do to HTML text elements?

> Font style is used to turn italic text on or off.  Font weight sets how bold the text is.  Font size is used to control how large the font is displayed.

- Describe two ways you could add spacing around the characters displayed in an `h1` element.

> I could use the letter-spacing and word-spacing properties to set the spacing between letters and words within the text.

## Things I want to know more about

- I want to understsand better how rem and em work when sizing fonts.
