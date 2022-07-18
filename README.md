# Tea Cozy
## Summary
This web page is for a fictional tea shop. It is a Codecademy Full Stack Engineer course off-platform project (meaning created outside of the Codecademy website). I was provided a redline image of the web design and the images to be used. I created the web page from scratch using Visual Studio Code, html, css, and flexbox features.
## The Experience
- The lessons leading up to this off-platform project were about responsive design and flexbox. All measurements in the redline design were in px, including some 1000-1200px section widths. Even though this project is about getting comfortable using flexbox, the resulting web page looks good down to 1024 x 768. Below that let the horizontal scrolling begin!
- I learned that you can change the color of a transparent png with a white color to whatever color you want. The logo png Codecademy provided was white and I needed it to be gray like the page color scheme. I found this on stack overflow: `filter: opacity(0.5) drop-shadow(0 0 0 gray) saturate(1000%);` and it worked great!
- The underscore in the links at top right seemed too close to the text to be clearly discernable so I researched how to get some separation between the text and the underscore and found this, also in stack overflow, which worked: `    text-underline-offset: 2px;`.
- Really got to exercise flexbox, using it to align and separate content, especially using `flex-direction: column;` to align and space out content vertically. It is important to remember that the container-level commands are reversed when using flex-direction: column.
- I am using a fixed header, and while working on the links to sections (with ids) I noticed that it seemed that the screen was not being positioned at the top of the sections. I found (can't recall where) and used `scroll-margin-top` to adjust each section being linked to to compensate for the fixed header.
- The redline appears to require that the whole page be darkened and I found a way to do that, but decided that I didn't like the way having the whole page darkened looked. I decided to just darken the locations section to demonstrate the use of the following code:
    background: rgba(0, 0, 0, 0.5) url(../images/img-locations-background.jpeg);
    background-position: top;
    background-repeat: no-repeat;
    background-blend-mode: darken;