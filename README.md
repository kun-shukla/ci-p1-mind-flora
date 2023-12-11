# Mind Flora

Mind Flora is a site for encouraging users to reap the myriad health benefits of spending time in nature. The site’s main section highlights popular outdoor destinations across the UK, based on the categories of Mountains, Coasts, Lakes and Forests.

In the form section at the bottom of the page, users have the facility to share and post their own favorite outdoor destinations. Thus creating a community driven content site for promoting the benefits of connecting with nature and the positive impact it has on mental well-being.

The live link can be found here - [Mind Flora](https://kun-shukla.github.io/ci-p1-mind-flora/)

![Mind Yoga Am I Responsive Image](assets/docs/readme-images/am-i-responsive-img.png)

[Image Source - Am I Responsive](https://ui.dev/amiresponsive?url=https://kun-shukla.github.io/ci-p1-mind-flora/)

## Site Owner Goals

- To promote and encourage users to connect with nature in the UK with a particular focus on benefits for mental wellbeing.
- To promote a sense of community by allowing for users to share their own recommended nature spots. Thereby using user-driven content to promote the site's overall aim of improving mental wellbeing.
- To present a user-centric, mobile-first website that is intuitive to use and navigate. And one which is fully responsive across a range of different device screen sizes.
- To use a colour theme and visual appeal that is aligned with the site's core purpose of fostering a sense of calm and mental relaxation.

## User Stories/Goals

- As a busy professional, I seek a website promoting UK nature spots for mental well-being, providing easy access to information about outdoor locations near major cities for relaxation after work.
- As a parent, I want a website that recommends family-friendly nature spots in the UK, offering engaging activities for my children and a scenic environment to relax and spend quality time with my children.
- As a photography enthusiast, I seek a website highlighting visually stunning UK nature spots to capture through my lens.
- As a mindfulness practitioner, I'm interested in a platform suggesting UK nature spots conducive to mindfulness practices, such as meditation, mindful walking and forest bathing to help me along my journey towards mental clarity and calmness.

## Design

The website's use of color. fonts and imagery is essential to providing the user with a positive emotional experience while using the website. The image-driven approach and the use of a subtle green color across various sections of the page promote a sense of calm and relaxation and ties in with the overall theme of the website to promote nature for mental well-being. In addition to this, the font style - Montserrat - imported via [Google Fonts](https://fonts.google.com/), along with appropriate using of letter spacing and line-height properties gives the site a non cluttered appearance which is pleasing to the eye and promotes relaxation.

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
- The logo 'Mind Flora' serves as the 'Home' link and takes the user back to the top when they are browsing other sections of the page. The idea behind coming up with this name for the website was to marry its 2 main areas of focus - mental wellbeing (Mind) and the connection it has with being out in nature (Flora). It is also a play on the term 'gut flora' and how keeping it in balance is important for overall wellbeing.
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

- This section encourages users to share their own content which will then be added to the relevant Category content section of the webpage. This feature will eventually form the backbone of content generation on the website.

### Footer

![Footer image](assets/docs/readme-images/footer-img.png)

- The footer section includes icon links to Mind Flora's Social channels i.e. Facebook, X (previously Twitter), Instagram and Pinterest.
- These links open in a new tab to prevent users from unintentionally navigating away from the site.
- Appropriate use of Aria attributes have been used for Accessibility so that screen readers can work effectively on the icon based links.

### Potential Future developments

- Based on user feedback a mobile 'burger' menu may be implemented
- Enhanced form features such as ability for users to upload and share an image of destination and to be able to sign up to a newsletter.
- Creation of an ‘Explore’ section for users to locate Nature walks via an embedded map feature.
- As the pool of user-generated content grows a 'Search' feature will be introduced to effectively filter through the 'library' of content.
- In time the site will provide a feature to enable users to organise 'meetups' to explore the therapeutic benefits of nature as a group of like-minded fellow travel buddies. This will further enhance the benefit to mental wellbeing by combining in a social aspect as well.

## Testing

### Validator Testing

- #### HTML
  - No errors were returned when passing through the official W3C Markup Validator
    ![W3C Markup Validator image](assets/docs/readme-images/validator-html.webp)
- #### CSS

  - No errors were found when passing through the official W3C CSS Validator
    ![W3C CSS Validator image](assets/docs/readme-images/valid-css.webp)

- #### Accessibility

  - The site achieved a Lighthouse (Chrome Dev tools) accessibility score of 94% which confirms that the colours and fonts chosen are easy to read and accessible
    ![Lighthouse score image](assets/docs/readme-images/lighthouse-testing.webp)

### Links Testing

- All navigation links tested thoroughly to ensure the user is directed to the correct section of the website at the appropriate 'anchor point'
- Social Media links in the page footer were tested manually to ensure there were no broken links and that they direct the user to the correct page.
- Also ensured appropriate usage of ARIA attributes and that external links opened in a new tab.

### Browser Testing

- The Webpage was tested on Google Chrome, Safari, Firefox and Microsoft Edge web browsers with no issues observed.

### Device Testing and responsiveness

- The website was viewed on a variety of devices such as Desktop, Laptop and mobile devices to ensure responsiveness across a range different screen sizes. The website performed as intended. Responsiveness was also checked extensively via Chrome developer tools across multiple device screen dimensions with no errors observed.

### Solved Bugs

#### 'Anchor point' issue when using page links to navigate to a particular section of the page

- As the Header containing the navbar is fixed I encountered an issue whereby page links to navigate to different sections of the site were 'arriving' at an 'anchor point' concealed by the navbar.
- To resolve this I used the 'scroll-padding-top' property to 'offset' the anchor points just enough to get the top of the targeted section to be fully visible just below the navbar.

#### Issue with achieving desired layout for the 'Categories Content' Section

- I made a design decision to go with Bootstrap for making the webpage fully responsive using the predefined 'grid layout' classes. However I discovered that I was unable to achieve the desired outcome for how I wanted the elements on the page to appear across the various screen size 'break points' (specifically for the 'Categories Content' section)
- My solution to this issue was to introduce flex styling and media queries to tweak the elements precisely and was therefore able to achieve the intended result.

### Known bugs

Issue observed while using the deployed site on iOS Chrome/Safari browsers, whereby the form section's background video does not immediately autoplay (despite being assigned the 'autoplay'/'mute' attributes). However, on visiting other sections and then revisiting the form section via the navbar, the video does usually start to play (though this can be erratic particulary on Chrome it seems).

## Technologies Used

- HTML5
- CSS
- Bootstrap

### Frameworks / Libraries / Programs Used

- [Adobe photoshop](https://adobe.com/) - for compressing image file sizes without reducing quality, converting images/video to a web compatible format.
- [Am I Responsive](http://ami.responsivedesign.is/) - for the Readme file's hero image depicting a mock-up of how the web page looks like across different device screen sizes.
- [Balsamiq](https://balsamiq.com/) - for lo-fi wireframing
- [Bootstrap](https://getbootstrap.com/docs/4.6/getting-started/introduction/) - for implementing responsiveness and the navbar drop-down 'sub-menu' functionality
- [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) - Used for overall development and troubleshooting. As well as for testing responsiveness and site performance scores (Lighthouse)
- [Coolers](https://coolors.co) - for deciding on a compatible color theme.
- [Flaticon](https://www.flaticon.com) - for the site's favicon
- [Font Awesome](https://fontawesome.com/) - Used for Social Media icons in footer.
- [GitHub](https://github.com/) - Used for version control and deployment.
- [Google Fonts](https://fonts.google.com/) - Used to import custom fonts.
- [Visual Studio Code](https://code.visualstudio.com) - Used as the code editor.
- [W3C](https://www.w3.org/) - Used for HTML & CSS Validation.

## Deployment

The project was deployed using GitHub Pages. The steps to deploy using GitHub Pages are as follows:

1. Go to the repository on GitHub.com
2. Select 'Settings' near the top of the page.
3. Select 'Pages' from the menu bar on the left of the page.
4. Under 'Build and deployment' > 'Branch', select the 'main' branch from the dropdown menu.
5. Once selected, click the 'Save' button.
6. Deployment should be confirmed by a message on a green background saying "Your site is published at" followed by the web address.

The live link can be found here - [Mind Flora](https://kun-shukla.github.io/ci-p1-mind-flora/)

## Credits

### Content

[ChatGPT](https://chat.openai.com) - used for generating ideas for the site's content.

### Media

All media files were sourced from the below websites and attributed to the following photographers:

- [Pexels](https://www.pexels.com/)
  - Marek Levak - Hero Image
  - Eberhard Grossgasteiger - 'Mountains' image in 'About' section
  - Unknown - 'Seven Sisters, England' - 'Coasts' image in 'About' section
  - Petra Ravensberg - 'A dirt road between trees' - 'Forests' image in 'About' section
- [Unsplash](https://unsplash.com)
  - Ben Griffiths - 'Sunrise at Ladybower Reservoir' - 'Lakes' image in 'About' section
- [Adobe stock](https://stock.adobe.com)
  - Whitcomberd - 'Hikers on Scafell Pike' image in Category content section (mountains)
  - WavebreakmediaMicro - 'Autumn leaves falling on the camera' video used as background for 'Form' section
- [Country File](https://www.countryfile.com/)
  - Unknown - 'Ullswater, Cumbria, Lake District' image in Category content section (Lakes)
- [Forestry England, UK](https://www.forestryengland.uk)
  - Unknown - 'Cannock Chase Forest' image in Category content section (Forests)
- [Much Better Adventures](www.muchbetteradventures.com)
  - Unknown - 'Kynance Cove in Cornwall' image in Category content section (Coasts)

### Online Resources Used

- [W3Schools](https://www.w3schools.com/)
- [Stack Overflow](https://stackoverflow.com/)

## Acknowledgments

- I found Code Institute's Love Running project and the Bootstrap module on building the 'Whiskey landing page' particularly helpful for refreshing my knowledge on how to use media queries effectively. Various elements of the site were inspired by the Love Running project such as the Footer section and Hero Image section. I followed the CI tutorials on Bootstrap to incorporate the 'Dropdown menu' component for the 'Discover' Nav link sub-menu.

- The design for the project was inspired by the work of a previous CI student. The way their website was designed was highly appealing to me and so I decided to base my own design layout on the same lines. I am therefore very grateful to this former student for their great work and for inspiring me with an idea for my own project. This is the deployed link for their project on Github - [Alison O'Keeffe](https://aliokeeffe.github.io/mindyoga/).
