# The Blackpool Tower

This website informs visitors about The Blackpool Tower, a famous landmark in a popular seaside town in northern England.
After an introductory text, it presents facts pertaining to the history of the tower and its present day status, including a summary of the activities and events offered for tourists.
Users can also watch a video of one of the tower's special features (the ballroom), see photos of the tower, view a map of the location and use a form to sign up for a newsletter.

<img src="assets/images/README images/main home page screenshot.png">

The website can be viewed here: [The Blackpool Tower](https://jillusc.github.io/Blackpool-Tower/index.html)


## Features

Style

* the colour scheme employs colours taken from the hero image and represent the sun and sand in keeping with the theme of the seaside. The font colour is not a harsh black, but a dark brown which was taken from the metal structure of the tower itself
* the font is imported to the html from Google Fonts and is called Josefin Sans: it has soft, rounded shapes with angular elements which reflect both the fun nature of the attraction and its location, as well as the elegance of the 129-year-old tower
* in the hero image, the tower is positioned in the horizontally-central area of the viewport on all devices, giving users a clear, direct association with the subject of the site; the overlaying text stands out thanks to a semi-transparent background box and contrasting bright coloured font
* the sections have alternating background colours and small icons from Font Awesome to further highlight the start of a new section:
<img src="assets/images/README images/headings and icons.png">
* for consistency, the header and footer share the same style:
<img src="assets/images/README images/header footer.png">

* the favicon was created using Photoshop: it echoes the shape of the tower: <img src="assets/images/README images/blackpool-tower-favicon.png">


Navigation

<img src="assets/images/README images/navigation screenshot.png">

* the menu features a house symbol for the home (top of page) link instead of the word 'Home' so that it's easier for users to differentiate it from the main content of the text sections (Past and Present); and because there is just the one page
* for visual balance and space conservation, and because it is not a major part of the site, the sign-up section is also navigated via an icon: a simple envelope lets the users know at a glance that there is the option to interact
* the sections have anchor links so that users can jump to each one for relevant content. In the menu, they are displayed left-to-right in order of appearance on the page for convention and ease-of-use
* the footer contains relevant social media icons which link directly to The Blackpool Tower's official pages, opening in new tabs
* all images have alt attributes and all icons have aria-labels for good practice with regards to accessibility

Page Sections

  1.   
<img src="assets/images/README images/1 section.png">


The first section of the page is named simply The Blackpool Tower as it holds general, introductory information. It has an icon of a landmark next to it so remind the users of the subject and to keep consistent with the other sections. Some text is displayed in bold so that readers' attention is drawn to the fact that these are the names of the attractions and not just a description; there is a correct assumption that the terms can be copy/pasted into a search engine and relevant results found. This section features a video that the user can control; it communicates a real-world representation of the content so far very clearly; it also visually breaks up the page's chunks of text.
<BR><BR>

  2.
<img src="assets/images/README images/2 section.png">

The second section, Past, has a summary of the tower's history using interesting facts spaced freely for ease of digestion by the reader; the icon is a timeline, chosen to reinforce the concept of the section's content.
<BR><BR>


  3.
<img src="assets/images/README images/3 section.png">

The third section, Present, details what is happening currently at the tower; the icon is of people to suggest that the tower's status is that of providing entertainment and it is popular.
<BR><BR>


  4.
<img src="assets/images/README images/4 section.png">

The fourth section is the gallery, showing a group of images which, on larger screens, display in columns via the use of Flexbox; the icon is a retro camera in keeping with the historical, fun aspect of the attraction and its location.
<BR><BR>

  5.
<img src="assets/images/README images/5 section.png">

The fifth section contains the address of the tower and an embedded Google Map to give a visual clue; the section's title and icon are appropriate.
<BR><BR>

  6.
<img src="assets/images/README images/6 section.png">

The final section is where users can submit their information to receive further information if desired; the form is short and non-intrusive - only basic information is requested - but users can communicate freely via the Message box. The form requires a name and a valid email address, and the button's colours change when clicked.

## Features to implement

* a burger menu would be nice and possibly expected by users of mobile phones
* a message to confirm form submission would be helpful for the user so that there is no question of whether inputing their information has been successful

## Testing

The page was inspected using Chrome's devtools and viewed in Chrome, Firefox, Edge, Safari and Samsung Internet browsers on an Apple and an Android mobile, on a tablet and a laptop. The anchor links, video playback, map link, form input and social media links all functioned successfully in every case.

<img src="assets/images/README images/video edge.png"><BR>
Playing the video in Edge on laptop<BR><BR>

<img src="assets/images/README images/map samsung.jpg"><BR>
Opening the map in Samsung Internet on mobile<BR><BR>

<img src="assets/images/README images/map in safari on iphone.jpeg" width="30%"><BR>
Opening the map in Safari on iphone<BR><BR>

<img src="assets/images/README images/form in safari on tablet.jpg" width="50%"><BR>
Testing the form functionality in Safari on tablet<BR><BR>


The site's html and css passed validation tests using W3C online tools:
<img src="assets/images/README images/html validated.png">
<img src="https://github.com/jillusc/Blackpool-Tower/assets/139234433/85a38c27-811a-4d63-916b-4276066ca8c7">

Using Lighthouse, the page's accessibility scored highly in the green zone:
<img src="https://github.com/jillusc/Blackpool-Tower/assets/139234433/487b9e4c-c122-454f-8555-40459e26e3b6">

There are no known bugs in existence.<BR>
A former issue was that in some devices the navigation menu was sitting very close to the bottom of the header, sometimes even outside of it, and this was rectified by removing/unspecifying a height property from the header; Flexbox was also simplified in the header element.


## Deployment

The site is deployed to Github by the following process:

* click Settings
* select Pages in the pane on the left
* source is set to 'Deploy from a branch' and the main branch is selected with the folder set to / (root)
* click Save

The website can be viewed here: [The Blackpool Tower](https://jillusc.github.io/Blackpool-Tower/index.html)

## Credits

Content:
The site uses two instances of third party code, used as templates that were edited accordingly and to suit:

* for assistance with the gallery layout: <https://www.w3schools.com/howto/howto_css_image_grid_responsive.asp>
* for a simpler form layout: <https://codepen.io/rstrahl/pen/rxmjgL>

Media:
The images used in the site were found on free images websites as detailed below:

* <https://www.rawpixel.com/search/blackpool%20tower?page=1&sort=curated&topic_group=_topics>    - (no name attributed)
* <https://pixabay.com/photos/blackpool-tower-england-7119769/>    - leemurry01
* <https://unsplash.com/photos/JENweyUB1Ds>    - Mark mc neill
* <https://unsplash.com/photos/2KdFSNBhcIQ>    - Mark mc neill
* <https://unsplash.com/photos/XGlZj6AGBlg>    - JonnyGios
* <https://unsplash.com/photos/cvBSUS4PfTo>    - Francis Heathcote
* <https://pixabay.com/de/photos/blackpool-turm-strand-england-4021722/>    - SnapHappyUK
* <https://unsplash.com/photos/Ax_paLwzGYs>    - Mark mc neill


They were converted to .webp files using the online tool Convertio.

## Acknowledgements

Thanks to Rahul Lakhanpal for his feedback.
