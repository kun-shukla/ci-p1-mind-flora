# Mind Flora

Mind Flora is a site for encouraging users to reap the myriad health benefits of going out in to nature. The site’s main section highlights popular outdoor destinations across the UK, based on the categories of Mountains, Coasts, Lakes and Forests.

In the form section at the bottom of the page, users have the facility to share and post their own favourite outdoor destinations. Thus creating a community driven content site for promoting the benefits of connecting with nature and the positive impact it has on mental well-being.

The live link can be found here - [Mind Flora](https://kun-shukla.github.io/ci-p1-mind-flora/)

![Mind Yoga Am I Responsive Image](assets/docs/readme-images/am-i-responsive-img.png)

[Image Source - Am I Responsive](https://ui.dev/amiresponsive?url=https://kun-shukla.github.io/ci-p1-mind-flora/)

## Site Owner Goals

- To promote and encourage users to connect with nature in the UK with a particular focus on benefits for mental wellbeing.
- To promote a sense of community by allowing for users to share thier own recommended nature spots. Thereby using user-driven content to promote the site's overall aim of improving mental wellbeing.
- To present a user-centric, mobile-first website that is intuitive to use and navigate. And one which is fully responsive across a range of different device screen sizes.
- To use a colour theme and visual appeal that is aligned with the site's core purpose of fostering a sense of calm and mental relaxation.

## User Stories/Goals

- As a busy professional, I seek a website promoting UK nature spots for mental well-being, providing easy access to information about outdoor locations near major cities for relaxation after work.
- As a parent, I want a website that recommends family-friendly nature spots in the UK, offering engaging activities for my children and a scenic environment to relax and spend quality time with my children.
- As a photography enthusiast, I seek a website highlighting visually stunning UK nature spots to capture through my lens.
- As a mindfulness practitioner, I'm interested in a platform suggesting UK nature spots conducive to mindfulness practices, such as meditation, mindful walking and forest bathing to help me along my journey towards mental clarity and calmness.

## Design

The website's use of color. fonts and imagery is essential to providing the user with a positive emotional experience while using the website. The image-driven approach and the use of a subtle green color across various sections of the page promote a sense of calm and relaxation and to tie-in with the overal theme of the website to promote nature for mental well-being. In addition to this, the font style - Montserrat - imported via [Google Fonts](https://fonts.google.com/), alongwith appropriate using of letter spacing and line-height properties gives the site a non cluttered appearance which is pleasing to the eye and promotes relaxation.

## Wireframes

Low-fi wireframes were created using hand-drawn illustrations

 <details>
    <summary>Mobile Wireframe</summary>

![Mobile Wireframe](assets/docs/readme-images/mobile-top.webp)
![Mobile Wireframe](assets/docs/readme-images/mobile-bottom.webp)
![Mobile Wireframe](assets/docs/readme-images/mobile-cat-content-sec.webp)

 </details>

 <details>

 <summary>Desktop Wireframe</summary>
 
![Desktop Wireframe](assets/docs/readme-images/larger-screen-layout2.webp)
![Desktop Wireframe](assets/docs/readme-images/larger-screen-layout.webp)

 </details>

## Features

### Navigation

![Nav bar image](assets/docs/readme-images/navbar.png)

- The navigation bar is fully responsive and has links to the 'About', 'Discover' and 'Share' sections of the web page.
- A design decision was made not to incorporate a 'burger' menu for mobile screens as this would mean an extra 'tap' to get to a particular link. Having said that I am aware there is a trade off here, as an advantage of having a drop down burger menu is that it optimises the use of screen 'real estate'.
- The logo 'Mind Flora' serves as the 'Home' link and takes the user back to the top when they are browsing other sections of the page
- The 'Discover' nav link has a drop-down toggle which, on pressing, opens up a sub-menu that contains links for each of the 4 content categories i.e. Mountains, Coasts, Lakes and Forests.
- The navbar is set to fixed so that, as the user scrolls further down the page, it remains visible at all times.This provides for an optimised navigation experience as the user does not have to manually scroll to the top of the page/use the browser back button. Furthermore a drop shadow effect is applied so that there is clear distinction between the navbar and content being viewed.

### Hero Image Section

![Hero Section Image](assets/docs/readme-images/hero-img.webp)

- This section has an alluring image of a landscape with a short text overlay to provide users with an immediate impression of the site's theme.
- The overlay text is placed deliberately to give it a good contrast against the darker background.

### About Section

![About section image](assets/docs/readme-images/about-sec.webp)

- The About Section provides a snapshot of the purpose/utility of the website.

- The user is then led on to a visually appealing representation of the four main content categories in the form of circular image links which further lead to the respective content section. The text below each of the images are also clickable.

- The design of this section is aimed at enticing users to explore the other sections of the web page by providing an enhanced, image-driven means of navigation

- The image links are fully responsive and change layout/size according to screen size to maintain a positive visual impression.

### Categories Content Section

![Categories Content Section Image](assets/docs/readme-images/cats-content-sec.webp)

- This section contains content relating to each of the four nature categories i.e. - Mountains, Coasts, Lakes and Forests.
- Each category has one recommended place to visit. The aim is to continually expand the content of this section both through curated as well as user generated content via a 'Share a Discovery' form section
- The alternating background colors provide a pleasing look and feel to this section. It is fully responsive and reduces to a single column layout for mobile screens.

### 'Share a Discovery' Form Section

![Form section image](assets/docs/readme-images/form-sec.webp)

- The form section comprises of a background video of falling autumn leaves. The file size and type have been optimised for web whilst preserving quality.
- The form overlays the background with a translucent effect so that the 'falling leaves' can still be seen despite the overlay.
- the overlay although translucent does not get distracted by the video background which auto plays in the background, silently and on loop.
- The form includes data validation features such as 'required' fields and only accepts an email format in the respective input field. If any field is left blank and the user attempts to submit the form a browser prompt will notify the user that an input is required.
- On clicking the 'Share' button and passing data validation the entered data then gets 'stored' via a dummy link provided by Code Institute (the link opens in a new tab) - this is purely for testing purposes.
- The form includes UX enhancing visual feedback features like on hover/focus custom styling i.e. when a input field is hovered over or selected with the cursor, a black outline appears.

- This section encourages users to share thier own content which will then be added to the relevant Category content section of the webpage. This feature will eventually form the backbone of content generation on the website.

### Footer

![Footer image](assets/docs/readme-images/footer-img.png)

- The footer section includes icon links to Mind Flora's Social channels i.e. Facebook, X (previously Twitter), Instagram and Pinterest.
- These links open in a new tab to prevent users from unintentionally navigating away from the site.
- Appropriate use of Aria attributes have been used for Accessibility so that screen readers can work effectively on the icon based links.

### Potential Future developments

- Based on user feedback a mobile 'burger' menu may be implemented
- Creation of an ‘Explore’ section for users to locate Nature walks via an embedded map feature.
- As the pool of user-generated content grows a 'Search' feature will be introduced to effectively filter through the 'library' of content.
- In time the site will provide a feature to enable users to organise 'meetups' to explore the therapuetic benefits of nature as a group of like-minded fellow travel buddies. This will further enhance the benefit to mental wellbeing by combining in a social aspect as well.

## Testing

### Validator Testing

- #### HTML
  - No errors were returned when passing through the official W3C Markup Validator
    - [W3C Validator Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Faliokeeffe.github.io%2Fmindyoga%2Findex.html)
- #### CSS
  - No errors were found when passing through the official W3C CSS Validator
    - [W3C CSS Validator Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Faliokeeffe.github.io%252Fmindyoga%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
