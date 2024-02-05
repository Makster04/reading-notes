# [Readings: Audio, Video, Images](https://github.com/codefellows/seattle-code-201d108/tree/main/class-11)
## Video and Audio Content
1. **Explain how the ability to use video and audio on the web has evolved since the early 2000s.** The use of video and audio on the web has evolved from limited compatibility and Flash dominance in the early 2000s to the introduction of HTML5, codec standardization, and the rise of streaming services. Today, native support for <video> and <audio> elements, responsive design, and the potential integration of VR and AR mark the continuing evolution.
2. **Describe the use of the src and controls attributes in the <video> element** The <video> element's src attribute specifies the source URL of the video file, enabling the embedding of video content. The controls attribute, when present, displays browser-built controls (play, pause, volume) to facilitate user interaction with the video.
3. **Why is it important to have fallback content inside the <video> element?** Including fallback content inside the <video> element is essential for reasons such as browser compatibility, error handling, and accessibility. It ensures that users have an alternative means to access media if their browser doesn't support the specified format, preventing a poor user experience.
4. **Write a very short story where <audio> and <video> are characters.** In a short story set in the kingdom of Internetia, <audio> and <video> collaborate as characters to create a multimedia masterpiece. They enchant the audience with a harmonious blend of sound and visuals on the web's grand stage. Mindful of diverse user experiences, they include fallback content to ensure that even browsers not fully supporting their multimedia magic can still provide an enjoyable digital experience for users.
## A Complete Guide To Grid
1. **How does Grid layout differ from Flex?**
* ***Grid Layout:*** Two-dimensional system for creating complex layouts with rows and columns, offering precise control over both dimensions.
* ***Flexbox:*** One-dimensional system, ideal for arranging items in a single row or column, focusing on distributing space along a primary axis.
* ***Usage:*** Grid for comprehensive layouts, Flexbox for simpler, one-dimensional layouts or item arrangements within a container.
2. **Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**
* ***Grid Container:*** The outermost HTML element with display: grid, serving as the container for grid items and defining the grid context.
* ***Grid Item:*** Children of the grid container, elements to be placed and arranged within the grid, capable of spanning multiple rows and columns.
* ***Grid Line:*** Dividing lines forming the grid's structure, with numerical labeling for both horizontal (row) and vertical (column) lines. Items are positioned between these lines, defining their placement in the grid.
## Responsive Images
1. **Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**
* ***Bandwidth Optimization:*** Responsive images help optimize bandwidth usage by delivering appropriately sized images based on the user's device, reducing loading times and data usage.
* ***Improved User Experience:*** Ensures a consistent and visually pleasing experience across various devices, enhancing user satisfaction and engagement.
* ***Search Engine Optimization (SEO):*** Search engines favor responsive websites, and including responsive images contributes to better SEO rankings.
2. **Define the following <img> attributes srcset and sizes. Write an example of how they are used.**
* ***srcset Attribute:*** Specifies a set of image sources with corresponding sizes and pixel densities, allowing the browser to choose the most suitable image based on the user's device characteristics.
* ***sizes Attribute:*** Informs the browser about the expected display size of the image, helping it select the appropriate source from the srcset.
3. **How is srcset more helpful for responsive images than CSS or JavaScript?**
* ***Browser Optimization:*** srcset allows browsers to select the most appropriate image source, reducing unnecessary downloads and optimizing performance.
* ***Automatic Handling:*** Unlike CSS or JavaScript, srcset automatically adapts to various screen sizes and resolutions without requiring manual intervention.
* ***Efficient Bandwidth Usage:*** By providing multiple image options, srcset ensures that devices receive images tailored to their requirements, preventing the download of unnecessarily large files and conserving bandwidth.

* ## Things I want to know more about 
