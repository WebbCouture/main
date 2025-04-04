﻿## WebCouture Website

View the live project here: https://webbcouture.github.io/main/

![responsive-img](readme-img/am-i-responsive.jpg)

## Overview
Welcome to WebCouture — a clean, responsive website designed to showcase professional web development services for a company targeting female clients. The client requested a pink and purple colour scheme to create a visually appealing, feminine aesthetic. The site is built using HTML, CSS, and a touch of JavaScript, and is fully responsive for desktop and mobile devices, including smaller screens like the iPhone 5.

## Table of Contents
- **User Experience**
- **Features**
- **How Features Support User Stories**
- **Design**
- **Wireframes**
- **Technologies Used**
- **Testing**
- **Deployment**
- **Credits**
- **Acknowledgments**

## User Experience
### First-Time Visitor Goals
- Understand the main purpose of the site quickly.
- Navigate the site easily to find information.
- Locate the info and contact pages effortlessly.
- Learn what the company offers and how to get in touch.

## Returning Visitor Goals
- Quickly access the contact form.
- Find social media links.
- Get in touch to give feedback or ask questions.

## Frequent User Goals:
- As a Frequent User, want to find the company´s contact on WhatApp easy, to call or text them.


## Features
🧭 Navigation Bar
- Appears on all three pages.
- Responsive across screen sizes.
- Displays logo and links to Home, Info and Contact.
- On mobile, navigation links shift below the logo for better visibility.

![navbar-img](readme-img/nav-bar.jpg)

🌸 Landing Page Image and Call to Action
- Pink-themed hero image with the message: "WE BUILD AND DESIGN YOUR WEBPAGE" let clients know what the company do.
- Call to action button to contact form.
- Aimed to immediately attract female users.

![home-img](readme-img/home.jpg)

💬 Tagline
"Web Design & Web Development" text reinforces the company’s services.


## Company Ideals section
The two main things the company do are presented in two sections on the main page. This give the user more information about the organization and the two things (We Build and We Design) they offer. And the customer can also see the third thing thay offer (or most important), support.

![builddesign-img](readme-img/builddesign.jpg)

📝 Info Page
- The Info Page is a page that tells the customer about the company, what they do, services and philosophy.

![info-img](readme-img/info.jpg)


📬 Contact Page
- Allows users to send feedback or inquiries.
- Form includes name and email fields.
- Confirmation message: “Your message has been sent.”

![contact-img](readme-img/contact.jpg)

🔗 Footer
- Present on all pages, identical for consistency.
- Includes social media icons: Facebook, WhatsApp, and Instagram.
- WhatsApp is emphasized for international communication.

![footer.img](readme-img/footer.jpg)

## How these features support the User Stories

![user-img](readme-img/user-stories.jpg)

## Features which could be implemented in the future
- On the index page - add more cool effects, video or photo.
- On the info page - photos, add some reference and pictures and links on webpages that we have done and some quotes from happy customers.
- on the contact page -photos, can add a map and an address when the company have moved in to their office.


## Design
- The pink picture, and the pink/purple style, has been chosen to attract female clients like the customer wanted.
- The info picture has ben chosen to show what the company design - that the webpage to look good on all screen sizes.

🎨 Color Scheme
- We choose our palette from the pink picture that the costumer want to have and mix it well so its easy to read with the background colours and text colours.

🔠 Typography
### Google Fonts used:
- Lato for body text
- Georgia for stylistic headings
- Oswald for standout titles

## Wireframes
**Created with Balsamiq during the planning stage:**

- Main Page Wireframe

![balsamiq1](readme-img/webcouture-balsamiq1.jpg)


- Info Page Wireframe

![balsamiq2](readme-img/webcouture-balsamiq2.jpg)


- Contact Page Wireframe

![balsamiq3](readme-img/webcouture-balsamiq3.jpg)

## Technologies Used
### Languages Used:
- HTML5
- CSS3
- JavaScript

## Frameworks, Libraries & Programs Used
### Google Fonts: 
- was used to import the 'Lato' and 'Oswald' fonts into the style.css file which are used on all pages of the project.
### Font Awesome: 
- was used to add icons for aesthetic and UX purposes.
### Git: 
- was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
### GitHub: 
- is used as the repository for the projects code after being pushed from Git.
### Microsoft Paint 3D: 
- was used for resizing images and editing photos for the website.
### Balsamiq: 
- was used to create the wireframes during the design process.


