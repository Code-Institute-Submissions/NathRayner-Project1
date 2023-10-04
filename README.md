### Hello!

![These are the finalised images of the website](/assets/images/am-i-responsive.jpg)

Above is the finished website. I'm pretty happy with it but have small bits I look forward to improving.

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

#### Wireframes

##### Desktop
![Wireframe for desktop index.html](/assets/images/wireframes/Wireframe-index.jpg)
![Wireframe for desktop creative.html](/assets/images/wireframes/wireframe-creative.jpg)
![Wireframe for desktop contact.html](/assets/images/wireframes/wireframe-contact.jpg)

##### Mobile

![Wireframe for mobile of index and creative.html](/assets/images/wireframes/mobile-wireframe.jpg)


#### User Stories

Possible user 1: As a Producer of film I would like to see Nath's IMDb credits - I can do so by looking at the footer, the Why Nath section on the index.html and ask for them via the contact page.

Possible user 2: As a fan of Nath's work I would like to follow his socials, I can do that by looking at the footer on any page and selecting which solcial I would like to follow from there.

Possible user 3: I have a role available on my team, I have been told to have a look at Nath and have been provided with his website, I can look through his past work Via downloading his CV from the footer, or the nav bar and see what personal projects he has been working on via his creative page.

Possible user 4: I have been looking for photography to use for my own app/website, I can see on Nath's creative page photo's that he has taken - I can then go into the contact part of the website to then ask Nath for permission to use these photos and get the raw images from him myself.

Possible user 5: I have a github project that I need more hands on deck for, I see Nath has a github social tag, I can then use this social link to get to Nath's github and see if he could work with me on this next project.


#### Troubles:

- At the start of making this project, I decided on having a nice black/grey/white theme, after consulting with my mentor I downloaded and used WAVE for chrome which said it might be an issue for some visually impared users.

- unable to make one of the main pictures disapear on smaller devices

- collapsed nav bar toggler not working as intended

- prettier has made it so some of the lines have a closing "/" on lines when not needed. This is something that doesn't break the code so has been opted left in.

#### Fixes

- I change the color scheme so that it is more friendly for all users.

- Was using incorrect code to make one of the index.html photos to disapear on smaller decives, have now changed that code to the correct one.

- Removed the collapseble nav bar toggler on smaller devices and have changed it so just the icons appear instead


#### Wireframes

I hand drew all of my wireframes. However if you want to see what they look like, go to the webpage as it has come out pretty much exactly how I drew.

#### Tests:

- Tested to see if nav bar works correctly - minor success, great on desktop, but currently having issues with the collapsable part on mobile devices.

- Test to make sure that all pages are reactive to device sizes - test a success!

- Testing to check to make sure the active page doesn't do anything when hovered over. - Success

- Images load properly and fill 90% of the creative page - Success

- Test to make sure CV opens - success but takes user away from original location - I have now changed this and made the target \_blank in order to create a new tab when looking at the cv.

- Test to make sure form gets submitted correctly - success, however there is currently no website that I can use in order to get the emails from this form, this will be coming when I start hosting on my own domains.

- Tested (for mobile) index.html lighthouse to make sure it's preformance, best practices and accessibility - Performance is okay, accessibility great and okay best practices.
![Lighthouse score for mobile index.html 71-97-83](/assets/images/lighthouse/lighthouse-desktop-index-mobile.jpg)

- Tested (for mobile) creative.html with lighthouse, this page is going to be resource heavy as it has multiple high quality images that were optimised. This page has a low performance score again due to the fact the images are large in file size and high quality, this is something I'm willing to sacrifice as it is important to have the images at a high quality. Accessibility and best practices are both still very good.
![Lighthouse score for mobile creative.html 70-94-83](/assets/images/lighthouse/lighthouse-desktop-creative-mobile.jpg)

- Tested (for mobile) contact.html with lighthouse, as expected this is the best performance from all pages, as it is low in data and most things are just text this page's performance is high, accessibility high and best practice decent. Again even though WAVE suggests that the grey on white is not good for all users (colour blind users) I am choosing to keep this as a design choice.
![Lighthouse score for mobile contact.html 93-93-83](/assets/images/lighthouse/lighthouse-desktop-contact-mobile.jpg)

- Tested (for desktop) index.html, decent performance, accessibility and best practices. Some minor errors that are noted above in the "Troubles" section of this readme.
![Lighthouse score for index.html 93-85-75](/assets/images/lighthouse/lighthouse-desktop-index.png)

- Tested (for desktop) creative.html again decent performance, great accessibility and decent best practices - this performance was expected to be lower as for the same reasons on the mobile test.
![Lighthouse score for creative.html 93-98-83](/assets/images/lighthouse/lighthouse-desktop-creative.jpg)

- Tested (for desktop) contact.html great performance and accessibility and decent best practices - happy with this page on desktop.
![Lighthouse score for contact.html 99-95-83](/assets/images/lighthouse/lighthouse-desktop-contact.jpg)

#### How the website was deployed

- Went to github repository for "Project 1"
- Settings tab
- Down to pages
- source - deploy from branch
- branch - main, /(root)
- deployed

Code written:

Some of the code written in this project is borrowed from a lesson via Code Institute - the git repository can be found here "https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4"
