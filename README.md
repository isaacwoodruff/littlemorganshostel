# Little Morgans Hostel

This is a fully responsive website that is a prototype for a real business called Little Morgans Hostel. This project is for the User-Centric Frontend Development Module at the Code Institute. Find a live demo [here.](https://isaacwoodruff.github.io/littlemorganshostel)


## UX

My objective for this website was to create an online presence and persuade visitors to either book a room or make contact. It was given a minimalistic design so that it was simple and intuitive for users to interact with. I chose a mobile first approach because most travellers would be using their mobile to look for rooms.


I wanted to provide them with a small bit of info at the start to stop them from getting bored and to keep them interested with a video of what the local area is like. I gave them a quick view of the facilities available. At the end of the facilities section I placed a BOOK A ROOM button as a call to action. I wanted them to see feedback from other guests so they could judge from others experiences so I added a reviews section. I want guests to have a way to contact the hostel with any questions so I added a contact form and then contact info in the footer.

### User Stories

A traveller visiting Ometepe Island in Nicaragua decides that he wants to find a hostel to stay at that offers food and drinks.


* I want to know what the rooms and facilities look like so I click on Facilities in the navigation bar at the top of the page which brings me to the facilities section with pictures and information about each facility.

* I want to book a room so I look for a link in the navigation bar which brings me to Little Morgans page on HostelWorld.com that shows a booking system.

* I want to ask the hostel a question so I look for a contact link in the navigation bar which brings me to a contact form. Underneath the contact form I can see the phone number and email address of the hostel. Next to these are links to the social media pages of the hostel which I can choose to contact them through.

* I want to see how other people found their stay at the hostel so I look for a reviews section on the site and find reviews of peoples experiences.


### Wireframe

For the wireframe I used Figma. You can find a demo [here](https://www.figma.com/proto/O7nG50WtbLtGdR44jEKAUl2A/Little-Morgans-Hostel?node-id=7%3A34&scaling=scale-down).


I designed the wireframe for a mobile version of the site. It helped me a lot to get a more solid idea for the layout and style of the site. I made some changes throughout the development but the structure is still very similiar.


## Features

### Existing Features
* **Responsive and fixed-top navbar:** Fully responsive navbar with a fixed-top ONLY on smaller devices.

* **Smooth scrolling:** Smooth scrolling animation when a link is clicked.

* **Embeded YouTube video:** Allows users to watch what the local area around the hostel is like.

* **BOOK A ROOM button:** Is a call to action that prompts users to book a room after seeing pictures of the hostel.

* **Carousel:** Allows users to read the best reviews presented in a clean, minimal way.

* **Contact form:** Lets users contact the hostel by filling out a contact form.


### Features Left to Implement

* **Gallery grid:** A grid of photos that the user can click on the see more of the hostel and surrounding area.

* **Functional contact form:** The current contact form is unable to send data. This functionality still needs to be implemented.

## Technologies Used

- [Bootstrap](https://getbootstrap.com/)
    - The project used the **Bootstrap** framework to help create a responsive mobile-first design.

- [Cloud9](https://c9.io)
    - The project used **Cloud9** as an integrated development environment.

- [Google Fonts](https://fonts.google.com/)
    - The project used **Google Fonts** to style the fonts of the site.

- [FontAwesome](https://fontawesome.com/)
    - The project used **FontAwesome** to style social media links and for carousel indicators.

- [Git](https://git-scm.com)
    - The project used **Git** for version control during the development process. 

- [GitHub](https://github.com/)
    - The project used **GitHub** for a remote repository.

- [GitHub Pages](https://pages.github.com/)
    - The project used **GitHub Pages** for hosting.

- [JQuery](https://jquery.com)
    - The project used **JQuery** to simplify DOM manipulation.

- [Autoprefixer](https://autoprefixer.github.io/)
    - The project used **Autoprefixer** to add prefixes to the CSS for cross browser compatibility.

- [Figma](https://www.figma.com/)
    - The project used **Figma** to build wireframes in the planning stage of development.


## Testing

1. Book a room:
    1. Click the Reservation link in the navigation bar and it opens a new tab to HostelWorld.com
    2. Click the BOOK A ROOM button above the reviews section and it opens a tew tab to HostelWorld.com
    
2. Review section:
    1. Scroll down to the reviews section and click the right indicator, this brings up the next review
    2. Click the left indicator, this brings up the previous review

3. Contact form:
    1. Click the contact us link in the navigation bar which scrolls to the contact form
    2. Try to submit the empty form to make sure that an error message appears about the required fields
    3. Try to submit the form with an incorrect email address and make sure that an error message appears for the email input

4. Verify links:
    1. Click on every single link in the navbar, all scroll to relevant sections except Reservation link which opens new tab to HostelWorld.com
    2. Click on BOOK A ROOM button which opens new tab to HostelWorld.com
    3. Click on all three social icons in the footer which open up each relevant link in a new tab

5. Embeded video:
    1. Click play on the embeded YouTube video which plays without error

6. Responsiveness:
    1. Use DevTools in Google Chrome and check that everything adjusts to the new screen sizes for desktop, tablet, and mobile

7. Smooth scroll:
    1. Click on each navigation bar link, this scrolls along the page to the relavant sections with a 'smooth scrolling' effect

8. CSS and HTML Validation:
    1. I used [CSS Validator](https://jigsaw.w3.org/css-validator/) and [HTML Validator](https://validator.w3.org/) to validate the projects code

8. Cross browser compatibility:
    1. I used [Browserling](https://www.browserling.com/) to test across multiple browsers which include Firefox, Chrome, Safari, and Internet Explorer

### Testing Tools Used

- [Browserling](https://www.browserling.com/)
    - The project used **Browserling** to test cross-browser compatibility.

- [CSS Validator](https://jigsaw.w3.org/css-validator/)
    - The project used the **CSS Validator** to validate the CSS.

- [HTML Validator](https://validator.w3.org/)
    - The project used the **HTML Validator** to validate the html.

