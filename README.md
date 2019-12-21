# Stream One Project - Fade Zone Barbers

This is a website I have created for a fictitious barbershop known as "Fade Zone Barbers". 
I chose to create my own project idea to demonstrate my capabilities of HTML/CSS.

The website contains a home page that includes content about the barbershop and the pricelist. 
The gallery page includes a masonry style gallery to showcase some of the barbershops haircuts.
And the contact page for the user to make an enquiry or give feedback.
 
## UX

This website is created for the owner of Fade Zone Barbers to attract more customers to the barbershop, my project helps them achieve this by providing a sleek and simple design that is pleasing to the eye.

As a customer I would want to see basic information about the barbershop and what they would charge for their services.
I would also want a gallery to see the quality of their service, and in addition a contact page for me to get in touch with the barbershop if I had any further enquiries.


This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

I wanted the Home page to contain important information about the barbershop such as what it's about and the pricelist, so the user is greeted with this when they first load the website.

I chose to go for a masonry approach when creating the Gallery page as I wanted to showcase a large number of images as examples of the types of haircuts the barbershop specializes in to the user, desktops will display these images in 5 columns, whereas smaller devices will collapse the page into 3 columns.

The contact form has a simple layout, a box split into two sections, one contains basic contact information and the address, the other contains a standard contact form for the user to submit feedback.
 
### Existing Features

- Feature 1 - My first feature allows the user to interact with the navigational items by hovering the cursor over them.
- Feature 2 - Similar to the navigational bar, the social media links in the footer also interact with the user when the cursor is hovered over.

### Features Left to Implement

- Feature idea - I would like to build a functioning form on the "Contact" page so that the user can submit feedback and it is sent accordingly to the barbershop.
- Feature idea - I would like to implement JavaScript to achieve a modal whereby when a gallery image is selected it will enlarge to the screen.

## Technologies Used

- [FontAwesome](https://fontawesome.com/)
    - The project uses **FontAwesome** to include the social media icons in the footer

- [Google Fonts](https://fonts.google.com/)
    - The project uses **Google Fonts** to achieve fonts more relevant to the styling of the webpage.

## Testing

1. Navigational Bar
    1. Hover the cursor over any of the navigational links.
    2. The hover pseudo class will transition the text from white to gold.
    3. Once activated the page will load the relevant internal link in the same tab.

2. Navigational Bar
    1. Navigate to any of the three pages.
    2. The "active" class will be applied to the link relevant to the page the user is on.
    3. Font size is increased, gold color applied to the text, and a gold bottom border will also apply.

3. Social Media Icons
    1. Hover the cursor over any of the social media icons.
    2. The hover pseudo class will transition the icon from white to gold.
    3. Once activated the page will load the relevant external link in a separate tab.

4. Contact Form Text Inputs
    1. Go to the "Contact" page.
    2. Activate any of the text input fields.
    3. The background color will transition from black to white.

5. Contact Form Submit Input
    1. Go to the "Contact" page.
    2. Hover the cursor over the input submit button.
    3. The background color will transition from black to gold.
    4. The font color will transition from white to black.

The project has media queries that makes the following elements responsive:
1. Header "Fade Zone Barbers"
2. Footer "Social Media"
3. Social Media Icons
4. About Us cover text
5. Price List
6. Gallery layout
7. Contact overlay layout

One bug I have encountered is with the navigational bar. The navigational links seem to appear slightly off center, from what I can identify this is due to an issue with the size of the anchor tags.
This has now been fixed as my mentor identified the bug.

Another issue that my test users and mentor identified was the white space between the gallery images and footer. I have attempted to troubleshoot this and debug the code
but I was unable to find a solution to this problem.

## Deployment
TBA

## Credits

### Content

- The "About Us" content in the home page section in this website was taken from [Headcase Barbers](https://www.headcase-barbers.com/.)

### Media

- All photos were taken from [Pexels](https://www.pexels.com/), a stock image library. And a slightly transparent filter was applied to the "About Us" hero image to lower the brightness.

### Acknowledgements

- I received a large majority of inspiration from the CSS Fundamentals Mini Project [Love Running](https://courses.codeinstitute.net/courses/course-v1:CodeInstitute+CF101+2017_T1/courseware/1f0ccaac7a3e43d895c1beae5363f46c/8b3e9adaef764e1d962a85668c799cdd/?activate_block_id=block-v1%3ACodeInstitute%2BCF101%2B2017_T1%2Btype%40sequential%2Bblock%408b3e9adaef764e1d962a85668c799cdd).
- My mid point review session with my mentor gave me the idea to amend the Gallery layout to a masonry style instead of the previous grid I was trying to achieve.
- The Tutor support team offered me assistance that allowed me to align the "About Us" text in the center of the hero image on the Home page.
- My Mentor informed me that the bug on the navigational bar was due to the padding initially being removed, this has since been amended.
- I reference [W3Schools](https://www.w3schools.com/) as the online library that I used for basic troubleshooting.
- The CSS code has been validated using the [CSS W3C Markup Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input)
- The HTML code has been validated using the [HTML W3C Markup Validation Service](https://validator.w3.org/#validate_by_input)