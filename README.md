![The Artful Rachel Logo](documents/Logo.JPG)

The Artful Rachel website allows people to learn about the works of an artist named Rachel as well as view information about upcoming events and showings for the artist. The visitors of the website could quickly access social media links for the artist and request custom artwork.

The site can be accessed by this [link](https://rachelfromireland.github.io/the-artful-rachel/).

![Responsive Mockup Image](documents/Mockup.JPG)

# User Stories
### First Time Visitor Goals:
As a First Time Visitor, I want to understand the site’s main purpose at a glance, so I can learn more about the artist.
As a First Time Visitor, I want the site to be easy to read and intuitive to navigate to avoid leaving because it is frustrating and instead have a pleasant user experience.
As a First Time Visitor, I want to see examples of previous artwork, so I can gauge the quality for myself before considering ordering.

### Returning Visitor Goals:
As a Returning Visitor, I want to see an easy-to-read and complete form to purchase my own custom artwork.
As a Returning Visitor, I want to see information about artwork, so I can decide for myself which medium and surface I like best.
As a Returning Visitor, I want to find a way to get in contact with the organization, so that I can ask any questions I have via email without filling in the commission form.
As a Returning Visitor, I want to find links to the artist’s social media, so I can see even more up-to-date artwork.

### Frequent Visitor Goals:
As a Frequent User, I want to be able to see updated live events and an updated gallery page showing the artist cares about the website and keeping things up to date.

# Features

## Navbar

![Navbar Desktop](documents/NavBar.JPG)
- Positioned at the top of the page.
- Contains the name of the website on the left side.
- Contains navigation links on the right side:
  - Home: Leads to the home page.  Users can learn about the Artful Rachel, including live event info.
  - Art: Leads to the art gallery page where users can see completed works by the artist.
  - Commissions: Leads to the commission form page where users can fill out the form to begin the process of ordering custom artwork.

The links have an animated hover effect. 
The navigation is clear and easy to understand for the user.

The navigation bar is responsive:

On Mobile Devices the navigation bar is hidden and is toggled by a palette button on the right-hand side.

![Navbar on mobile](documents/Navbar-Mobi.JPG)

When the palette menu is clicked, there is a dropdown menu with the links in the same order. 

![Navbar mobile with menu expanded](documents/Navbar-Mobi-Expand.JPG)

## Home Page
#### Represents:
- The main business of the artist.
- Describes the artist and their style.
- Shows live event dates and info.
- Invites users to fill out the commission form.
 
 ![Home Page Screenshot](documents/Home-Page.jpg)

### Banner Section
The Banner section has a fixed background image.
Directly below the banner is an information section that contains:
- The name of the artist's website.
- Short description of the artist’s style.
- Contact button that leads directly to the commission page.

![Banner Section](documents/Banner-Section.JPG)

### Art Styles Section
- The Art Styles Section begins with a short description of the artist’s mediums and reminds users they can order custom art.
- The Art Styles Section has some images of recent artworks, which can also be seen in the gallery.  One image for each medium type the artist uses.
- Entices viewers to consider ordering a piece of custom artwork.

![Art styles section](documents/Style-Section.JPG)

### Events Section
- The Events section has four upcoming events and one ongoing event, gallery showings, art sales and a paint-along session.
- Each box has an icon displayed with the text.
- Each box has the address and date of the event listed.
- Each box is transparent and situated on a background image.

![Events Section](documents/Events-Section.JPG)

### Contact Us Section
- The Contact Us Section has an explicit message for the visitors of the website to contact the artist.
- It contains an email and phone number so users can query about things not related to ordering art or that aren’t covered by the form.
- It also has a button that directs to the commission page.  

![Contact Section](documents/Contact-Section.JPG)

### Footer
The footer contains social media links that open in a new tab.  

![Footer section](documents/Footer.JPG)

## Art Gallery Page
- The Gallery page has an identical banner image and a message for the visitors that contains a short description and invites them to hover over an image to learn more.
- It has a button after the description that leads to the commission page.
- It has photos of past artworks completed by the artist and serves as a virtual gallery.
- The gallery is responsive, the amount of columns will depend on the user’s screen size.
- Each image has a description of the artwork that can be seen when the user hovers a mouse over the image; or taps when on a mobile or tablet.
- The description contains the name of the artwork, the medium used and the surface it was painted on.
- It has a footer which is identical to the home page's footer.

![Gallery Page](documents/Gallery.jpg)

## Commission page
The Commission page contains a contact form:
- All text input fields are customized.
- All inputs are set to be required to be filled out.
- It has a custom dropdown matching the submit button with four options for the desired medium: Oil, Acrylic, Gouache and Watercolour.
- The text inputs, dropdown and submit button are animated on hover.
- The page is responsive on all common screen sizes.
- The submit button leads to the Thank You page. 

![Commissions Page](documents/Commissions.jpg)

## Thank You Page
- The Thank You page appears after submitting the commission form.
- It contains a thank you message with some additional information about order times.
- There is a button below the message which brings the user back to the home page.

![Thank You Page](documents/Thanks-Page.JPG)


# Technologies Used
HTML was used as the foundation of the site.

CSS - was used to add the styles and layout of the site.

CSS Flexbox - was used to arrange elements on the pages.

CSS Grid - was used to make "gallery" and "commission" pages responsive.

VSCode was used as the main tool to write and edit code.

Git was used for the version control of the website.

GitHub was used to host the code of the website.

# Design
## Color Scheme
The project uses a limited color scheme, found [here](https://looka.com/blog/12-fall-color-palettes/).  The chosen palette was number 12 – Idle Afternoon, with the two colors specifically being `#979f83` and `#192e25`.  These were converted to RGBA for when transparency was needed.  These colors were chosen as they were warm and inviting, and will not clash with any of the artwork.

![Color Scheme image](documents/Colours.JPG)

## Typography
### Main Font
Poppins from Google Fonts is the main font of the website to increase the readability of the content on the pages.

![Poppins font](documents/Poppins-Font.JPG)

### Logo Font
Charmonman from Google Fonts was used to attract viewers' attention to the artist’s logo.  It was chosen as it looks handwritten and matches the theme of the site.

![Charmonman font](documents/Char-font.JPG)

## Testing

- I tested this page in different browsers to ensure it worked.  The browsers tested were Chrome, Firefox and Safari.
- I have used DevTools to confirm that the project is responsive and looks good on all standard screen sizes.
- I have proofread all the text and checked that elements are easy to read and understand.
- I have tested the commission form and confirmed the animated elements work.  I have also checked to ensure the Thank You page is loaded after the user hits the submit button.

### Validator Testing
HTML
- One error was found and left in the project after being put through the official [W3C validator](https://jigsaw.w3.org/css-validator/).  This is explained below in the 'Future Improvements' Section.

CSS
- No errors were found when passing through the official [(Jigsaw) validator](https://validator.w3.org/)


# Deployment
### Deployment to GitHub Pages
The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Main Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://rachelfromireland.github.io/the-artful-rachel/).
### Deployment Locally
In order to make a local copy of this project, you can clone it. In your IDE Terminal, type the following command to clone my repository:

git clone https://github.com/RachelfromIreland/the-artful-rachel.git

# Future improvements
- Image placement: One of the errors flagged in the HTML coding was that the "height" and "width" of the images on the Home and Gallery pages should have a number but a percentage is listed.  I tried several times to fix this but just made things worse.  I decided to leave this code as is with the hope of fixing it in the future with some help.

- Commit messages.  I’m very new to coding and feel I can commit more frequently with more descriptive messages.

- Work more closely with a mentor for guidance.  I was assigned a new mentor (at my request) before submitting the project so the final project has not been checked by a mentor.  I’m sure there are some areas I could have done better.
# Disclaimer:
The reason an error was left in and for my mentor change is because of recent health issues.  This has been discussed with Student Care and I am feeling supported.  The timing of this first project and the fact I've already been granted an extension just mean I am too late to ask for help to fix the errors I found.  I will do much better with this in the future.

# Credits
## Content
Inspiration for the footer as well as style elements cited within the code come from Code Institute’s Love Running project. 

Elements of the CSS styling are directly inspired by my mentor Julia Konovalova’s “Animal Shelter” project, these have also been cited in the code.

The Gallery page’s hover animation which shows text was inspired by a YouTube video by [Kevin Powell](https://www.youtube.com/watch?v=ceNMP-aQkQ4).

## Media
All the images for the website are the author’s own.
# Tools
W3Schools was a huge help for me in understanding how to make the things I wanted to code more readable.


