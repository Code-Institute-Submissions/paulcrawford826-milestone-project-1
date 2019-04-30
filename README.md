# Flatcap Carnival | One-page Website for Code Academy User Centric Design Milestone Project

In this project I have created a static one-page website for a band. I have used a mobile first approach ensuring that the website looks good on all screen sizes. The website is broken down into 5 section with navigation between sections.

The HTML and CSS files have been validated and there are no errors.
 
## UX
 
The first thing I done in the UX process was to research the band and gather as much information as possible, I spoke to the lead singer who is a family member and also looked at their current website. 

After my research I went through some the following user stories:

- As a potential fan, I want to find out information about the band, so that I can see what genre music they play.
- As a potential fan, I want to listen some music the band plays, to see if I would like it.
- As a fan, I want to find out where/when the band are playing, so that I can see what gigs I can go to.
- As a fan, I want to be able to book tickets to gigs, so that I don’t have to search other sites for tickets.
- As a fan, I want to keep up to informed about new releases, so that I can buy their new music.
- As a potential booker, I want to listen to the band, to find out if they are what I want for my function.
- As a potential booker, I want to see the band in action, to see how they perform.
- As a potential booker, I want to see contact the band, to find out if they are available.

I then created 3 different wireframes, a 5-page website and 2x 1-page websites which can be found in the assets folder hosted here [Wireframes]( assets/wireframes). after evaluating the pros and cons I decided to go with the one-page website [version 1.3]( assets/wireframes/1.3) as this would best suit the functions required. I then developed the website, initially inputting the basic structure and all the information for the final site then working my way to the design phase with HTMl5 and CSS3 using the mobile first approach ensuring that the website functioned correctly on the smallest screen first then worked my way up to the largest screen.

This website was built mainly for fans of the band to keep up to date with the band but can also be used by potential fans and promoters to book the band for gigs. 

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Fixed Navigation bar - allows all users see the band Logo and navigate the site with ease, being a fixed top navbar allows access to the navigation at all times without scrolling.
- Book tickets to gigs - allows fans and potential fans to book tickets to gigs, by clicking a button they can purchase tickets to chosen gigs.
- View videos - Allows all users to view selected videos, by clicking play in an embedded YouTube video.
- Listen to music - Allows all users to listen to the band play, by clicking play in an embedded SoundCloud media player.
- Contact the band - Allows all members to contact the band, by filling in name, address, subject and message into a form and clicking the submit button.
- Social - Allows all members to keep up to date on the band and like/follow the bands social media accounts, by clicking on the relevant social media icons in the footer section.

### Features Left to Implement

- Create function for the gigs section to pull data from a database keeping it up to date.
- Implement ticket buying feature and link buy ticket button to it.
- Create a functioning contact us feature

## Technologies Used

- [HTML5](https://www.w3schools.com/html/html5_intro.asp)
    - The project uses **HTML5**.

- [CSS3](https://www.w3schools.com/css/css_intro.asp)
    - The project uses **CSS3**.     
    
- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** to simplify responsive design process.

- [JQuery](https://jquery.com/)
    - The project uses **JQuery** required for boostrap.js.

- [Popper.js](https://popper.js.org/)
    - The project uses **JQuery** required for boostrap.js.

## Testing

I tested the website using chrome developer tools viewing all sections and features on each device emulator, I also tested the site on Apple iPad Pro and iPhone 7 devices. during testing I found that in the chrome device emulators the background images were showing up correctly but on the actual device the images were not rendering correctly and were zoomed in. This issue was fixed by removing 1 line of code from styles.css. 

I worked through my user stories 1 at a time and ensured that all features were working as they should on all chrome emulators and on the devices available to me at the time. various issues arose and they were corrected resulting in the final product.

1. View videos:
    1. Go to the Media section
    2. click on the embedded YouTube video
    3. Try to play the video in full screen and see if the video plays correctly

2. Listen to music:
    1. Go to the Media section
    2. click on the embedded SoundCloud media player
    3. try to play the music and see if any error occurs

3. Contact form:
    1. Go to the "Contact Us" section
    2. Try to submit the form with an invalid email address and verify that a relevant error message appears

4. Social media function
    1. Go to the footer 
    2. click on the social media section to see if the correct website is displayed and it is opened in a new tab

There are a few differences on the site depending on what device/screen size you are viewing on:

On extra small devices (up to 480px): 

- All sections are shown as a single column

On screen sizes below 575px

- The navigation bar is shown as a Hamburger menu.

On screen sizes 577px and below:

- The copyright text is shown centred in singe column.
- The social media icons are shown centred in singe column.
- Padding throughout the page is reduced to 10px.
- The band name on the home section top margin is reduced to 25rem.

On small devices (768px to 991px):

- The meet the band item is shown in 2 column format now showing the band members function.
- The gig section is shown in a 3-column format from this size up.
- The media section is viewed in a 2-column format only showing 2 videos and 2 songs.
- The contact section is viewed in a col-md-6 with an offset-md-4 to centralise it on the page.
- The footer is shown as in a 2-column layout with the copyright aligned left and the social section aligned right from this point on.

On all other devices (992px and up):

- The meet the band item is shown in 3 column format.
- The media section is viewed in a 2-column format only showing 2 videos and 2 songs.
- The contact section is viewed in a col-md-6 with an offset-md-4 to centralise it on the page.

## Deployment

During the development phase I committed the project to GitHub on numerous occasions and once completed I deployed the master branch to [GitHub pages](https://paulcrawford826.github.io/milestone-project-1/)

## Credits

### Content
- The text was copied from the band’s current website [Flatcap Carnival Website](https://www.flatcapcarnival.com/)

### Media
-  Images by [Hayley Roberts](www.imagesbyhayley.com) used with permission.
-  Videos by [Flatcap Carnival](https://www.flatcapcarnival.com/) hosted on [YouTube](https://www.youtube.com/channel/UCVqsMWlbKMd_DD55xWyfV9g)
-  Music by [Flatcap Carnival](https://www.flatcapcarnival.com/) hosted on [SoundCloud](https://soundcloud.com/flatcap-carnival)

### Code Snippets
 - Full screen background images by [CSS Tricks](https://css-tricks.com/perfect-full-page-background-image/)
 - html, body 100% causing scrollbar to appear [Stackoverflow users](https://stackoverflow.com/questions/34357434/html-body-100-causing-scrollbar-to-appear/34357546)

### Fonts
- Pacifico and Open Sans by [Google Fonts](https://fonts.google.com/)

### Favicon
- Favicon and insert code generated by [Real Favicon Generator](https://realfavicongenerator.net)

### Acknowledgements

- I received inspiration for this project from the Code Institute User Centric Frontend Development introduction to bootstrap module.
- The band current website [website](https://www.flatcapcarnival.com/)
- Design feedback from my Mentor Owonikoko Oluwaseun.
