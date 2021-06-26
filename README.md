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

I used [Balsamiq](https://www.balsamiq.com) to create Wireframe mockups for desktop, tablet and mobile devices which can be found here: 
* [Home Page](/readme-documents/wireframes/home-page-wireframes.png) 
* [Before You Go](/readme-documents/wireframes/before-you-go-wireframes.png) 
* [When In Oz](/readme-documents/wireframes/when-in-oz-wireframes.png) 
* [Gallery](/readme-documents/wireframes/gallery-page-wireframes.png) 
* [Contact](/readme-documents/wireframes/contact-page-wireframes.png) 

The Wireframes were a useful aid prior to starting to build the site but the design did evolve in the following respects and for the following reasons:

### Header and Footer
* Having photos in the header and footer did not look good once built and so the header and footer were given coloured backgrounds instead. 
* Having the three elements of the header (compass logo, Oz Hacks logo and navigation bar) built as three separate bordered boxes looked old fashioned and so the borders were removed to give one borderless block header.
* Having gaps between the header and footer and the right and left edges of the page looked odd and was replaced with a header and footer that took up 100% of the width of the page.
* The labels in the footer that went with the icon links to external websites were removed to give a less cluttered appearance. The icons themselves indicate what the links are for and are referenced on the Before You Go and When in Oz pages in more detail in any case. 
* On tablet devices, the page navigation links were initially going to move underneath the header but there was enough room for the links to appear horizontally in the header whilst still being readable so they were moved within the header for a neater appearance.  
* Initially a hamburger menu was going to be used for page navigation on mobile devices but without the use of JavaScript this was very complex, caused issues with accessibility and ultimately was not required as the mobile view still looked good by stacking the navigation links on top of each other. 

### Photo and Text Box Theme
* The Wireframes were based on there being a theme throughout the site of having a text box adjoined to a smaller video or image. With the Home Page and Contact page this would have looked too cluttered against a background hero image. The theme was therefore abandoned for the Home and Contact pages and was adapted for the Before You Go and When in Oz pages on larger screens by having a large text box stacked on top of a smaller video/image box for screens 1024px - 1439px wide and by having adjacent equally sized text boxes and video/image boxes for screens 1440px+ wide.
  
### Animation for Hacks Pages
* The intial animation idea for the Before You Go and When in Oz pages on larger screens was to have all the boxes on the left move from the left edge of the page to the centre and to have all the boxes on the right move from the right edge of the page to the centre, meeting in the middle. CSS grid was used for the layout of the hacks pages as it was an efficient way of re-arranging the hacks pages for different screen sizes. As the animation options for CSS grid are limited, the initial animation idea was swapped for a grid animation where the row gaps between each hack and media pairing open up and the column gap between the hacks and their corresponding media closes to bring the hack text and accompanying media together.

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

I selected Fontdiner Swanky as the font for the OzHacks logo and headings throughout the site as it has a fun and energetic feel appropriate for the subject matter of the site. Google Fonts suggested the Roboto font as a popular pairing with Fontdiner Swanky. The combination is complimentary with Roboto being a clear and easily readable font for use throughout the majority of the website. 

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

As one of the main colours associated with Australia is the rusty red colour of the outback and Uluru as an iconic Australian landmark, I used [Eye Dropper](https://eyedropper.org/) on a photo of Uluru to obtain the Firebrick colour hex code. I then used [ColorSpace](https://mycolor.space/?hex=%23AC2C00&sub=1) to generate a colour palette using Firebrick as the base colour. The Dark Salmon, Tan and Sky Blue colours were then generated, along with Firebrick, as the 'Pin Palette'. I chose this palette as I felt it was reflective of the colours of Australia and gave a nice look. The Dark Salmon with the Firebrick created a sunset type aesthetic whilst the Tan and Sky Blue gave a seaside/beach type aesthetic. The Sea Shell colour was taken from the 'Natural Palette' which also included the Tan and Firebrick colours. 

When I selected the image for the compass animation I again used [Eye Dropper](https://eyedropper.org/) on the navy colour appearing in the compass image to obtain the Midnight Blue hex code. I felt that out of the existing colours only Firebrick was dark enough to be used as the main text colour throughout the site against the Sea Shell background but I found it more visually appealing to use Midnight Blue as the predominant text colour with Firebrick being used more sparingly as more of a feature colour. Using Midnight Blue as the main text colour also provided a colour link back to the compass image which appears in the header on every page.

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

    The website page links appear in the cream Sea Shell colour initially and once visited turn to the dark Midnight Blue colour. This helps the user keep track of which pages on the site they have visited and gives an attractive appearance as when the pages are visited the Midnight Blue colour matches up with the Oz Hacks logo and compass in the header giving a sense of completeness. This encourages the user to keep going along the navigation bar visiting all the pages until they have all turned Midnight Blue. The contrast between the lightness of the Sea Shell colour and the darkness of the Midnight Blue also means that it is easy for users with Monochromacy/Achromatopsia colour blindness to see which pages they have visited. 

    A Firebrick coloured line remains under the relevant page name when the user is on that page, so that the user can tell at a glance where they are on the website. A Sea Shell coloured line appears under the relevant page name when the user hovers over it, highlighting an action the user can take to get to the other pages.

* **Logo**

    The rotating compass logo provides a point of interest when arriving at the Home page and is a consistent feature in the 'sticky header' across all the pages. The compass imagery is part of the travelling theme of the website designed to evoke excitement about an upcoming or existing backpacking experience. The rotation animation adds to the interest but is slow enough to not be distracting. 

    The Oz Hacks logo is also a consistent feature across all pages and when clicked on takes the user back to the Home page which is a predictable and standard website convention. 

* **Footer**

    The footer contains links to external useful websites for flights, hostels, visas and tripadvisor for users that want to further plan their trip. The links have a relevant logo to highlight what the link is for. As with the page navigation links in the header, the icons initially appear in the Sea Shell colour, turning Midnight Blue once visited with a Sea Shell underline when the icons are hovered over. This gives the user a sense of predictable interaction. 

#### Before You Go and When in Oz Pages

These pages represent the main goals of the user in finding out hacks both before the user goes to Australia and when they are there to make their backpacking experience as successful as it can be. 

* **Presentation of Hacks**

    Both of the hacks pages follow the same layout for predictability and familiarity purposes.  

    Each hack has a text box which provides information on the hack and an accompanying related video or image. The photos are designed to provide inspiring relevant imagery and the videos enhance the hacks by providing further/more detailed information beyond the text to help the user achieve their goal of successfully backpacking Australia. On smaller screens each hack text box is stacked on top of its accompanying image/video going down the page. On larger screens, each hack text box is adjacent to its accompanying media with the text box and media switching sides as you go down the screen. Both of these structures create content hinting to keep the user scrolling down the page until all the hacks have been seen. 
    
* **External Links**

    Where applicable the text for the hacks has external links where the user can find out further information relating to the hack to provide added value to the user. These links appear in the Sky Blue colour to differentiate them from the rest of the text and once clicked on turn Midnight Blue in line with the rest of the hack text. This behaviour mirrors that the user will have experienced with the header and footer links for consistency. Again, as with the header and footer, the links have a lighter Sky Blue underline when hovered over to indicate to the user that there is an action for them to take. To ensure that the user can still easily find any links they have already visited but want to re-visit, the links are also in a larger font size. 

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
    
    The Send button is large and clear at the bottom of the form and has a Sea Shell coloured shadow when hovered over (or tapped on touch screens). 

#### Responsive Design

    The website needs to be equally visually appealing across desktop, tablet and mobile given that backpackers may be using this site at home on a desktop before travelling but may be reliant on a tablet or mobile whilst backpacking. 

    The header is adapted for tablet across all pages by moving the navigation links underneath the header and for mobile by using a hamburger icon for the navigation links and making the Uluru image the background to the Oz Hacks logo. 

    For the Gallery page the overlapping photos appearing on a dektop are changed to a single photo with horizontal scrolling for tablet and mobile. 

### Further Feature Ideas
[                     ]
    
## Technologies Used
* HTML5 programming language for the structure and content of the website.
* CSS3 for styling the look of the website. 
* Font Awesome 
* GIT
* GitHub
* Gitpod
* Google Fonts

## Testing

## Deployment

## Credits 