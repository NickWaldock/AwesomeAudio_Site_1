# Welcome to the Awesome Audio Website
![Am I Responsive](/assets/images/README%20Images/am-i-responsive.png)

[View the site here](https://nickwaldock.github.io/AwesomeAudio_Site_1/)
<br />
<br />

# Table of Contents
1. [Introduction](#introduction)
2. [Overview & Aims](#overview--aims)
3. [User Experience](#user-experience-ux)
4. [Main Features](#main-features)
5. [Technologies](#technologies)
5. [Testing](#testing)
6. [Deployment](#deployment)
7. [References & Acknowledgements](#references--acknowledgements)
<br />
<br />

# Introduction

Awesome Audio is fictional music recording studio inspired from the dreams of a musician with a love for high quality and vintage audio recording alongside the inspirational tranquility that only the countryside can bring. Awesome Audio offers all this for an audio recording session free from the distractions of busy city music scenes.

Thank you for taking the time to browse this site which represents my first forray into the world of coding! 
<br />
<br />

# Overview & Aims

As a high-end audio recording studio, Awesome Audio offers musicians a range of recording techniques blending the convenience of digital recording with the often sought-out warmth of vintage analogue equipment. Musicians and artists today are often caught between the decision of cost and convenience vs quality when it comes to producing a record. City studios are often expensive, small, and usually specialise in a certain recording genre. While this can be useful for smaller projects, for larger projects it can be more cost and creatively effective to retreat to a countryside studio where artists can explore multiaple recording approaches free from the distractions of the fast-paced city recording dynamic.


The Awesome Audio site aims to: 

1. Establish Awesome Audio as a credible audio recording studio
2. To deliver a feel for the brand as one of sohphistication, tranquility, assurance, and style.
3. Provide an easy-to-navigate web space with ease for users to make enquiries
4. Clearly demonstrate all the initially important information a propsetive client would be insterested in and looking for when researching a recording studio, including visual gallery, recent client list, equipment lists, location, and contact details;
5. To be of responsive design and able to work on all device screen sizes
<br />
<br />

# User Experience (UX)
## User Stories

As a first time visitor, I want to:

- Easily navigate around the site and find all the relevant information to discover if I am interested in bringing my project there.
- Easily find key information such as location, equipment lists, and pictures of the recording spaces.
- Be able to find the companies relevant social media pages

As a returning visitor, I want to:
- Easily be able to send a message to the company and have confidence of receiving a reply
- Read information about the companies recent client lists to see the calibur of artists that are recording there.

As a frequent visitor, I want to: 
- Be able to navigate to the map easily to find the exact location and plan logistics through google maps.
- Be able to see the terms and conditions of booking with the company including cancellation procedure, deposits, and completion of work conditions
<br />
<br />

# Main Features

## Inspiration for Design
Design ideas were inspired from a number of audio recording websites, see [references](references.md). Key design ideas and important information to include was inspired by and used with permission from my good friends at [Masterlink Productions](https://www.masterlinkproductions.co.uk). Particularly the, about section, equipment list, gallery images, and terms and conditions.

Note: As with the rest of the site, the 'Artists' are fictional.
<br />
<br />

## Logo and Typography
The Awesome audio logo was created in [Canva](https://www.canva.com/) and uses a soft orange template image with a slightly off-white background. The font Forum makes up the main title and Monserrat for the tag line. These themes are expanded throughout the site for consistency with sans-serif as a back up font. 

Forum has an antique and classic feel reflecting the companies love for high-end vintage equipment and Montserrat to reflect simpliciity, style, and order.
<br />
<br />

## Colors and Imagery
Black solid parallel lines are used as a design feature to seperate seections and provide definition to images, this is to demonstrate stability to the design. Corners were softened to reflect the more tranquil nature of the brand. As the brand is a fictious one, images used were either from royalty-free stock images sites or from the [Masterlink Productions](www.masterlinkproductions.co.uk).

A full reference list for images and content can be found [here](/references.md)
<br />
<br />

## Wireframes

[PDF Wireframe Designs](/assets/images/README%20Images/site-wireframe.pdf =width="200" height="400")

Initial wireframe designs for the project were constructed after audio recording studio website research and marked up by hand.
In most cases, wireframe design was adhered to, but in some cases the design was altered in the process of coding. An example of this is this [equipment section](/assets/images/README%20Images/equipment-wireframe.png width="200" height="400"), where the layout was unfeasable to display all of the relevant information in an effective and pleasing way.
<br />
<br />

## Features
- The Awesome Audio website is built with responsive design and is effective for viewports >450vw
<br />
- Interactive elements:
  - An always visible navigation bar with in-page links and cross-site links that indicates which main page you are currently viewing.
  - Navagation text hides below 900vw and can be revealed when clicking the top left logo icon, this is to tidy up the design on smaller screens.
  - About Us information cards with internal links to relevant information
  - Gallery with organised images
  - Other interactive elements such as: jump to top button, footer with social links, and a submittable contact page with confirmation and thank you message.
  <br />
  <br />

# Technologies
Languages used in this site are HTML 5 and CSS3
Additional technologies include: 
- Google fonts
  - to import the Forum and Montserrat fonts into the style.css file
- Font Awesome
  - for icons used for buttons and social links
- [Canva](https://www.canva.com/en_gb/)
  - for graphic design of logo
- [EZ Gif](https://ezgif.com/) 
   -for image file-type modification to webp
- [TinyPNG](https://tinypng.com/) 
   - for image compression
- Chrome DevTools
   - For debugging and testing responsiveness during development
- GitHub
  - Site repository
- Gitpod
  - Online IDE for all coding work and site file management, terminal was used to add, commit, and push to Github
  <br />
  <br />

# Validation

## Bugs, Troubleshooting & Design Changes

Some of the design of the site doesn't fully reflect the initial wireframe designs. As this is my first attempt at creating my own site there were a number of moments of redesign during deployment due to my fledgling understanding of good design aethestics. 

The following are the main changes in design
### 1. The 'About Us' section 

<br />

![](/assets/images/README%20Images/about-us-wireframe.png =width="200" height="400")

<br />

The original wireframe had this section arranged in 6 seperate elements with headings in-between and links indented with the text. This proved to be difficult to effectively achieve in development and led me to learning about Grid and Flex notebly from this [Kevil Powell video](https://www.youtube.com/watch?v=sKFW3wek21Q) where Kevin arranges his information in the form of 'cards'. I opted to adapt my design to this for ease of styling and eventual responsiveness.

<br />

![](/assets/images/README%20Images/about-us-site.png =width="200" height="400")

<br />

### 2. The 'Equipment' Section

<br />

![](/assets/images/README%20Images/equipment-wireframe.png width="200" height="400")![](/assets/images/README%20Images/equipment-phone-wireframe.png =width="200" height="400")

<br />

In this original design I envisaged text information and links all within an relating image. This again became difficult due to the qualtity of content information I was aiming to convey. The design quickly became unfeasable, and in a desire to simplify the design and layout I once again turned to grid and flex to facilitate this. 

<br />

![](/assets/images/README%20Images/equipment-phone-site.png =width="200" height="400")
<br />

### 3. The 'Recent Artists' Section

<br />

<img src="/assets/images/README%20Images/artists-phone-wireframe.png" width="25%">

<br />

On reflection of the original wireframe this design unlikely to be effective. The design is quite different to the full-width design and could make the aesthetic incongruent between devices. Again, grid was instead used to re-arrange the images and text in a single column for smaller screens.

<br />

<img src="./assets/images/README%20Images/artists-phone-site.png" width="25%">

<br />
<br />

## Testing

The site's code has been tested on W3C html validator and W3C CSS validator
The site was mainly tested during development on Google Chrome utilising the browser's built-in DevTools, and has also been tested on Safari and Firefox browsers with coresponding use of developer tools.
<br />
<br />

## Bugs

When testing the site on Firefox and Safari two main issues were discovered:
1. Links were changing color to render as 'visited' including the footer social icon links. This was solved through direct element targeting and the use of the "!Important" value. 
2. The 'About Us' section images would not maintain their 1/1 aspect ratio. This was solved with an extra line of directly targeted code in the CSS stylesheet.


## Validation

HTML and CSS validations have passed, with a single exception due to the design and functionality of the hamburger menu.
![](/assets/images/README%20Images/validation-error.png =width="200" height="400")

 This same single error exists on each html page validation result due to this decision. This has been deliberately left in order to maintain functionality of the hamburger menu. I attempted to resolve this with experimenting with alternative arrangments of the elements but within at the start of my coding journey it seemed to me that if the error is resolved the menu fails to function as intended, and I was advised to keep it and discuss the reasons here. I had originally experimented with other menu designs including using the site logo to toggle and reveal a menu, however these designs didn't feel right. I then disocvered a blog with an elegant and simple menu for smaller screens. The final code used was quoted and adapted to fit with the site's generaly themes and styles. It is the only instance in the project where code was directly 'borrowed' and then adapted. It is this core code that causes the error due to the use of a 'nav' inside a 'label' in that particular context. The original code can be found [here](https://alvarotrigo.com/blog/hamburger-menu-css-responsive/).

 Future development could include searching for an alternative function as my knowledge improves, or a redesign of the menu althogether.

 Only a few other minor validation errors were found and subsequently fixed:
 1. Duplicate id tags
 2. Incorrect Aria labels
 3. Missing alt tags for images
 4. A missing space between two classes
 5. Contact form submit button format and use of 'a' elements and icon
 6. Internal nav bar links broken

-[HTML Validation Results index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnickwaldock.github.io%2FAwesomeAudio_Site_1%2Findex.html)

-[HTML Validation Results gallery.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnickwaldock.github.io%2FAwesomeAudio_Site_1%2Fgallery.html)

-[HTML Validation Results contact.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnickwaldock.github.io%2FAwesomeAudio_Site_1%2Fcontact.html)

-[HTML Validation Results terms.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnickwaldock.github.io%2FAwesomeAudio_Site_1%2Fterms.html)

-[HTML Validation Results thankyou.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnickwaldock.github.io%2FAwesomeAudio_Site_1%2Fthankyou.html)

-[CSS Validation Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fnickwaldock.github.io%2FAwesomeAudio_Site_1%2Fassets%2Fcss%2Fstyles.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

<br />



## Future Development

Future development of this site could include:
- Additional multi-media elements such as user controllable video and audio
- Chat Bot for messaging and sorting enquiries
- Live social media feeds
- File sharing for completed projects 
- A 'Services' section detail the specific services the company offers
- A blog
- Making the gallery more interactive, click to enlarge images with detailed captions
<br />
<br />

## Deployment

The live site can be accessed [here](https://nickwaldock.github.io/AwesomeAudio_Site_1/)
<br />

### GitHub
This project was deloyed to GitHub Pages with the following steps:
1. Log in to GitHub (create an account if necessary)
2. Locate the [GitHub Respository](https://github.com/NickWaldock/AwesomeAudio_Site_1)
3. On the repository page, find the 'Settings' icon anc click on it
4. In the Settings page, look for and click the 'Pages' menu item on the left hand side (under section titled 'Code and automation', you may need to scroll down slightly)
5. In the 'Pages' page, under 'Source', select 'Branch:main', then '/root' and click save
6. After a few minutes, the site will be published
<br />

### Forking
The fork this repository proceed with the following steps:
1. Log it to GitHub (create an account if necessary)
2. Locate the [GitHub Respository](https://github.com/NickWaldock/AwesomeAudio_Site_1)
3. On the repository page, find the 'Fork' menu in the top right, click on the small down arrow
4. Select '+ Create a new fork'
5. Remane repository as required
6. Click 'Create Fork'
7. You now have your forked version of this repository
<br />

### Cloning
To clone thei repository procees with the following steps:
1. Log in to GitHub (create an account if necessary)
2. Locate the [GitHub Respository](https://github.com/NickWaldock/AwesomeAudio_Site_1)
3. On the repository page, find and click on the 'Code' menu in the mid-top right of the page
4. Choose to either download or open in GitHub Desktop,
  -or;
    5. Choose the HTTPS option and copy the URL to your clipboard
    6. - To clone the repository using HTTPS, under "HTTPS", copy the url
       - To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click SSH, then copy the url
       - To clone a repository using GitHub CLI, click GitHub CLI, then copy url
    7. Open Terminal and change the current directory to where you want the cloned directory
    8. Type git clone, and paste the url, press Enter to create your local clone
<br />
<br />

## References & Acknowledgements
<br />

### References

The full list of references can be found [here](references.md)
<br />

### Acknowledgements

My thanks go to Chris Quinn, my mentor at Code Institute for his expert guidance, advice, support, and knowledge. The tutors at Code Institute who have assisted me in many troubleshooting and debugging steps, and my partner Kendal for supporting me with a steady stream of tea during my long hours staring at the screen! And finally to you, for taking the time to check out this project. Thank you.

