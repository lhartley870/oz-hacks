# Oz Hacks
Oz Hacks is a site intended to provide practical and useful hacks for backpacking around Australia. The site is targeted at anyone of any age who is either planning to go backpacking or who is already backpacking in Australia. Oz Hacks will be useful for travellers as it provides top tips specifically for backpacking around Australia as opposed to anywhere else accompanied by applicable image, video and external link content.

The live project can be viewed [here](https://lhartley870.github.io/oz-hacks/index.html). 

![Responsive view of live website Home page](/readme-documents/screenshots/home-page-screenshots.png)

## UX (User Experience) 
### Users
Users of this website are typically going to be people who are searching for:
1. Useful travel hacks prior to flying to Australia; and/or 
2. Useful travel hacks when already backpacking around Australia; and/or
3. Potentially, inspiration for good places to visit in Australia as a secondary reason for visiting the site following on from the primary reason at 1 and/or 2.

### User Stories
* As a first time user of the site, I want to see what the site is all about and the experience of the author so that I can decide whether it is worth exploring the site further.
* As a first time user of the site, I want to be able to easily navigate the site so that I can find exactly what I want quickly. 
* As a first time user of the site planning to backpack around Australia, I want to be able to find travel hacks that are applicable before I fly so that I can best plan my trip. 
* As a first time user of the site already backpacking in Australia, I want to be able to find travel hacks that are applicable to me now so that I can improve my current backpacking experience. 
* As a returning user to the site having found the hacks useful, I want some inspiration for places to visit to inform my upcoming trip. 
* As a returning user to the site having found the hacks useful, I want to contact the site author for advice on a specific issue to assist me ahead of my trip. 
* As a returning user to the site having found the hacks useful, I want to explore some of the hacks further to help me plan my trip more fully. 
* As a returning user to the site having found the hacks useful, I want some useful links to book my flights and organise my visa. 
* As a user of the site I want a comforting familiar layout as I explore the site with an attractive colour scheme and Australian imagery so that I can be inspired and excited about my upcoming/existing backpacking experience. 

## Wireframes

I used [Balsamiq](https://www.balsamiq.com) to create Wireframe mockups for laptop/large monitor, tablet and mobile devices which can be found here: 
* [Home Page](/readme-documents/wireframes/home-page-wireframes.png) 
* [Before You Go](/readme-documents/wireframes/before-you-go-wireframes.png) 
* [When In Oz](/readme-documents/wireframes/when-in-oz-wireframes.png) 
* [Gallery](/readme-documents/wireframes/gallery-page-wireframes.png) 
* [Contact](/readme-documents/wireframes/contact-page-wireframes.png) 

The Wireframes were a useful aid prior to starting to build the site but the design did evolve in the following respects and for the following reasons:

### Header and Footer
* Having photos in the header and footer did not look good once built and so the header and footer were given coloured backgrounds instead. 
* Having the three elements of the header (compass logo, Oz Hacks logo and navigation bar) built as three separate bordered boxes looked old fashioned and so the borders were removed to give one borderless block header.
* Having gaps between the header and footer on the right and left edges of the page looked odd and was replaced with a header and footer that took up 100% of the width of the page.
* The labels in the footer that went with the icon links to external websites were removed to give a less cluttered appearance. The icons themselves indicate what the links are for and are referenced on the Before You Go and When in Oz pages in more detail in any case. 
* On tablet devices, the page navigation links were initially going to move underneath the header but there was enough room for the links to appear horizontally in the header whilst still being readable so they were moved within the header for a neater appearance.  
* Initially a hamburger menu was going to be used for page navigation on mobile devices but without the use of JavaScript this was very complex, caused issues with accessibility and ultimately was not required as the mobile view still looked good by stacking the navigation links on top of each other. 

### Photo and Text Box Theme
* The Wireframes were based on there being a theme throughout the site of having a text box adjoined to a smaller video or image. With the Home Page and Contact page this would have looked too cluttered against a background hero image. The theme was therefore abandoned for the Home and Contact pages and was adapted for the Before You Go and When in Oz pages on larger screens by having a large text box stacked on top of a smaller video/image for screens 1024px - 1439px wide and by having adjacent equally sized text boxes and videos/images for screens 1440px+ wide.
  
### Animation for Hacks Pages
* The initial animation idea for the Before You Go and When in Oz pages on larger screens was to have all the text boxes and videos/images on the left move from the left edge of the page to the centre and to have all the text boxes and videos/images on the right move from the right edge of the page to the centre, meeting in the middle. CSS grid was used for the layout of the hacks pages as it was an efficient way of re-arranging the hacks pages for different screen sizes. As the animation options for CSS grid are limited, the initial animation idea was swapped for a grid animation where the row gaps between each hack and media pairing open up and the column gap between the hacks and their corresponding media closes to bring the hack text and accompanying media together.

## Design

### Page Designs

The pages are designed to flow as the user takes each step through the journey of the website. 

The Home Page has a large hero background image of a campervan synonymous with the user's backpacker journey and visit to the website starting. The cover text is in a box with rounded corners for larger screens and the box covers the whole background image for smaller screens and is partially transparent, revealing the hero image behind. This layout is repeated on the final Contact page with a sunset hero background image synonymous with the user's steps on the website coming to a close. The colour scheme for the cover text box is switched with the first page having a cream cover box and navy text and the Contact page flipping that to cream text and a navy cover box. The first and last pages having a matching layout brings the user full circle. 

The Before You Go and When in Oz pages have the same layout with the text boxes and photos/videos either being stacked on top of each other for smaller screens or being side by side for larger screens. The layout, whether on larger or smaller screens, creates a flow down the page encouraging the user to keep scrolling down to find out the next hack for backpacking Australia. On larger screens the hack text box and media appear on different sides of the screen as you scroll down creating a flow across as well as down the page. The hack text boxes and accompanying videos/images all have curved corners matching the cover text box on the Home and Contact pages.  

The Gallery page has a standalone structure with the photos appearing to be polaroids for smaller screens and having an overlapping structure on larger screens. The flow of the Gallery page does, however, link back to the Before You Go and When in Oz Pages with the first polaroid being on the left of the screen, the second being on the right etc and the overlapping structure on larger screens creating a familiar flow across as well as down the page. 

### Fonts

I used [Google Fonts](https://fonts.google.com/) for the website fonts. The selected fonts and their fallbacks, should they not import into the site correctly, are as follows:

Selected Font | Fallback Font
------------- | --------------
Fontdiner Swanky | Cursive
Roboto | Sans-Serif
Courier Prime | Monospace
Rock Salt | Cursive

I selected Fontdiner Swanky as the font for the Oz Hacks logo and headings throughout the site as it has a fun and energetic feel appropriate for the subject matter of the site. Google Fonts suggested the Roboto font as a popular pairing with Fontdiner Swanky. The combination is complimentary with Roboto being a clear and easily readable font for use throughout the majority of the website. 

Courier Prime was selected for the Home Page cover text as it has the appearance of text typed on a computer which is key to the typing animation that appears on the Home Page. 

Rock Salt was selected for use on the Gallery Page as it has a handwritten appearance and I wanted the captions to appear as though they had been handwritten underneath the photos as if someone had made a scrapbook of their backpacking travels.   

### Colours

The colour scheme used on the site is as follows: 

Colour Name | Hexadecimal Code
------------| ---------
Firebrick       | #ac2c00
Dark Salmon     | #dc9c85
Tan             | #d2b48c
Sky Blue        | #88aee1
Midnight Blue   | #025
Sea Shell       | #fff5ed
Teal            | #237b75

As one of the main colours associated with Australia is the rusty red colour of the outback and Uluru as an iconic Australian landmark, I used [Eye Dropper](https://eyedropper.org/) on a photo of Uluru to obtain the Firebrick colour hex code. I then used [ColorSpace](https://mycolor.space/?hex=%23AC2C00&sub=1) to generate a colour palette using Firebrick as the base colour. The Dark Salmon, Tan and Sky Blue colours were then generated, along with Firebrick, as the 'Pin Palette'. I chose this palette as I felt it was reflective of the colours of Australia and gave a nice look. The Dark Salmon with the Firebrick created a sunset type aesthetic whilst the Tan and Sky Blue gave a seaside/beach type aesthetic. The Sea Shell colour was taken from the 'Natural Palette' which also included the Tan and Firebrick colours. 

When I selected the image for the compass animation I again used [Eye Dropper](https://eyedropper.org/) on the navy colour appearing in the compass image to obtain the Midnight Blue hex code. I felt that out of the existing colours only Firebrick was dark enough to be used as the main text colour throughout the site against the Sea Shell background but I found it more visually appealing to use Midnight Blue as the predominant text colour with Firebrick being used more sparingly as more of a feature colour. Using Midnight Blue as the main text colour also provided a colour link back to the compass image which appears in the header on every page.

The Teal colour was generated by using ColorSpace to generate colour palettes using Midnight Blue as a base colour. The Small Switch Palette was generated which had a colour of #278f8c. Inputting this colour into the [WebAIM Link Contrast Checker](https://webaim.org/resources/linkcontrastchecker/?fcolor=0000FF&bcolor=FFFFFF) along with the background colour of Sea Shell and the body text colour of Midnight Blue and sliding the scale along until a pass was reached for all categories, gave the Teal colour to be used for links within the hack text. The Teal colour is in keeping with the seaside/beach aesthetic of the Tan and Sky Blue colours. 

I used the ColorSpace Gradient tool which can be found [here](https://mycolor.space/gradient?ori=to+right&hex=%23DC9C85&hex2=%23D2B48C&sub=1) to generate the gradient colour CSS code used for the header using a left to right gradient with a start colour of Dark Salmon and an end colour of Tan. 

I used [Color-Hex](https://www.color-hex.com/color/fff5ed) to convert the Sea Shell and Midnight Blue hex codes into rgb colour codes so that I could use rgba values for the partly transparent cover text boxes on the Home and Contact pages.  

I also used [Coblis](https://www.color-blindness.com/coblis-color-blindness-simulator/), a colour blindness simulator, to test my website colour palette early on to make sure that the choice of colours and contrasts would still be visually appealing to people with different types of colour blindness. The combination of orange/pink based colours and blue based colours means that the site offers an appealing colour experience for all types of colour blindness tested using the simulator:

1. Anomalous Trichromacy: 
    * Red-Weak/Protanomaly
    * Green-Weak/Deuteranomaly
    * Blue-Weak/Tritanomaly

2. Dichromatic:
   * Red-Blind/Protanopia
   * Green-Blind/Deuteranopia
   * Blue-Blind/Tritanopia

3. Monochromatic:
   * Monochromacy/Achromatopsia
   * Blue Cone Monochromacy

Even though no colours can be seen with Monochromacy/Achromatopsia except for black, white and grey, the site is still visually appealing through the use of contrast between darker and lighter colours including the partly transparent cover text boxes on the Home and Contact pages, the inset shadow effect on the hack text boxes, the shadow effect on the polaroid photos in the gallery and the shadow effect when hovering over gallery photos on larger screens. 

## Features
### Existing Features
#### Home Page

The Home page is designed to quickly give the user an idea of what the website is about, draw the user in and encourage them to continue exploring the rest of the site.

* **Central Welcome Message and Hero Image**

    The Home page has a camper van hero image which fills the whole page bar the header and footer to grab the user's attention. The welcome message appears as though it has just been typed with the signature of the site author at the end of the message being animated. This animation draws attention to the welcome message which helps users feel a connection to the author, provides reassurance that the author has first-hand experience to be able to provide useful hacks and encourages the user to continue browsing the site.

    The hero image and overlaying text box structure is repeated on the Contact page to create a sense of consistency and familiarity for the user. 

* **Navigation Bar**

    The website is set up to take the user through a logical journey of separated steps via the easy-to-use navigation bar which includes links to all the pages and is the same on each page. Running left to right, the navigation bar reflects the stages the user is likely to go through in terms of both the stages of their trip and their likely primary and secondary goals for visiting the website as mentioned above. This helps the user find what they are looking for quickly and intuitively and provides a logical flow to the whole site. Its appearance on each page as part of a 'fixed/sticky header', which remains visible at all times at the top of the screen when scrolling, prevents visitors having to use the 'back' button. 

    A Firebrick coloured line remains under the relevant page name when the user is on that page, so that the user can tell at a glance where they are on the website. A Sea Shell coloured line appears under the relevant page name when the user hovers over it with a mouse or focusses on it with a keyboard, highlighting an action the user can take to get to the other pages.

* **Logo**

    The rotating compass logo provides a point of interest when arriving at the Home page and is a consistent feature in the 'sticky header' across all the pages. The compass imagery is part of the travelling theme of the website designed to evoke excitement about an upcoming or existing backpacking experience. The rotation animation adds to the interest but is slow enough to not be distracting. 

    The Oz Hacks logo is also a consistent feature across all pages and when clicked on takes the user back to the Home page which is a predictable and standard website convention. 

* **Footer**

    The footer contains links to external useful websites for flights, hostels, visas and tripadvisor for users that want to further plan their trip. The links have a relevant logo to highlight what the link is for. As with the page navigation links in the header, a Sea Shell underline appears when the icons are hovered over or focussed on. This gives the user a sense of predictable interaction. 

#### Before You Go and When in Oz Pages

These pages represent the main goals of the user in finding out hacks both before the user goes to Australia and when they are there to make their backpacking experience as successful as it can be. 

* **Presentation of Hacks**

    Both of the hacks pages follow the same layout for predictability and familiarity purposes.  

    Each hack has a text box which provides information on the hack and an accompanying related video or image. The photos are designed to provide inspiring relevant imagery and the videos enhance the hacks by providing further/more detailed information beyond the text to help the user achieve their goal of successfully backpacking Australia. On smaller screens each hack text box is stacked on top of its accompanying image/video going down the page. On larger screens, each hack text box is adjacent to its accompanying media with the text box and media switching sides as you go down the screen. Both of these structures create content hinting to keep the user scrolling down the page until all the hacks have been seen. 
    
* **External Links**

    Where applicable the text for the hacks has external links where the user can find out further information relating to the hack to provide added value to the user. These links appear in the Teal colour which, as mentioned above, complies with the WebAIM Link Contrast Checker and is in keeping with the seaside aesthetic of the Tan and Sky Blue colours. Again, similarly to the header and footer, the links have a Teal underline when hovered over to indicate to the user that there is an action for them to take. To ensure that the user can easily find any links, they are also in a larger font size. 

* **Animation**

    When these two pages are loaded on larger screens, where the hack text box and accompanying video/image are adjacent to each other, there is an animation where a row gap opens up between each hack and media pairing and a column gap closes up between the hack text boxes and their accompanying media. This animation feature is designed to provide a point of interest when these two pages are visited and represents the text for the hack and the corresponding video/image coming together to inform the user. 

#### Gallery Page
    
With the main purpose of the site being to provide useful hacks for backpacking Australia, the Gallery serves a secondary useful function to users in providing inspiration for places to visit in Australia.

* **Arrangement of Photos**

    On smaller screens the Gallery page consists of images of Australia which appear to be polaroids. The polaroids are on opposite sides of the screen as you go down the page. On larger screens the Gallery page provides an overlapping/stacked structure of different sized photos as you go down the page. As with the hacks pages, the stacking down and across the page on all screen sizes creates content hinting encouraging the user to keep scrolling down.

    The structure of the Gallery on both smaller and larger screens is designed to create the idea of a scrapbook of travelling photos with handwritten captions underneath stating the locations of the photos. As with the typing effect of the welcome message on the Home page, this is designed to create a connection between the user and the author as though the user is looking through a friend's photo scrapbook. 

    The photos are grouped depending on the area of Australia to help the user quickly scroll to the area that they are interested in knowing more about. The areas are set out in a logical order of North, East, South and West connecting back to the compass logo in the header. 

*   **Hover Effect**

    On larger screens where the photos are stacked on top of each other, when hovered over (or tapped on touch screens), the relevant photo appears to come to the top of the pile for full viewing and has a shadow effect in the Dark Salmon colour to focus the user on that photo and its caption. 
    
#### Contact Page

This page brings the user's journey through the website to a close and gives the user the opportunity to ask for any advice/raise questions further to reviewing the information on the site. 

* **Structure**

    The Contact page has a similar structure to the Home page to bring everything full circle, offering familiarity at the beginning and end of the user's experience.  

* **Contact Form**

    The user is asked to provide their full name and email address and there is a box for them to type out what advice they need. 
    
    The user is also asked to confirm for how long they are planning to stay in Australia by choosing from a dropdown list and to select a radio button to confirm whether they are planning to work and travel or just travel in Australia. These are key questions that the user will need to consider as part of their trip and will aid the user by providing the author with the background information she will need to know in order to effectively respond to any advice requests without having to ask the user additional questions first. The dropdown list provides an extensive range of time periods that the user can easily and quickly select from and there are only three radio button options which again the user can complete quickly and easily without having to type anything out.  
    
    The Send button is large and clear at the bottom of the form and has a Dark Salmon coloured shadow when hovered over (or tapped on touch screens). 

### Further Feature Ideas
* Implement the necessary back-end functionality so that the Contact form information when submitted goes through to a designated email address. At present, the form is not functional for submission and the form element has the action attribute and method="POST" attribute removed to prevent an error message appearing if anyone tries to submit the contact form. 
* For smaller screens where the photo gallery appears as polaroids, have a photo carousel slider that enables one polaroid at a time to take up the main page section with the user being able to slide across to the next photo on touch screens. 
* Implement a hamburger menu for mobile devices if any additional pages are added to the site as the current site navigation in the header could become unmanageable. 
* Implement a solution that would allow only image stubs of the embedded YouTube videos to load when the page is loaded with the player only being loaded once the user clicks on the video to help minimise/remove the initial slight delay in the videos appearing on the Before You Go and When in Oz pages when those pages are loaded. 
* Add a dark mode for the site. 
    
## Technologies Used

### Languages 
* [HTML5](https://en.wikipedia.org/wiki/HTML5) programming language for the structure and content of the website.
* [CSS3](https://en.wikipedia.org/wiki/CSS) for styling the look of the website.

### Libraries, Resources and Programs
* [Git](https://git-scm.com/) was the version control system used via the Gitpod terminal to commit and push code to GitHub.
* [GitHub](https://github.com/) was the git repository hosting service used to store code pushed from Git and to deploy the website live on the internet.
* [Gitpod](https://www.gitpod.io/) was the online IDE (Integrated Development Environment)/editor used to create, modify and preview the project code. 
* [Google Fonts](https://fonts.google.com/) was used to import all of the fonts used on the website into the style.css file. 
* [Font Awesome](https://fontawesome.com/) was used to provide all the icons throughout the site.  
* [Balsamiq](https://www.balsamiq.com) was used to prepare all of the Wireframes for the site. 
* [Chrome DevTools](https://developer.chrome.com/docs/devtools/) was used to inspect the project code throughout creation of the site. 
* [ColorSpace](https://mycolor.space/) was used to generate the 'Pin Palette' and 'Natural Palette' colour schemes from which most of the colours for the website were taken. The Gradient tool was also used to generate the CSS code for the header gradient colour. 
* [Eye Dropper](https://eyedropper.org/) was used to find out the hex codes for the rust red colour in a photo of the Australian landmark Uluru and for the navy colour in the compass logo image. 
* [Color-Hex](https://www.color-hex.com/color/fff5ed) was used to convert the Sea Shell and Midnight Blue hex codes into rgb colour codes so that rgba values could be used for the partly transparent cover text boxes on the Home and Contact pages.  
* [Coblis](https://www.color-blindness.com/coblis-color-blindness-simulator/), a colour blindness simulator, was used to test the website colour palette to make sure that the choice of colours and contrasts would still be visually appealing to people with different types of colour blindness. 
* [Am I Responsive?](http://ami.responsivedesign.is/) was used to create the screenshot shown in this README.md file showing how the website looks on different device types. 
* [Unsplash](https://unsplash.com/), [Pexels](https://www.pexels.com/), [Pixabay](https://pixabay.com/) and [Rawpixel](https://www.rawpixel.com/?sort=shuffle&page=1&feed=creative-feed) provided free photos and images used throughout the site.
* [W3 Schools](https://www.w3schools.com/), [Stack Overflow](https://stackoverflow.com/) and [CSS-Tricks](https://css-tricks.com/) were used for general guidance and learning.  
* [YesViz](https://yesviz.com/viewport/) and [Screen Size Map](https://screensizemap.com/) were used for awareness of the viewport sizes of different device screens for responsive design purposes and [What is my Viewport](https://whatismyviewport.com/) was used to confirm the viewport screen sizes of my devices for testing the project. 
* [Can I Use?](https://caniuse.com/) was used for checking browser compatibility.
* [Compressor](https://compressor.io/) was used for compressing photos used on the site. 
* [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) was used to check the contrast of text colours against their background colours. 
* [The W3C Markup Validation Service](https://validator.w3.org/) and [The W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) were used for testing the html and css code for the site.
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) were used for preparing the README.md and TESTING.md files.

## Testing

Please see the separate [TESTING.md file](TESTING.md) for details of the project testing carried out. 

## Deployment

## Credits 

### Code

* The gradient background colour code for the header was generated by [ColorSpace](https://mycolor.space/gradient?ori=to+right&hex=%23DC9C85&hex2=%23D2B48C&sub=1) when inputting the Dark Salmon colour (#dc9c85) first and the Tan colour (#d2b48c) last.
* The code for the compass logo rotation animation was adapted from this [Flaviocopes](https://flaviocopes.com/rotate-image/) site. 
* The code for styling the navigation link for the page the user is on with a coloured underline was adapted from the Code Institute 'Love Running' project as well as the html for the footer external links.  
* The typing animation code for the Home page was adapted from this [CSS-Tricks post by Geoff Graham](https://css-tricks.com/snippets/css/typewriter-effect/). 
* The code to remove the black bars above and below the YouTube embedded videos by maintaining the aspect ration of the videos on the Before You Go and When in Oz pages was taken from [this Stack Overflow solution by Michael Coker](https://stackoverflow.com/questions/43954836/disabling-blackbars-on-youtube-embed-iframe). 
* Code to remove black edging on the embedded YouTube videos was adapted from the code suggested by Patrick Grey in [this GitHub post](https://github.com/twbs/bootstrap/issues/26284).
* The code to make the photos on the Before You Go and When in Oz pages fit within their grid areas was adapted from [this answer given by Michael Benjamin on Stack Overflow](https://stackoverflow.com/questions/46090760/controlling-the-size-of-an-image-within-a-css-grid-layout). 
* The polaroid effect for the gallery photos on smaller screens was adapated from [this Line25 tutorial](https://line25.com/tutorials/how-to-create-a-pure-css-polaroid-photo-gallery).

### Media

#### Ilustrations

With thanks, the [compass illustration](https://www.rawpixel.com/image/394679/free-illustration-vector-compass-map-compass-icon) appearing in the header on all of the website pages is from [Rawpixel](https://www.rawpixel.com/?sort=shuffle&page=1&feed=creative-feed) but no illustrator identity was provided.

#### Photos

With thanks, the photos appearing on the website were taken by the following photographers: 

* From [Unsplash](https://unsplash.com/):
    * Home page - hero [camper van photo](https://unsplash.com/photos/kSJTEv9w5l4) by Simon Rae
    * Before You Go page:
        * [Camper in a sleeping bag photo](https://unsplash.com/photos/S5WS8jNDSqA) by Emerson Ward
        * [Kindle photo](https://unsplash.com/photos/3gC4gBnD3Xs) by Perfecto Capucine
        * [Aeroplane window photo](https://unsplash.com/photos/p9vr45T2scg) by Blake Guidry
    * When in Oz page:
        * [Melbourne class tram photo](https://unsplash.com/photos/xM9KZlD7dro) by Daniel Pelaez Duque
    * Gallery page: 
        * [Uluru photo](https://unsplash.com/photos/IKlpLl7HVo0) by Jason H
        * [Crocodile photo](https://unsplash.com/photos/qdg2Hxyjz4M) by Simon Watkinson
        * [Sydney Opera House photo](https://unsplash.com/photos/r2L6vCKaVRk) by Srikant Sahoo
        * [Coastal Walk Sydney photo](https://unsplash.com/photos/-fCvu160WRs) by Laura Cros
        * [Blue Mountains photo](https://unsplash.com/photos/-8fBv_bR4pU) by Quentin Grignet
        * [Whitehaven Beach photo](https://unsplash.com/photos/AEGEMP8L9TE) by Calvin Shelwell
        * [Surfers Paradise photo](https://unsplash.com/photos/mKwBMtDSZes) by Caleb Russell
        * [Fraser Island shipwreck photo](https://unsplash.com/photos/7zMGEK4PAuw) by Andreas Dress
        * [Bathing Boxes photo](https://unsplash.com/photos/H54c-6zu_BU) by Kon Karampelas
        * [Hosier Lane photo](https://unsplash.com/photos/wolwSgRH3XI) by Linda Xu
        * [Seal photo](https://unsplash.com/photos/m1V93jKlElk) by Danny Lau
        * [Whale Shark photo](https://unsplash.com/photos/SiLz-4N33sk) by Jeremy Bishop
        * [Pink Lake photo](https://unsplash.com/photos/QXAQKirGGpw) by Jake Stone
        * [Pinnacles photo](https://unsplash.com/photos/gF0IZVVKrD0) by Tobias Keller
        * [Quokka photo](https://unsplash.com/photos/4cT6YwMkHyg) by Christine Mendoza
    * Contact page:
        * Hero [Surfers on Bondi Beach photo](https://unsplash.com/photos/pzM4E7OhWLk) by Alex King

* From [Pexels](https://www.pexels.com/):
    * When in Oz page:
        * [Hostel room photo](https://www.pexels.com/photo/woman-in-red-t-shirt-sitting-on-black-chair-5158980/) by Cottonbro

* From [Pixabay](https://pixabay.com/):
    * When in Oz page:
        * [Credit card photo](https://pixabay.com/photos/money-card-business-credit-card-256319/) by Michal Jarmoluk\
    * Gallery page:
        * [Twelve Apostles photo](https://pixabay.com/photos/twelve-apostles-australia-rocks-2372379/) (no author given just ID 12019/10259)

* The Gallery page photos of the Devils Marbles, Byron Bay Lighthouse, Umpherston Sinkhole and Perth Botanical Gardens were taken by the developer. 

#### Videos

All the embedded videos used on the website are from [YouTube](https://www.youtube.com/). The YouTuber content creators are as follows:

* Before You Go page:
    * [Osprey Fairview Women's Travel Pack video](https://www.youtube.com/watch?v=13mqns50ImE) by Enwild
    * [10 Minimalist Packing Tips video](https://www.youtube.com/watch?v=HhaJBpNr5zs) by Pack Hacker
    * [Working Holiday Visa video](https://www.youtube.com/watch?v=LE8xpSc-zeU) by Lauren Meisner
* When in Oz page:
    * [Top 10 Destinations in Australia for 2021 video](https://www.youtube.com/watch?v=Uu4z4t1CXUk) by MojoTravels
    * [Travelling Australia - How Much do you need to Budget? video](https://www.youtube.com/watch?v=I4D84vzvASo) by Stoked For Travel
    * [50+ Australian Slang Words You Need to Learn video](https://www.youtube.com/watch?v=Ei7230KxvCg) by Aussie English

### Content

* All content was written by the developer although the information for hack 5 (Key Travel Documents) on the Before You Go page was largely taken from the [Australian Government's visa page](https://immi.homeaffairs.gov.au/visas/getting-a-visa/visa-finder) which has a link in the footer, the information for hack 3 on the When in Oz page was largely taken from [Commonwealth Bank's website](https://www.commbank.com.au/moving-to-australia/banking.html) which is a link within that hack text and some of the public transport card information for hack 5 (City Transport) on the When in Oz page was taken from [this Rocky Travel blog](https://www.rockytravel.net/blog/australia-public-transport-cards-review/). 

### Acknowledgments

Many thanks to:
* My mentor, Gerard McBride, for his help and guidance.
* The Code Institute tutors for their support. 