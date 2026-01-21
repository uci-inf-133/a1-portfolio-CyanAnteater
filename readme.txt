--Readme document for Rina Taing, rinat1@uci.edu--

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
1. I added a profile image of myself (index.html) and added a relevant photo/image/screenshot for each of my 3 portfolio works (portfolio.html). 
All of these have an alt attribute that briefly explain what the image is of.
2. I added headings and paragraph text to the main body of the index.html and portfolio.html pages. Various heading sizes were also used to add variety to the pages' looks.
3. The navbar at the top allows you to click and navigate across the index.html, portfolio.html, and contact.html pages. 
4. I added a <footer> to all 3 of my pages so it looks a bit more professional.
5. I used Google Material Icons' "code symbol" (used in the navbar as a "brand icon") and the "mail" icon in the contact.html page.
6. I added a link that goes to my PDF resume (hosted on Google Drive) on index.html, and a link that goes to the A1 project rubric on portfolio.html. 

(b) CSS features
1. I modified padding and margins of cards and images to help with visual layout and readability across the 3 pages.
2. I modified the color of the A1 project rubric link found in portfolio.html so the color scheme was more consistent with my overall website palette.
3. I used Bootstrap's table layout to help structure the textual content in the "quick facts" card in index.html.
4. I imported the "Bitter" Google Font found here with fallbacks to similar looking fonts: 
https://fonts.google.com/share?selection.family=Bitter:ital,wght@0,100..900;1,100..900


(c) Advanced features
1. A navbar was added to the top of all 3 of my pages so the user had an intuitive way of navigating through the pages. Using Bootstrap allowed me to make it so that
when the screen size becomes small, a hamburger menu icon appears so that a dropdown menu appears to navigate too!
2. The contact form on contact.html uses a form tag so it can accept an email and message. I also made it so that if you type in an invalid email or try to hit "submit" when
the fields are empty/missing, the browser does a check and will provide a warning saying "email is missing" or "email is missing @ sign" etc. I thought this was pretty cool!



3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.
Yes, I did ignore flagged "potential problems" from AChecker. A lot of the "potential problems" it flagged across my 3 pages were similar (ie those generated from my navbar, which exists across all 3 pages) so there are duplicate “potential problems” that were flagged.

Categories of “Potential Problems”
Out of the flagged items, those pertaining to visual or aesthetic “issues” was one category. For example, AChecker marked my usage of the Google Icons to be "decorative", "having alt text that doesn't convey the same info as the image filename", "color might be hard to see", and other trivial things regarding my image/font choices. I feel that the alt descriptions I provided are sufficient enough to give users a heads-up on what the placed image is meant to be. I also tested the color layout I have, and I believe they have a high enough color contrast to see things clearly. About 1/3 of the flagged items pertained to these kinds of “aesthetic” problems. Upon reading some of the “learn more” pages for each of these problems, it appeared these sorts of problems would be flagged “unconditionally” as conducting manual human review is necessary to evaluate visual elements.

Another category of issues were “code format” ones. For example, AChecker said that my hyperlink addresses were "not meaningful" or "too long". I don’t really have control over these, so there’s nothing much that I can do. To compensate, I made sure that the associated display text was descriptive/relevant to where the links redirected you to, so I think it's ok to ignore this one. About 1/3 of the flagged items pertained to these problems with my links I put in my <a> tags.

A third category of issues were “navigation”/”enabling shortcut” issues. AChecker said that I could be missing navigation hacks (ie “skip to content”) or didn’t use headers to separate sections on my page. I feel like because the page is relatively short and doesn't contain too many sections, adding navigation hacks/making my website support those would be overkill since you might not be able to tell if you even "skipped" to a particular section of content on the page (since everything is pretty much viewable on a standard screen with minimal scrolling already). I also felt that some of the suggestions AChecker brought up were a bit outside my skill level, so I did make an initial attempt to try to resolve these. About 1/3 of the flagged items pertained to navigation-related topics.

