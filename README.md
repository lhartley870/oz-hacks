# Oz Hacks
Oz Hacks is a site intended to provide practical and useful hacks for backpacking around Australia. The site is targeted at anyone of any age who is either planning to go backpacking or who is already backpacking in Australia. Oz Hacks will be useful for travellers as it provides top tips specifically for backpacking around Australia as opposed to anywhere else accompanied by applicable image, video and external link content.

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

I used [Balsamiq](https://www.balsamiq.com) to create Wireframe mockups for browser, tablet and mobile views which can be found here: 
* Home 
* Before You Go 
* When In Oz 
* Gallery
* Contact

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
------------ ---------
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
* **Navigation Bar**

    The website is set up to take the user through a logical journey of separated steps via the easy-to-use navigation bar which includes links to all the pages and is the same on each page. Running left to right, the navigation bar reflects the stages the user is likely to go through in terms of both the stages of their trip and their likely primary and secondary goals for visiting the website as mentioned above. This helps the user find what they are looking for quickly and intuitively and provides a logical flow to the whole site. Its appearance on each page prevents visitors having to use the 'back' button. 
    [Info about feeback of nav bar]
* **Logo**
    The rotating compass logo provides a point of interest when arriving at the home page and is a consistent feature across all the pages. The compass imagery is part of the travelling theme of the website designed to evoke excitement about an upcoming or existing backpacking experience. 

    The Oz Hacks logo is also a consistent feature across all pages and when clicked on takes the user back to the home page which is a predictable and standard website convention. 

* **Header and Footer**
    
    The header contains the navigation links and has a background image of Uluru which is one of the most recognisable Australian landmarks as part of the consistent Australian and travelling imagery across the site designed to provide a positive user reaction for the target audience. 

    The footer contains contrasting ocean imagery and links to external useful websites for flights, hostels, visas and tripadvisor for Australian backpackers for users that want to further plan their trip. The links have a relevant logo and state what the link is for to provide clarity. [info about feedback of links]

* **Central Welcome Message**

    The welcome box has a small image to the left in keeping with the backpacking theme and a larger text box to the right which contains a welcome message. The message appears in the box as though it is being typed with a signature of the site author at the end of the message. This animation draws attention to the welcome message which helps users feel a connection to the author and her experience and encourages the user to continue browsing the site.

    The image and text box structure is repeated througout the Before You Go and When In Oz hacks pages to create consistency and familiarity for the user.  

#### Before You Go and When in Oz Pages
* **Presentation of Hacks**

    Both of the hacks pages following the same layout for predictability across the site and follow the smaller image/video and larger text box structure of the Home Page. 

    Each hack has a corresponding text box and either a video or image next to it to help the user further understand the hack. The hacks are piled one on top of the other creating content hinting to keep the user scrolling down the page until all the hacks have been seen. Where applicable the text for the hacks has external links where the user can find out further information relating to the hack to provide added value to the user. 

* **Animation**

    When these two pages are loaded, the boxes running either side of the centre of the screen come in from the right and left and appear to race each other until they meet in the centre. This animation feature is designed to provide a point of interest when these two pages are first opened and represents the text for the hack and the corresponding video/image coming together to inform the user. 

#### Gallery Page

* **Arrangement of Photos**

    The Gallery page provides an overlapping/stacked photo structure as you go down the page to create the idea of a scrapbook of travelling photos. As with the hacks, the stacking down the page creates content hinting encouraging the user to scroll to the bottom of the page. 

    When hovered over on a desktop, the relevant photo appears to come to the top of the pile for full viewing.
    
    Each photo has a caption stating the place name and the photos are grouped depending on the area of Australia to help the user quickly scroll to the area that they are interested in knowing more about. 
    
#### Contact Page

* **Structure**

    The Contact page has a similar structure to the Home Page to bring everything full circle and complete the user's journey through the site. 

* **Content**

    The page contains a form that visitors to the site can use if they have any queries or comments for the site author. The user is asked to provide their full name and email address and there is a button at the bottom of the form to submit it. 

* **Feedback**

    [Include details of form feedback using methods other than colour]
    
    
      On a tablet or mobile, the photos appear one at a time with horizontal scrolling to better suit the device type. 

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








The site also has separate pages for hacks applicable before a user travels to Australia and hacks 

