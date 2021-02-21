# Amani Kickboxing Gym
# Table of Content
# General Information
The [Code Institute](https://codeinstitute.net/) Milestone Project 1 requires students to build a static frnt-end website to prsent useful information to users.

This project will demonstate HTML5 and CSS3 skills, as well Bootstrap which was used in the creation of a form.

The project idea is to build a website for a gym. In this case, the website is for a kickboxing gym where information presented on the site will enable users to learn more about the gym and the services/ trainings they offer.

This project was created using the mobile first stategy where a website is created and developed for mobile users first, then tablets and finally desktop users.
# UX
This section highlights the business objectives and user experience .

## Business Objectives 
* Capture a wider market and attract new clients.
* Establish an online presence through the new website and social media interactions.


## User Stories
* As a site owner, I want the landing page to have relevant information, so that visitors can immediately understand what the business is about.
* As a site owner, I want contact details to be available on the landing page, so that visitors can have quick access to contact information.
* As a visitor, I want to easily navigate the site, so that I can quickly find information.
* As a visitor, I want information about training times, so I can know which training days and times work best for me.
* As a visitor, I want to know what services or training is available, so that I can make an informed decision to join the gym.
## Design 
The webiste's design and layout is based on fonts, colors, wireframes, images and icons.

### Fonts
* [Google Fonts](https://fonts.google.com/) was imported to CSS with the Oswald font family being the main font and San Serif the fall back font.

### Wireframes
* Wireframes were created using the [Balsamiq](https://balsamiq.com/wireframes/) software.

* Wireframes were created for Mobile, Tablet and Desktop computers

* A pdf of the wireframes can be found [here](/assets/Wireframes/Amani_Wireframes_MS1.pdf). This file can also be downloaded from Github. (**Please Note:** _[Adobe Acrobat Reader](https://get.adobe.com/reader/) is required to view files in pdf format_).


# Features
The website incorparates a header with the logo on the left a navigation bar with menu items on the left. It aslo incorporates a footer with social media icons and copyright information. The header and footer maintain consistency on all pages.


## Home
The **Home** page allows the user to have ease of access and navigation to all other pages, from the navigation bar, **call-to-action** buttons, and links to other pages and social media platforms in the footer of the page.

The **Home** page fetaure a hero image with a **learn more** button at the bottom center of the hero image. The button, when clicked, takes the user to the **Training** page.

The **About Us** content is created in a **section** with information presented in the center and includes a link to the **Contact Us** page. 

Information about the gym's **opening hours** is also created in a **section** with the content presented in the center. 



## Training 
The **Training** page feature a hero image.The Train page aslo and incorporates the gym's phylosophy.

Two **sections** provide relevant information presented in **two columns** each - with the type of train information and appropriate **image**.

## Contact Us 
The contact us page includes detailed contact information

- [Email address](mailto:info@amanikickboxing.com) - a business email that the user can to contact us
- Phone number - a business contact number that is available during business hours
- Address with directions on [google maps](https://www.google.com/maps/place/Rullstensgatan+176,+906+55+Ume%C3%A5/)
- Contact form - the user can use the form to send inquiries about any of our trainings.
    
 
# Technologies
This project is created with:
* HTML5 - used for building the website
* CSS3 - for styling elements
* Google Fonts - Oswald used for the font-family and Sans-Serif as the fall-back.
* Bootstrap CDN
    - Font Awesome - for Icons
    - Bootstrap
* JavaScript
* Gitpod/Github

# Testing 
The [W3C](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdce4a9da-36f6-4466-bd74-86f87ab6347c.ws-eu03.gitpod.io%2F%23%2Fworkspace%2FAmani-Strength-Training-MS1-Code-Institute&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) CSS Validation Service was used to valid both CSS and HTML code.

## Testing User stories
1. As a site owner, I want the landing page to have relevant information, so that visitors can immediately understand what the business is about.
    - From the logo alone, a user can immediately know what the website is about.
    - Hero images demonstate what clients can expect from the webiste and from the gym in general.
    - The **Training** page gives detailed imformation on the services/traininging that are being offered.   

2. As a site owner, I want contact details to be available on the landing page, so that visitors can have quick access to contact information.
    - The **Home** page have contact details listed. The **Email** address opens up an external link to microsoft mail which lists the most used emails. 
    - From the navigation bar, the visitor can access contact details by clicking the **Contact Us** menu.
3. As a visitor, I want to easily navigate the site, so that I can quickly find information.
    - The site has a navigation bar in the header with menu items (Home, Training and Contact Us) that link to their respective pages.
    - The site also features a footer with socila media icons that open externally to their respective webistes.
4. As a visitor, I want information about training times, so I can know which training days and times work best for me.
    - Information on opening hours on the **Home** page is clearly displayed.
5. As a visitor, I want to know what services or training is available, so that I can make an informed decision to join the gym.
    - On the **Training** page, detailed information about the trainings offered is clearly displayed with accompanying images. 
## Functional Testing
### All pages
The testing below is identical on all pages (Home, Training, and Contact Us)
1. logo
    - Clicking on the logo will return the user to the home page
2. Navigation bar
    - Menu Items collapse to a second line when the size size is set for mobile phones.
    - The active page is highlighted with a darker grey and inactive menu items with a lighter grey color.
3. Contact Us link
    - when clicked, leads the user to the Contact Us page. This link is blue when inactive to draw emphasis on it and when hovered over, turn grey with a margin below it.
4. Social Media Icons
    - Facebook, Twitter and Instagram icons, when clicked, direct the user to respective websites. All social media links open in new tabs.
    
### Home Page
1. Learn more
    - This button, turns green when hovered over, and when clicked, directs the user to the **Training** page.
2. Email address
    - The email address is blue when inactive and when hovered over turns grey with a margin below. Clicking the email address directs the user to their prefered email service.
             ![Email address link](/assets/images/email_address_link.png)
### Contact Us Page
1. **Click Here** opens an external page with directions on google maps. This link is also blue when inactive and when hovered over turns grey with a margin below
2. Contact form
    - All fields are required.
        - Clicking the submit button without any input in the field:
            ![No input](/assets/images/Form_submit_no_input.png)
        - Entering wrong format for email address:
            ![Wrong email format](/assets/images/email_address_wrong_format.png)
    - When all fields are correctly input, form submits successfully.
# Deployment
# Credits
Many resources were used to create this website.
## Images
All images were free to use and downloaded for [Pexels](https://www.pexels.com/search/boxing/) website.
All images were traced back to their orignal source which was [Pexels](https://www.pexels.com/search/boxing/).
## Code
#### HTML5
* [Bootstrap](https://getbootstrap.com/docs/4.3/getting-started/introduction/), a popular front-end open source toolkit has been used for the columns, rows, buttons and form.

#### CSS3

* Some of the CSS code was edited using the google inspect tool to style the elements better and create a more responsive webiste.

## Icons
* [Font Awesome](https://fontawesome.com/) was used for the social media icons. Here, the free icons were selected and styled to match the overall color-scheme of the website. 

## Other resources
* [w3schools.com](https://www.w3schools.com/default.asp): used for a deeper understanding of HTML and CSS.
* [StackOverflow](https://stackoverflow.com/): Used for troubleshooting. 
* Code Institute course modules.


