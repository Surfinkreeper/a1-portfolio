--Readme document for *Daniel Salameh*, *dnsalame@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features

* At least one image, with descriptive alt attribute(s)
I have a few images, specifically my headshot and porject thumbnails that are important and have alt text to let
screen readers know what they are. As taught in class, I kept the alt text simple and to the point. With the background
image, I did not include alt text as it is decorative

* Appropriate headings and paragraph text
I have heading 1s be the main title of each section. Any descriptive text in a paragraph block. For my project cards,
the project titles are heading 2s to show that they are a sub heading of the "Projects" heading 1

* Links to external page(s)
Right under my head show I includes a list of buttons that link to external profiles of mine. For now I have my Github, 
Itch.io, and LinkedIn but I plan on adding more ways to contact me. I used `target="_blank"` to make sure these opened in
a seperate tab

(b) CSS features

* Modifying padding and margins to indent content and enhance readability
I have padding and/or margins are almost all my blocks. I noticed in early renditions of the website readability was hard
as text would stick to the side of block. padding helped seperate it from the background. I also separated the separate blocks
using margins through Bootstrap, something that took a little bit of learning. 

* Leveraging Bootstrap CSS helpers such as image shapes and table layouts to display content in a more interesting manner
I used Bootstrap a ton in this project. Mainly I used it for 3 things: Nav bar, pfp image shape, and the projects display.
It helped me format things in a way that reactive to different screen sizes. Specifically the projects I wanted to make sure that
when displaying on a phone, it did not make the projects super small and instead put them in one column

(c) Advanced features

* Creating a more complex page layout, such as including a sidebar or navigation bar
I used a navigation bar to allow the user to hop between different parts of the page. I did not create the about section but that was
my next goal. This navigation bar adjusts to different screen sizes.

* Leveraging nested selectors to specify format
I used nested selectors when created the nav bar. I used `navbar a` and `navbar a:hover` to specify what links look like specifically in the
nav bar but nowhere else.


3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

Most of my potention problems in the accessibility test had to do with the images and their alt text. It was saying that it was not descriptive enough or that
it was not needed. It was also worried about texting being hard to read over the images. I believe that the images don't need much of an explaination as they are
just there to support the text. There is also no text going over the images so the contrast does not matter.

4. How long, in hours, did it take you to complete this assignment?

Roughly 7 hours. A lot of which was spent learning reading W3 and the Bootstrap website.

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

I used [W3 Schools](https://www.w3schools.com/html/default.asp) and [Bootstrap](https://getbootstrap.com/docs/6.0/utilities/flex/) to learn
to code in HTML and then how to do it easier in Bootstrap. It was a lot of content but I tried to learn it before even coding much of the assignment.
I did use AI but not to produce any code, I would query Claude as documentation lookup telling me what tags were good for what scenarios and how they are used.

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

None!

7. Is there anything special we need to know in order to run your code?

Make sure you extract all the zipped file for the style.css to load properly! I am excited to keep working on this portfolio. Right now my current portfolio on danielsalameh.com is built in framer and I am paying to have it hosted.
In the future I want to keep coding this portfolio and host it myself.