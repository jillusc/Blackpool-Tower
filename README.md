# The Blackpool Tower

This website informs visitors about The Blackpool Tower, a famous landmark in a popular seaside town in northern England.
After an introductory text, it has facts pertaining to the history of the tower and its present day status, including a summary of the activities and events offered for tourists.
Users can watch a video of one of the tower's special features (the ballroom), see photos of the tower, view a map of the location and use a form to sign up for a newsletter.

The website can be viewed here [The Blackpool Tower](https://jillusc.github.io/Blackpool-Tower/index.html)

<img width="577" alt="main home page screenshot" src="https://github.com/jillusc/Blackpool-Tower/assets/139234433/e9b8676b-04bd-4dc6-a2de-2ee056976430">

## Features
Style
* the colour scheme employs colours taken from the hero image and represent the sun and sand in keeping with the theme of the seaside. The font colour is not a harsh black, but a dark brown which was taken from the metal structure of the tower itself
* the font is imported to the html from Google Fonts and is called Josefin Sans: it has soft, rounded shapes with angular elements which reflect both the fun nature of the attraction and its location, as well as the elegance of the 129-year-old tower
* in the hero image, the tower is positioned in the central area of the viewport for all devices, giving users a clear, direct association with the subject of the site; the overlaying text stands out and this section looks neat at 280px, 576px, 768px and 992px widths
* the sections have alternating background colours and small icons from Font Awesome to further highlight the start of new sections
* for consistency, the header and footer share the same style
* the favicon was created using Photoshop: it echoes the shape of the tower

Navigation
* the menu features a house symbol for the home (top of page) link instead of the word 'Home' so that it's easier for users to differentiate it from the main content of the text sections (Past and Present); and because there is just the one page
* for visual balance and space conservation, and because it is not a major part of the site, the sign-up section is also navigated via an icon: a simple envelope lets the users know at a glance that there is the option to interact 
* the sections have anchor links so that users can jump to each one for relevant content. In the menu, they are displayed left-to-right in order of appearance on the page for convention and ease-of-use
* the footer contains relevant social media icons which link directly to The Blackpool Tower's official pages, opening in new tabs
* all icons have aria-labels for good practice with regards to accessibility

Page Sections
* the first section is named simply The Blackpool Tower as it holds general, introductory information. It has an icon of a landmark next to it so remind the users of the subject and to keep consistent with the other sections. Some text is displayed in bold so that readers' attention is drawn to the fact that these are the names of the attractions and not just a description; there is a correct assumption that the terms can be copy/pasted into a search engine and relevant results found. This section features a video that the user can control; it communicates a real-world representation of the content so far very clearly; it also visually breaks up the page's chunks of text
* the second section, Past, has a summary of the tower's history using interesting facts spaced freely for ease of digestion by the reader; the icon is a timeline, chosen to reinforce the concept of the section's content
* the third section, Present, details what is happening currently at the tower; the icon is of people to suggest that the tower's status is that of providing entertainment and it is popular
* the fourth section is the gallery, showing a handful of images which, on larger screens, display in columns; the icon is a retro camera in keeping with the historical, fun aspect of the attraction and its location
* the fifth section contains the address of the tower and an embedded Google Map to give a visual clue; the section's title and icon are appropriate
* the final section is where users can submit their information to receive further information if desired; the form is short and non-intrusive - only basic information is requested - but users can communicate freely via the Message box. The form requires a name and a valid email address, and the button's colours change when clicked

## Features to implement
* a burger menu would be neater and expected by users of mobile phones
* a message to confirm form submission is preferable so that users don't question whether inputting their information has been successful
* improved responsiveness with regards to the header and hero image

## Testing
* full testing was not completed: it has been viewed and inspected using Chrome and functions well at the media queries' screen specifications
* using Lighthouse, the page's accessibility scored highly in the green zone
<img width="1073" alt="lighthouse ratings" src="https://github.com/jillusc/Blackpool-Tower/assets/139234433/487b9e4c-c122-454f-8555-40459e26e3b6">
* the site html and css were validated using W3C online tools

## Known Bugs
* the anchor links in the navigation menu jump to a point that is lower than what would be desirable: fixes that were attempted did not solve the problem
* the responsiveness is not smooth and needs improvement

## Deployment
The site is deployed to Github by the following process:
* click Settings
* select Pages in the pane on the left
* source is set to 'Deploy from a branch' and the main branch is selected with the folder set to / (root)
* click Save

## Credits
Code credits:
The site uses two instances of third party code, used as templates that were edited accordingly and to suit:
* for assistance with the gallery layout: https://www.w3schools.com/howto/howto_css_image_grid_responsive.asp
* for a simpler form layout: https://codepen.io/rstrahl/pen/rxmjgL

Photographic credits:
The images used in the site were found on free images websites as detailed below:
https://www.rawpixel.com/search/blackpool%20tower?page=1&sort=curated&topic_group=_topics    - (no name attributed)
https://pixabay.com/photos/blackpool-tower-england-7119769/    - leemurry01
https://unsplash.com/photos/XGlZj6AGBlg    - JonnyGios
https://unsplash.com/photos/JENweyUB1Ds    - Mark McNeill
https://cdn.blackpoolgrand.co.uk/app/uploads/2015/11/P1020466.jpg    - (no name attributed)
They were converted to .webp files using the online tool Convertio.

## Acknowledgements
Thanks to my mentor Rahul Lakhanpal for his feedback



