# Class 1 Reading Notes

These readings matter because it forms the foundation of understanding web development.  The basics of HTML, CSS, and JavaScript are required for creating the structure of a site, the styling, and any interactable or dynamic parts of the site.

## Getting Started

- Compose a short poem describing how HTTP sends data between computers.

> The client requests a copy of the page from the server.  Hopefully this is easy to understand for the casual observer.  The server responds and sends data in packets.  Hopefully the site designer remembered to close all their curly brackets.  The clients browser then parses and displays the page.  The CSS link tells us if the sites background is beige.

- Describe how HTML, CSS, and JS files are "parsed" in the browser.

> HTML files get parsed first, requests are sent back to the server for any linked element references like CSS stylesheets and scripts.  The browser than creates an in-memory structure and subsequently executes JavaScript.  After this, a visual representation of the page is created on the screen.

- How can you find images to add to a website?

> From google images, you can click on the tools button and use the usage rights option. If you select Creative Commons Licenses, you can use those images.

- How do you create a string vs a number in JavaScript?

> JavaScript determines the data type of a variable when it is assigned to a value.  For strings, quotes should surround the characters to indicate that it is a string.  To assign a number, no quotes should be included and only numerical input provided.

- What is a variable and why are they important in javascript?

> Variables are containers that can store values. They are necessary to store values that can change allowing us to do dynamic things with our websites.

## Introduction to HTML

- What is an HTML attribute?

> An HTML attribute is extra information about the element that doesn't show up in the content.

- Describe the anatomy of an HTML element.

> The anatomy of an HTML element is the opening tag, the content, and the closing tag.

- What is the difference between \<article> and \<section> element tags?

> Article is used to indicate related content that makes sense without the rest of the page.  Section would be used to group a part of the page that contains a single piece of functionality.  Articles themseleves could contain sections within them.

- What elements does a typical website include?

> A typical website will include a header, a nav bar, main content, sidebar, and a footer.

- How does metadata influence SEO?

> The description metadata is used for search engine results.  This will show up in the search engine results so it is important to include and be descriptive about the page's content.

- How is the \<meta> HTML tag used when specifying metadata?

> The meta html tag is used within the \<head> tag to provide data related to the site that won't be displayed in the browser.  Some examples are the sites encoding, author and description, open graph data, and many others.  These are all specified through attributes within a meta element tag.

## How To Start a Design Website

- What is the first step to designing a website?

> Define what you want to accomplish with the site.  It is important to have a clear goal and vision.

- What is the most important question to answer when designing a website?

> What exactly do I want to accomplish?

## Semantics

- Why should you use an \<h1> element over a \<span> element to display a top level heading?

> We should use an h1 element because HTML code should represent the content that will be populated and not just for styling.  The H1 heading indicates that the following content is the top level content of my page whereas the span element gives no such indication.

- What are the benefits of using semantic tags in our HTML?

> It helps with search engine optimization, makes finding blocks of code much easier, helps visually impaired people navigate the page, and helps the developer to structure the content that will be populated.

## What is JavaScript?

- Describe 2 things that require JS in the browser:

> Two things that would require JS to run in the browser are storing valuable pieces of information in variables like the users name, and performing operations on text that is displayed on the page.

- How can you add JavaScript to an HTML document?

> JavaScript is added to an HTML document using the \<script> element.

## Things I want to know more about

- Do all websites have a single IP address? What if the associated data lives on multiple servers? Does DNS handle multiple IP's for the same domain name?
- How do servers handle massive amounts of requests happening at the same time (google or other very popular websites)?
- What are some popular forms of project ideation?

## Reading Page Links

- [Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
- [HTML Document Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
- [Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)
- [How to Start a Design Website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)
- [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [What is JavaScript?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