For the contact.html, I got slightly more "potential problems" that fell into another "manual review" type of category:
AChecker said that the form may not give helpful warning messages on invalid/required fields. However when I tested each combination of invalid inputs, the warning messages I got from Chrome (my web browser), seemed very descriptive to me. They told me exactly what I needed to fix to create a "correctly filled out form", so I didn't think I would need to go edit and add my own custom messages. Also, if the browser offers validation checking, I feel like it should've already been vetted for accessibility (else it wouldn't be offered).

Note that despite the above, I did pass all of the checkers with a green mark with no “known” or “likely” warnings/errors. 

4. How long, in hours, did it take you to complete this assignment?
This project took me about 34 hours to complete. I allocated at least 2 hours a day since the assignment release date to work on learning HTML/CSS and coding the actual website up. 
On certain days, I would spend upwards of 5-6 hours trying to debug and add in elements. Writing the readme and finalizing the checker scores also took 5 hours too. 

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)
The main online resources I used were the following:

https://www.codecademy.com/enrolled/courses/learn-html
This CodeCademy course was used to help me get a grasp on understanding what HTML is, how to use the tags and elements to create content on a page, and some of the syntax associated with the HTML language. I got through 80% of the course before I decided that it was time for me to move onto learning CSS.

https://www.codecademy.com/enrolled/courses/learn-css
This CodeCademy course was used to help me get a grasp on understanding key concepts and principles in CSS. I got through to like 62% of the course, so I learned a decent amount through this to get a good enough footing when working on A1.

https://www.w3schools.com/html/html5_semantic_elements.asp
This W3 Schools website on HTML semantic elements was consulted to allow me to see whether I could incorporate these to hit the first section of the rubric. Based on what I read in the article, I looked to see which semantic tags made the most sense for me to use; this is how
I got inspiration to include the <footer> tag in my pages (I didn't know that it existed prior). 

https://inf133.netlify.app/html-tutorial.html
The content on this website from discussion on 1/16 was also consulted. The live examples embedded on the page were really helpful since I was able to see how a particular snippet of code would render on a website. Some of the code on this was referenced when I made my website 
(ie the "The Three Pillars of Web Development" section with the card layouts).

https://getbootstrap.com/docs/5.3/components/navbar/
This Bootstrap page on the Navbar implementation was referenced to make my own navbar. 

https://getbootstrap.com/docs/5.3/forms/form-control/
This Bootstrap page on forms and handling input was referenced to make my own form in the contact.html page. I learned about built-in form checking from a simple Google query after in order to get my form to the state it is in currently.

https://getbootstrap.com/docs/5.3/components/buttons/#disabled-state
This Bootstrap page on button configurations was referenced to include my own button on the contact.html page. I didn't do anything advanced with my button, so this was mostly used just to see what types of buttons existed so I could get ideas.

Besides the links provided above, I also used ChatGPT to explain concepts surrounding "best practices" for accessibility, flex containers/containers and grids, and for what the conventional rules are when writing HTML/CSS. The queries I gave ChatGPT were framed as "why does this work like this", "how do I...", or "what is..." types. I then asked follow ups to give me further examples because sometimes what it was explaining made no sense/was too abstract for me. Overall, I used the LLM like an agent (ie as if it were a tutor/experienced web developer) that could guide me through HTML/CSS concepts and common pitfalls. 
When I coded the website up in VSCode (I wanted to work in an IDE and have access to reformatting tools), I did not use any code-autocomplete or AI/Copilot assistance. 


6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
I did not discuss anything with my classmates or people outside of this class for the assignment. I did however, attend 3 of the office hours so I met with TAs and asked them for their opinion on my website layout and design. 
In those office hour sessions, we also discussed how I could better incorporate using Bootstrap and grid layouts, as my early draft of the website didn't utilize it as much as I am currently. I was also struggling to get the responsiveness to work, so we talked about strategies on how I could add more page-responsiveness. 


7. Is there anything special we need to know in order to run your code?
I do not think so.
