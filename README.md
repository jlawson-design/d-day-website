___

# The website is available at [this link](https://jlawson-design.github.io/d-day-website/)

__
# Table of Contents

- [The website is available at this link](#the-website-is-available-at-this-link)
- [Table of Contents](#table-of-contents)
- [Background](#background)
- [UX](#ux)
  - [User](#user)
  - [Design](#design)
  - [Structure](#structure)
- [Features](#features)
  - [Navigation Bar](#navigation-bar)
  - [Landing Content](#landing-content)
  - [Contact](#contact)
  - [Video Content](#video-content)
  - [Historical Imagery](#historical-imagery)
  - [Footer](#footer)
  - [Future Features](#future-features)
    - [Dynamic Scroll Bar](#dynamic-scroll-bar)
    - [Form Submit Page](#form-submit-page)
    - [Single Page](#single-page)
- [Testing](#testing)
  - [Process](#process)
- [Bug Fixing](#bug-fixing)
  - [Resolved](#resolved)
  - [Unresolved](#unresolved)
- [Resources](#resources)
  - [Image Content](#image-content)
  - [Education](#education)
  - [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)

___

# Background

D-Day is an informational/educational website intended to provide accurate historical information of the WW2 Allied amphibious landings known as Operation OVERLORD. The intention is to provide an impartial, elegant, and user friendly recounting of what occured on the beaches of Normandy in June of 1944.

Inspired by the first project idea from Code Institute's brief, D-Day focuses on providing a useful historical hub with usable evidence-based information. The content is strongly linked to existing literature, making it a one-stop-shop for information on this well-known historical event. This comes as we pass the 79th anniversary of the operation's commencement on June 6th 1944.

Like other historical websites such as [Britannica.com](https://www.britannica.com/event/Normandy-Invasion/D-Day-June-6-1944) or [History.com](https://www.history.com/topics/world-war-ii/d-day), this site provides a unique user experience, leveraging off the universal principles of design to give an accessible and aesthetically pleasing experience. The target audience for this website is anyone with a cursory knowledge of WW2 history who wishes to learn more. Academics and experts are also welcome, as this site boasts acknowledgements and references to some of the most famous pieces of secondary sources on the event in question.
___

# UX

## User

The user for this site is either someone who has an interest in the subject matter or someone with a deep knowledge of WW2 history. It is unlikely that the user will be some form of organisation and more likely to be an individual. This site caters to both experts and those more unfamiliar to the topic, delivering an accessible experience.

## Design
The design of the website should be elegant, minimalist, and ultimately **respectful** to the historical event. 
![Alt Text](/assets/img/readme-img/figma-wireframe.jpg)

- An initial design of the website was formed through the creation of a wireframe on [Figma](https://www.figma.com/). This wireframe guided design decisions and negated the temptation of scope creep.
- A minimalist design style was chosen for the website, evoking a sense of history, back when the majority of pictures taken lacked colour. However, the colour palette adheres to the design philosophy of providing a pleasing user experience, and colour is still used albeit sparingly.
- The colour palette consists of thematic colours such as 'Gunmetal', Battleship Gray' and 'Aquamarine'. [Colour Palette](https://coolors.co/ffffff-202a25-67dfba-848586-c1ae8c-857d66)
- Roboto was chosen as the site font. It's simplicity matches the minimalist style of the site and Roboto Slab is used for select headings as it matches well. 
![Alt Text](/assets/img/readme-img/colour-palette.png "Colour Palette")

## Structure
The home page consists of several articles on the historical event and imagery found online. The second page consists of secondary video sources describing the event through interviews and documentary footage.

___

# Features
UX attracts the user to the site, but features ensure they stay. The features are intended to compliment the site's overall aesthetic and solidify its purpose as a historical educator.

## Navigation Bar

The site features a navigation bar that responds to the user when each item is hovered over with the mouse. The responsive links change colour when the user hovers their mouse over them. 
![Alt Text](/assets/img/readme-img/nav-bar.jpg)

## Landing Content
The article on the homepage provides a well-researched introductory article, giving interesting facts about the event and referencing existing literature where necessary. 
The homepage features the headline article for the website, a comprehensive summary of the D-Day landings, drawing the user in through imagery and descriptive writing.
![Alt Text](/assets/img/readme-img/homepage.jpg)

## Contact

This section allows users to get in touch by entering their details through a form. The form asks for the user's name, email, and a brief descriptions about their enquiry. 
![Alt Text](/assets/img/readme-img/contact-section.jpg)

## Video Content
Reference to external video content is provided in the site. The content is intended to flesh out the details of the primary article and boost the user experience. An aspect ratio calculator [Omni Calculator](https://www.omnicalculator.com/other/16-9-aspect-ratio#:~:text=Check%20the%20width%20and%20height%20of%20your%20image.,16%2F9%2C%20aspect%20ratio%20of%20your%20image%20is%2016%3A9.) was used to calculate the relevant height to specific widths for the iframe videos. 
![Alt Text](/assets/img/readme-img/video-footage.jpg)

## Historical Imagery
Imagery from the historical date is used to immerse the user in the content on screen. 
![Alt Text](/assets/img/readme-img/site-imagery.jpg)

## Footer

The footer links to social media and content delivery websites for the page, specifically Instagram and Github and LinkedIn. The links within the footer move as the user hovers over it, providing a minimalist sense of dynamacism. 
![Alt Text](/assets/img/readme-img/footer.jpg)

## Future Features

There are a few features that were left on the cutting room floor that may be added in future versions.

### Dynamic Scroll Bar

The addition of a dynamic scroll bar to indicate the user's progression along the webpage was considered as a feature. However, as this required a Javascript solution, it was not included in the final build. 

### Form Submit Page

Currently the form links to the Code Institute submission page once submitted. Extra content could include a built-in submission page to keep the site consistent. 

### Single Page

Feedback was provided to convert the site into a one-page application. This feature would involve moving the video section below the feedback form. Time constraints meant that this could not be implemented.
___

# Testing

Different elements of the site were coloured throughout the process to discern where changes were being made. As the majority of the site has a white background this required constant testing processes. 

## Process

___

# Bug Fixing
The site text was tested using the [W3C Validator](https://validator.w3.org/nu/) which resulted in the identification of a few bugs shown in the following section. Below are the results of the successful tests:
![Alt Text](/assets/img/readme-img/index-W3C-validator.jpg)
![Alt Text](/assets/img/readme-img/video-W3C-validator.jpg)
Finally, the webpage CSS was tested using the Jigsaw validator. All errors found are noted in the following section:
![Alt Text](/assets/img/readme-img/style-jigsaw-validator.jpg)

## Resolved
- One bug that occured early on in the project creation was when the project would not update when run through "python3 -m http.server". As the source of this error could not be identified, the project was rebooted in a new Github repository. This is not the correct way to solve this error but provided new learnings to keep track of what is entered into the terminal. For example, accidentally terminating a running website with CTRL+Z instead of CTRL+C does not adequately shut down the project and requires additional commands to stop the code from running. 
- W3C Validator identified the second major error found in the <meta> element of index.html.
- A bug occured when creating movement when hovering over the social media links. The hover effect occured when the surrounding list item area was hovered over. This was fixed through adding an id "click-icon" to the icons and moving the css properties to that id.
- The frameborder attribute on the iframe element was obselete and removed through identification by W3C Validator. 

## Unresolved
- The logos in the footer of the page are slightly off-centre. This error could be remediated by editing the flexbox parameters in the stylesheet. 
- The size of the images for the media queries could use more work to ensure the imagery and video footage is shown to be the right size in all instances. 
___

# Resources
Below are a list of sources used in both the creation of the site content and learnings. 

## Image Content
- Imagery was taken from [Shutterstock.com](https://www.shutterstock.com/). This was to gather images of high-quality.
- The Favicon was created using the [Favicon.io Generator] (https://favicon.io/favicon-generator/)

## Education
- The Code Institute videos were constantly referred to in the creation of this project, specifically those focused on the Love Running template website.
- [W3Schools](https://www.w3schools.com/) was used for understanding and adding new styling content. 
- Creation of the website was assissted by [Easy Tutorials](https://www.youtube.com/watch?v=oYRda7UtuhA&list=PLjwm_8O3suyP5kGKmwS_DM0Hs1j7fshi5) on YouTube.

## Technologies Used
- Wireframes were created in [Figma](https://www.figma.com/).
- Code was written exclusively in HyperText Markup Language (HTML) and Cascading Style Sheets (CSS).
- To fix errors and troubleshoot, [Stack Overflow](https://stackoverflow.com/) was constantly referred to. 
- [Coolers.co](https://coolors.co/) was used to create the colour palette for the site. 
- CodeAnywhere was used as the recommended Integrated Development Environment (IDE).
- [Font Awesome](https://fontawesome.com/) provided clipart imagery for social media links.
- [Google Fonts](https://fonts.google.com/) was imported in the style sheet to use the selected font types. 
___

# Acknowledgements

I would like to thank the Code Institute team and the Slack community. I would also like to extend my thanks to my mentor, Okwudiri Okoro, for his impartial perspective and guidance on the project. A special thank you to Bethany and Alan for granting me an extention due to illness.
