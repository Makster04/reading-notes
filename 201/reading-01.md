# [102 OVERVIEW](https://github.com/codefellows/seattle-code-201d108/tree/main/class-01)

## Getting Started
1. **Compose a short poem describing how HTTP sends data between computers.**
* In digital realms where connections thrive,
* A browser sends a message, a quest to derive.
* HTTP request echoes, a plea to deliver,
* Website's essence, a digital river.
* (Thanks to Chat GPT)
* Client and server, a dance they play,
* Through TCP/IP, data finds its way.
* Internet's embrace, a network's glide,
* In bits and bytes, a seamless tide.
2. **Describe how HTML, CSS, and JS files are “parsed” in the browser.** The browser parses the HTML file first **-->** Sends requests back to the server for any CSS files it has found from <link> elements and/or any JavaScript files it has found from <script> elements **-->** Then it parses the CSS and JavaScript.
3. **How can you find images to add to a Website?** You can go to *Google Images*
4. **How do you create a String vs a Number in JavaScript?** For a string you put a sentence in single or double quotes, while for a number you don't. The computer might even think the word you write without quotes is a number.
5. **What is a Variable and why are they important in JavaScript?** A variable is a container for a value, like a number, string, or boolean. They're a key part of JavaScript to manage and manipulate data, making your codes more flexible, readable, and such.
  
## Introduction to HTML
1. **What is an HTML attribute?** While HTML stands for "HyperText Markup Language" and is a markup language, Attributes are part of an element that contains extra info about it that won't appear in the content. 
2. **Describe the Anatomy of an HTML element.** Understanding the anatomy of HTML elements is essential for creating well-structured and valid HTML documents.
3. **What is the Difference between <article> and <section> element tags?**  <article> is specifically for standalone and distributable content, while <section> is a more general container for grouping related content on a page. 
4. **What Elements does a “typical” website include?**
* - <.!DOCTYPE HTML.>: Defines the document type and version of HTML being used.
* - <.HTML.>: The root element that wraps all the content on the page.
* - <.head.>: Contains meta-information about the document, such as the title, character set, stylesheets, and scripts.
* - <.body.>: Contains the main content of the webpage, including text, images, links, and other elements.
* - <.header.>: Represents the header of the webpage, often containing a logo, navigation menu, and other header-related content.
* - <.nav.>: Contains navigation links or menus.
* - <.main.>: Wraps the main content of the webpage, excluding headers, footers, and sidebars.
* - <.article.>: Represents a self-contained piece of content, such as a blog post, article, or news story.
* - <.section.>: Groups related content together, providing a way to structure and organize the page.
* - <.footer.>: Contains footer-related content, often including copyright information, links, or contact details.
* - <.p.>: Represents a paragraph of text.
* - <.h1.>, <.h2.>, ..., <.h6.>: Heading elements, used to define headings of various levels.
5. **How does metadata influence Search Engine Optimization?** 
Metadata plays a big role in SEO by providing info about the content of a webpage. It helps search engines understand the context and relevance of a page's content
6. **How is the <meta> HTML tag used when specifying metadata?** Metadata provides info about the document, such as character encoding, viewport settings, and other important details that browsers and search engines use to interpret the content.

### Miscellaneous
1. **What is the first step to designing a Website?** Define what you want to accomplish with it.
2. **What is the most important question to answer when designing a Website?** What Exaxtly do I want to accomplish?
3. **Why should you use an <.h1.> element over a <.span.> element to display a top level heading?** Its more well-structured, meaningful, and accessible web content.
4. **What are the benefits of using semantic tags in our HTML?**
* - Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
* - Screen readers can use it as a signpost to help visually impaired users navigate a page
* - Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
* - Suggests to the developer the type of data that will be populated
* - Semantic naming mirrors proper custom element/component naming
5. **Describe 2 things that require JavaScript in the Browser?** The *DOM (Document Object Model) API*, which allows you to manipulate HTML and CSS, creating, removing and changing HTML, dynamically applying new styles to your page, etc. Every time you see a popup window appear on a page, or some new content displayed. Also, The *Geolocation API* retrieves geographical information. This is how Google Maps is able to find your location and plot it on a map.
6. **How can you add JavaScript to an HTML document?** You can include JavaScript directly within the HTML file using the <script> tag. 
