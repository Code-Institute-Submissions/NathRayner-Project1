### Hello!

#### UX

This page is intended to be a page that is informational based about myself, Nath Rayner.

I have made this page in order to use it as an online CV.

Users for this page are going to be able to see all projects I am currently involved in, find all of my social medias and a direct way to submit their information in order for me to get back in touch.

#### Design Choices

I have gone for a sleek mainly black website, with grey and alice white. During the process of building this website I have made it a little more "plain" with more black than grey as I don't want any users with colour blindness to have a poor experience. So I have stuck with a more "forced darkmode" type of style.

#### Plans for the website:

This website is to be used as an online CV or contact page for myself. I will update it with projects I'm working on and a fresh CV.

This website will be extremely useful as it will provide any potential employeers with all of my details, a way to get in touch with me and a way to instantly get to see my CV. I plan to eventually make the images on the creative page a bit more responsive, maybe starting smaller, then when clicked give information about the picture and who is in it, also make it downloadable with a watermark.

However for now it's a great starting point to give people access to what I'm currently doing and to get involved!

#### Troubles:

- At the start of making this project, I decided on having a nice black/grey/white theme, after consulting with my mentor I downloaded and used WAVE for chrome which said it might be an issue for some visually impared users.

- Navbar staying white, working on a fix

- unable to make one of the main pictures disapear on smaller devices

- collapsed nav bar toggler not working as intended

- prettier has made it so some of the lines have a closing "/" on lines when not needed. This is something that doesn't break the code so has been opted left in.

#### Fixes

I change the color scheme so that it is more friendly for all users.

#### Wireframes

I hand drew all of my wireframes. However if you want to see what they look like, go to the webpage as it has come out pretty much exactly how I drew.

#### Tests:

- Tested to see if nav bar works correctly - minor success, great on desktop, but currently having issues with the collapsable part on mobile devices.

- Test to make sure that all pages are reactive to device sizes - test a success!

- Testing to check to make sure the active page doesn't do anything when hovered over. - Success

- Images load properly and fill 90% of the creative page - Success

- Test to make sure CV opens - success but takes user away from original location - I have now changed this and made the target \_blank in order to create a new tab when looking at the cv.

- Test to make sure form gets submitted correctly - success, however there is currently no website that I can use in order to get the emails from this form, this will be coming when I start hosting on my own domains.

- Tested (for mobile) index.html lighthouse to make sure it's preformance, best practices and accessibility - Performance is great, accessibility decent and need work on best practices.

- Tested (for mobile) creative.html with lighthouse, this page is going to be resource heavy as it has multiple high quality images that were optimised. This page has a low performance score again due to the fact the images are large in file size and high quality, this is something I'm willing to sacrifice as it is important to have the images at a high quality. Accessibility and best practices are both still very good.

- Tested (for mobile) contact.html with lighthouse, as expected this is the best performance from all pages, as it is low in data and most things are just text this page's performance is high, accessibility high and best practice decent. Again even though WAVE suggests that the grey on white is not good for all users (colour blind users) I am choosing to keep this as a design choice.

- Tested (for desktop) index.html, decent performance, accessibility and best practices. Some minor errors that are noted above in the "Troubles" section of this readme.

- Tested (for desktop) creative.html again decent performance, great accessibility and decent best practices - this performance was expected to be lower as for the same reasons on the mobile test.

- Tested (for desktop) contact.html great performance and accessibility and decent best practices - happy with this page on desktop.

Code written:

Some of the code written in this project is borrowed from a lesson via Code Institute - the git repository can be found here "https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4"
