[Responsive Image](https://imgur.com/AnhXoen)

# I Prevail - website for fans of the band

This project was designed to give new or current fans access to information about the band I Prevail, including a video of their music, links to tour dates and merchandise and a short bio about the band and the members plus the ability to contact the band to enquire about booking them for an event.
 
## UX

The site is designed for users to learn more about the band, keep up to dates on show images, music, merchandise and tour dates, with that in mind the site is set into 3 separate pages, the homepage being where the all users will land gives information or shares media for anyone who is interested in I previal. The gallery page for those looking to keep up on the bands shows and the about us page where new or returning fans can learn more their favourite band members.
 
### First time users
- As a first time user, I want to hear the latest music so I can learn more about the bands music
- As a first time user, I want to read about the band and members so I can learn more about them
- As a first time user, I want to see pictures of the band so I can see what shows are like

### Returning users
- As a returning user, I want to see tours information for the band so I can look to attend a show
- As a returning user, I want to see any new merchandise that is available to buy as a fan
- As a returning user, I want to enquire about booking the band to play at a show 

### Frequent visitor
- As a frequent visitor, I want to check out any new images from the latest show to keep up to date on the band

## Features

### Existing features

- Tour alert - allows users visiting to see band are on tour and click link to go to official tour page to look for shows and tickets
- Navbar - allows all users to navigate to all pages of wesite by clicking page required, also has button to open form to book band
- Music video embedded - allows all users to view the bands latest music video to either keep up to date or learn about their music
- Merchandise images - allows users to see the latests items for sale in the shop, clicking on the image will take them to shop to purchase items
- Gallery image carousel - gives all users the ability to see the latest pictures from the bands shows by scrolling through carousel using built in arrows
- Gallery - allows users to see some of the best images from previous shows, clicking on images brings them to center of page and enables a simple gallery scroll for easier viewing with caption information.
- About us - gives users the ability to learn more about the band by reading information provided on page
- Download poster - gives all user access to a free poster to downlaod by clicking on the icon in the footer
- Book us button - allows user to enquire about booking the band, in navbar and footer, by clicking button form opens to provide inforation about booking band and submitting information to enquire about them performing at a show
- Social links - allows user to view other social media platforms for the band by clicking icons in the footer

## Technologies Used

- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** to provide the layout of the pages. Components are also used to create the carousel within the gallery, the modal for booking the band and media object used to display the band info on the about us page

- [JQuery](https://jquery.com)
    - The project uses **JQuery** as part of bootstrap components

- [FancyBox](https://fancyapps.com/fancybox/3/) 
    - The project uses **FancyBox** to create the responsive gallery

- [Popper](https://popper.js.org/)
    - The project uses **Popper** as part of the fancybox gallery

- [FontAwesome](https://fontawesome.com/)
    - The project uses **FontAwesome** to provide the icons used in social links and the download poster icon

- [GoogleFonts](https://fonts.google.com/)
    - The project uses **GoogleFonts** to provide the fonts used on the pages

## Testing - Old

1. Tour alert
    1. Click link to confirm that tour information page is loaded in separate tab

2. Navbar
    1. Click Home link and confirmed index.html was loaded
    2. Click Gallery link and confirmed gallery.html was loaded
    3. Click About Us link and confirmed about.html was loaded
    4. Clicked Book Us button and verified that modal opened (modal testing is below)

3. Music Video
    1. Clicked video and verified that it plays within web page
    2. Clicked YouTube link in video and verified that if clicked youtube page would open in new tab
    3. Clicked full screen button and verified that video would play full screen
    4. When playing full screen clicked exit full screen button and verified page would return to previous started

4. Merchandise 
    1. Clicked image 1 (cd) and verified link to merch store opened
    2. Clicked image 2 (lp) and verified link to merch store opened
    3. Clicked image 1 (hat) and verified link to merch store opened

5. Gallery carousel
    1. Clicked arrows left and right and verified images scroll
    2. Viewed carousel and waited to verified that images auto scroll

6. Gallery
    1. Clicked image 1 and verified that image became centered and caption was visiable
    2. Clicked image 2 and verified that image became centered and caption was visiable
    3. Clicked image 3 and verified that image became centered and caption was visiable
    4. Clicked image 4 and verified that image became centered and caption was visiable
    5. Clicked image 5 and verified that image became centered and caption was visiable
    6. Clicked image 6 and verified that image became centered and caption was visiable
    7. Clicked image 7 and verified that image became centered and caption was visiable
    8. Clicked image 8 and verified that image became centered and caption was visiable
    9. When image was centered used arrow buttons and verified that highlighted image would scroll to next or previous image

7. Modal
    1. Completed form using valid data and submitted and verified that no errors happened
    2. Tried to submit empty form and verified required fields highlighted to user
    3. Input invalid email and verified that error message was presented
    4. Clicked close button and verified that user able to close modal if no longer needed

8. Footer
    1. Clicked icon for free poster and verified poster opened in new tab
    2. Clicked Book Us button and verified form opened 
    3. Clicked social links and confirmed all social media platforms opened to correct places and in new tabs

## Testing - New

### First time users testing
- As a first time user, I want to hear the latest music so I can learn more about the bands music
    a. users arrive at the home page with the latest music available below the hero image.
    b. users are able to play the embedded youtube video to hear the latest music immediately without navigation or leaving the page.

- As a first time user, I want to read about the band and members so I can learn more about them
    a. users can you easily see the option within the navigation bar named 'About Us' giving them a clear indication of where to find out more about the band.
    b. when arriving on the 'About Us' page the information about the band is the first thing on the page, giving users a quick way to find out about the band.
    c. by scrolling down on the page users can quickly navigate to the band members information to learn more about erach member, including a picture on screen sizes above or equal to 768px (width).

- As a first time user, I want to see pictures of the band so I can see what shows are like
    a. users can you easily see the option within the navigation bar named 'Gallery' giving a clear indication of where the gallery of the band can be found.
    b. when on the Gallery page users are immediately able to see the latest show images, these can be scrolled through using the carousel.
    c. by scrolling down images of the band are avialble to view, each able to be clicked on to bring to forefront and making viewing the images easily.
    d. while viewing one image of the gallery after clicking/tapping on it, users can you the navigation arrows of the gallery to view the rest of the images without needed to minimise and return to main gallery.

### Returning users
- As a returning user, I want to see tours information for the band so I can look to attend a show
    a. on the home page the tour alert is visible on all screen sizes at the top of the page, giving quick and easy access to the tour information for the band.

- As a returning user, I want to see any new merchandise that is available to buy as a fan
    a. scrolling down on the home page, images of available merchandise are clearly viewable to give users a quick view on available items.
    b. a message below these images clearly informs users that they can click on the images to go to the full store.
    c. clicking on the images opens the full store for the user, this is done in a new tab to enable the user to keep their place on the site without the need to navigate through the page again.

- As a returning user, I want to enquire about booking the band to play at a show
    a. users can book the band using the call to action button within the nav bar (on screen sizes of 768px and higher) and the footer (all screens) the button is shown in a contrast colour to make it stand out and easily spotted by users.
    b. user can complete the mo0dal (form) that is called when the Book Us button is pressed, this has named fields so easily show what information is required and error messages to help the user in case of missing information.
    c. when the form is completed a green submit button is clearly displayed to show the user that it needs to be submitted.
    d. once submitted the form disappears to enable the user to continue browsing.

### Frequent visitor
- As a frequent visitor, I want to check out any new images from the latest show to keep up to date on the band
    a. users can you easily see the option within the navigation bar named 'Gallery' giving a clear indication of where the gallery of the band can be found.
    b. when on the Gallery page users are immediately able to see the latest show images, these can be scrolled through using the carousel.

1. Tour alert
    1. Click link to confirm that tour information page is loaded in separate tab

2. Navbar
    1. Click Home link and confirmed index.html was loaded
    2. Click Gallery link and confirmed gallery.html was loaded
    3. Click About Us link and confirmed about.html was loaded
    4. Clicked Book Us button and verified that modal opened (modal testing is below)

3. Music Video
    1. Clicked video and verified that it plays within web page
    2. Clicked YouTube link in video and verified that if clicked youtube page would open in new tab
    3. Clicked full screen button and verified that video would play full screen
    4. When playing full screen clicked exit full screen button and verified page would return to previous started

4. Merchandise 
    1. Clicked image 1 (cd) and verified link to merch store opened
    2. Clicked image 2 (lp) and verified link to merch store opened
    3. Clicked image 1 (hat) and verified link to merch store opened

5. Gallery carousel
    1. Clicked arrows left and right and verified images scroll
    2. Viewed carousel and waited to verified that images auto scroll

6. Gallery
    1. Clicked image 1 and verified that image became centered and caption was visiable
    2. Clicked image 2 and verified that image became centered and caption was visiable
    3. Clicked image 3 and verified that image became centered and caption was visiable
    4. Clicked image 4 and verified that image became centered and caption was visiable
    5. Clicked image 5 and verified that image became centered and caption was visiable
    6. Clicked image 6 and verified that image became centered and caption was visiable
    7. Clicked image 7 and verified that image became centered and caption was visiable
    8. Clicked image 8 and verified that image became centered and caption was visiable
    9. When image was centered used arrow buttons and verified that highlighted image would scroll to next or previous image

7. Modal
    1. Completed form using valid data and submitted and verified that no errors happened
    2. Tried to submit empty form and verified required fields highlighted to user
    3. Input invalid email and verified that error message was presented
    4. Clicked close button and verified that user able to close modal if no longer needed

8. Footer
    1. Clicked icon for free poster and verified poster opened in new tab
    2. Clicked Book Us button and verified form opened 
    3. Clicked social links and confirmed all social media platforms opened to correct places and in new tabs

I had family and friends review and use the website using a variety of computers and devices to make sure that the website functioned properly and that the UX worked as intended with positive results.

## Deployment

Deployment was done using git pages. By going into setting and options, scrolling down to github pages and choosing the master branch of my repository

## Credits

### Content
- Band wiki section text was copied from [Wikipedia article I Prevail](https://en.wikipedia.org/wiki/I_Prevail)

### Media
- Gallery and carousel images were sourced from [LiveMetalBlog](https://livemetalblog.wordpress.com/2018/05/30/rock-on-the-range-photos-i-prevail-05-20-18/)
- Full band image was sourced from [Billboard](https://www.billboard.com/articles/columns/rock/8504650/i-prevail-trauma-paranoid)
- Merch images were sourced from [FearlessRecords](https://store.fearlessrecords.com/pages/i-prevail)

### Acknowledgements

- A few acknowledgements here that I would have been stuck without;

- Help with the youtube video wrapper and making it responsive came from [CSStricks](https://css-tricks.com/fluid-width-video/)
- Help with text area and rows used in the modal came from [Stackoverflow](https://stackoverflow.com/questions/48557955/how-to-increase-height-of-textarea-using-bootstrap-rows-and-columns)
- Help with centering fancybox gallery images when screen sizes varied came from [Stackoverflow](https://stackoverflow.com/questions/21199737/jquery-fancybox-content-not-centering-in-chrome/54231869)
- Responsive image at the top of readme created using [Am I Responsive](http://ami.responsivedesign.is/)
- The knowledge to create this was learned from my course with the code institute and also the 2 mentors I had to help with this, Guido Cecilio for helping with the planning and Spenser Barriball for mid project and end project help and reviews