## Testing
### HTML Validator Results

- index.html ✅ Valid

![menu-img](readme-img/menu-checker.jpg)

- info.html ✅ Valid

![info-img](readme-img/info-checker.jpg)

- contact.html ✅ Valid

![contact-img](readme-img/contact-checker.jpg)


## CSS Validator
![css-img](readme-img/css-checker.jpg)

## Lighthouse scores
- **Performance:** 88
- **Accessibility:** 98
- **Best Practices:** 100
- **SEO:** 100

![lighthouse](readme-img/lighthouse.jpg)

## Browser Compatibility
### Tested on:
- Chrome Version 90.0.4430.212 (Official Build) (64-bit)
- Firefox Version 88.0.1 (64-bit)
- Edge Version 90.0.818.62 (Official build) (64-bit)
- Safari on macOS Catalina (Safari Version 14.0.3)
- Test Cases and Results

## Test Cases and Results

![test-img](readme-img/test-case.jpg)

## Navigation test
![navtest-img](readme-img/navigationtest.jpg)

## Form Validation Tests

### Required Fields
- Scenario: User attempts to submit the contact form without filling out all required fields.
- Expected Outcome: Form submission is blocked and the browser displays an error or highlights missing fields, depending on your validation (HTML5 or JavaScript).

### Invalid Email Format
- Scenario: User types a string that is not in a valid email format (e.g., “abc” or “user@domain” with no TLD).
- Expected Outcome: The form does not submit and a validation error appears, prompting the user to enter a valid email.

### Valid Email Format
- Scenario: User types a properly formatted email address (e.g., “john@example.com”).
-Expected Outcome: Email field validation passes and no error is displayed (assuming all other required fields are filled).

### Optional vs. Required Fields
- Scenario: If you have optional fields (e.g., phone number), confirm that leaving them blank does not trigger an error.
- Expected Outcome: Form can still be submitted successfully if the optional field is empty, and the rest are valid.

### Successful Submission
- Scenario: User completes all required fields with valid inputs, including a valid email, then clicks “Submit.”
- Expected Outcome: The form should submit successfully, showing either a confirmation message (if handled on the client side) or redirecting to a success/thank-you page (if handled on the server).

### Reset/Clear Form (If applicable)
- Scenario: Check if there is a reset button or if the user manually clears the fields.
- Expected Outcome: All fields return to their default state and any displayed errors are cleared.

## Known bugs

When looking at mobile and desktop the bottom text "WebCouture - CRN: 55 - 57 68 132 - Address: 109 Albert Road, Blackpool - Phone: 010-230 30 34"
look good and was at the bottom of the pages, where the footer began.
But if you looked at a big screen, 3840px, there was a bigger space after the text.
The problem was that we have used "br" in html code to make the space.
Afterwards, when we put the text in the footer and change the styling in css for " footer h5 " it worked good on every screen.


## Deployment
- How this site was deployed In the GitHub repository, navigate to the Settings tab, then choose Pages from the left hand menu
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment
- Any changes pushed to the master branch will take effect on the live project
- The live link can be found here https://webbcouture.github.io/main/

## How to clone the repository
- Go to the https://webbcouture.github.io/main/ repository on GitHub
- Click the "Code" button to the right of the screen.
- Click HTTPs and copy the link there
- Open a GitBash terminal and navigate to the directory where you want to locate the clone
- On the command line, type "git clone" then paste in the copied url and press the Enter key to begin the clone process.

## How to Forking the GitHub Repository

- By forking the GitHub Repository, you can make a copy of the original repository in your own GitHub account. 
- This means we can view or make changes without making the changes affecting the original.
- Log into GitHub and locate the GitHub Repository.
- At the top of the Repository there is a "Fork" button about the "Settings" button on the menu.
- You should now have a new copy of the original repository in your own GitHub account.

## Credits
- Content on the menu page was loosely based on menus on Love Running 
- All other content was written by the developer.

## Code
- Fade-in hero image adapted from a CSS tutorial.

## Media
- Colours based on client’s pink image.
- Icons: Font Awesome
- Fonts: Google Fonts
- Images: Unsplash

## Acknowledgments
- Special thanks to mentor Brian Macharia for guidance and constructive feedback during the project.

### Amanda​