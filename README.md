# Koryeo Warriors Taekwondo

Koryeo Warriors Taekwondo allows visitors to find out about their local taekwondo club. Visitors can find out about taekwondo, learn about class times and prices, gain insight into what the classes entail and also look at some pictures of students all in the hope of getting a feel of what to expect. Visitors can then contact the instructor to arrange a trial class or find out more. 

![Screenshot of the website on different devices](documentation/screenshot-amiresponsive.png)

The live link can be found [here](https://nhamidi90.github.io/kw-taekwondo)

## User stories

### First time visitor goals:
* As a first time user I want to know a bit about taekwondo so I can decide whether I should pursue it
* As a first time user I want to know about the instructor so I can see if they will be good for me
* As a first time user I want to know about the taekwondo lessons and what to expect, where and when they are held and also the prices for classes so I can see whether they fit into my schedule and how far it is from me
* As a first time user I want to be able to contact the instructor for more information should I have any questions and also to request to join classes
* As a first time user I want the site to be easy to navigate through so I can find what I need
* As a first time user I want the site to be appealing enough to entice me to start taekwondo classes through testimonials and images
* As a parent I want to find out whether there are classes suitable for my child so I can enrol them

### Returning visitor goals:
* As a returning visitor I want to easily find the information on classes to see if they fit into my schedule and budget
* As a returning visitor after carefully considering joining classes, I want to have a way to contact the instructor to get a free trial session
* As a returning visitor I want to check their social media so I can find out more about the club
* As a parent I want to show the pictures to my child so they can decide for themselves whether to join

### Frequent visitor goals:
* As a student or parent of student, I want to be able to access any news such as upcoming competitions and events so I can add them to my calendar and to see how past events went
* As a student or parent of student, I want to see pictures of training sessions and events so I can save them and remember them

## Features

### Navbar

* There are two navbars: one for smaller screens and one for large screens
* The mobile navbar is located at the top of the screen. The logo is on the left an the toggle button on the right so you can open it up. If the viewer is using a desktop or large tablet, this will be hidden.
* The navbar for larger screens is located underneath the hero image. It spreads across the length of the page and is responsive; should need be, the links will overflow to the second line. As the user scrolls down, the navbar will move and stick to the top of the screen. The navbar is easy to navigate and links have an animated effect upon hover. If the user is using a mobile or small tablet, this will be hidden.
* In addition, there will be a bar above the hero image displaying the logo on the left and a 'book a free session' button on the right leading too the contact page. The button has an animated effect upon hover. This will be hidden on smaller screens
* All pages will include the navbar

Links: 
* Home – leads to the home page where visitors can learn about the club and instructor
* About taekwondo – leads to a page which gives the reader an introduction to the basics of taekwondo and some theory
* Classes and pricing – leads to the classes page where visitors can find out what classes exists, when and where classes are held as well as prices
* Gallery – leads to the gallery page where visitors can see pictures of classes/events
* News – leads to the news page where information for students is posted such as competition details, results of grading etc. 
* Contact – leads to the contact page where visitors can fill out a form to contact the instructor, find out the instructor’s contact details and see the map of where classes are held

![Screenshot of the mobile navbar closed](documentation/screenshot-mobile-navbar-closed.png)

![Screenshot of the mobile navbar open](documentation/screenshot-mobile-navbar-open.png)

![Screenshot of the top bar](documentation/screenshot-top-bar.png)

![Screenshot of the main navbar](documentation/screenshot-main-navbar.png)

## Hero image

* The hero image is located at the top of the page
* On all pages apart from the home and response pages it includes the page title

![Screenshot of the hero image](documentation/screenshot-hero.png)

### Footer

* The footer is responsive. In mobile view, you will only see the social icons. 
* On larger screens you will have information on the company including the address, web address, phone number and links to social media
* The links to social media have an animated hover effect
* All pages will include the footer

![Screenshot of the compact footer](documentation/screenshot-footer-small.png)

![Screenshot of the full footer](documentation/screenshot-footer-full.png)

### Home page

*	Includes an introduction the club and reasons why you should study taekwondo. There is a button at the end of the section leading to the classes and pricing page with a hover effect
*	Includes a couple of quotes from students with some pictures
*	Includes a picture and introduction to the instructor. There is an external link to the British taekwondo Council website for users to find out more which opens in a new tab
* The page is responsive to screen size

![Screenshot of index.html](documentation/screencapture-index.png)

### About taekwondo

*	Includes a brief introduction of where taekwondo started. There is also an external link to the federation this club will follow (International Taekwondo Federation) which opens in a new tab
*	Includes the five tenets of taekwondo
*	Includes information on the grading system with images of belts
*	Has a table including some Korean phrases used in taekwondo
*	The page is responsive. As the screen becomes smaller, the images of the belts will disappear


![Screenshot of abouttkd.html](documentation/screencapture-abouttkd.png)

### Classes

*	Contains information on three types of classes arranged in columns: children's, ladies and mixed
*	Each section has a button inviting visitors to book a class by leading them to the contact page. The buttons have a hover effect
*	The page will respond to screen size change
*	Upon hover, or click if on mobile, there is a sweeping motion from top to bottom

![Screenshot of classes.html](documentation/screencapture-classes.png)

### Gallery

* This page has photos arranged in columns which will change depending on the size of the screen
* Smaller screens will display pictures in two columns
* Larger screens will display pictures in three columns
* The size of the photo will depend on the screen

![Screenshot of gallery.html](documentation/screencapture-gallery.png)

### News

* This is a page for the instructor to use to inform their students or any visitor of any news happening in the club
* It has three news items currently, each with an image which will respond to changes in screen size 
* More items can be added in the future

![Screenshot of news.html](documentation/screencapture-news.png)

### Contact Us

* This is where visitors can contact the instructor using the form or see any contact information for themselves
* On the form, only the name and email address are required
* The submit button is animated upon hover
* It includes links to social media with a hover effect
* Visitors can also see a map to the site where classes are held
* The page is responsive and the size of the map depends on the screen size


![Screenshot of contact.html](documentation/screencapture-contact.png)

### Response Page

* After the user submits a form, they will be directed here
* It contains a thank you message with the promise to get in touch with the user
* After 10 seconds, the user will be automatically redirectd to the home page

![Screenshot of response.html](documentation/screencapture-response.png)

## Technologies Used

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) was used to make the main content of the site
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) was used to add styling
* [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) was used to align items on the page
* [Bootstrap](https://getbootstrap.com/) code was used to create various tools including the navbar for mobile view, contact form, buttons and grid system
* [Visual Studio Code](https://code.visualstudio.com/) was the programme used to write and edit code
* [Balsamiq](https://balsamiq.com/) was used to make wireframes
* [Git](https://git-scm.com/) was used for source control management
* [GitHub](https://github.com/) was used to store code for the website
* [GitHub pages](https://pages.github.com/) hosts the website. The live link is [here](https://nhamidi90.github.io/kw-taekwondo/)
* [Adobe photoshop](https://www.adobe.com/uk/products/photoshop.html) was used to crop images for the README.md file

## Wireframes

### Desktop screen
* [Home](documentation/large-home.png)
* [About taekwondo](documentation/large-abouttkd.png)
* [Classes](documentation/large-classes.png)
* [Gallery](documentation/large-gallery.png)
* [News](documentation/large-news.png)
* [Contact Us](documentation/large-contact.png)
* [Response](documentation/large-response.png)

### Tablet screen (small and large)
* [Home](documentation/tablet-home.png)
* [About taekwondo](documentation/tablet-abouttkd.png)
* [Classes](documentation/tablet-classes.png)
* [Gallery](documentation/tablet-gallery.png)
* [News](documentation/tablet-news.png)
* [Contact Us](documentation/tablet-contact.png)
* [Response](documentation/tablet-response.png)

### Mobile screen
* [Home](documentation/mobile-home.png)
* [About taekwondo](documentation/mobile-abouttkd.png)
* [Classes](documentation/mobile-classes.png)
* [Gallery](documentation/mobile-gallery.png)
* [News](documentation/mobile-news.png)
* [Contact Us](documentation/mobile-contact.png)
* [Response](documentation/mobile-response.png)

## Testing

All information on testing can be found on [TESTING.md](TESTING.md)

## Deployment

### Deployment to GitHub Pages

The site was deployed to GitHub pages. To deploy this site: 
  * In the [GitHub repository](https://github.com/nhamidi90/kw-taekwondo), navigate to the Settings tab
  * Select the **pages** link on the left hand side under *Code and automation*
  * Under *Source*, ensure **Deploy from branch** is selected
  * Under *Branch*, select **main** then **save**
  * The page will automatically refresh and provide a link to your site indicating successful deployment.

The live link can be found [here](https://nhamidi90.github.io/kw-taekwondo)

### Local Deployment

* To make a local copy of this project, you can clone the repository by typing the following command into your IDE terminal:

 `git clone https://github.com/nhamidi90/kw-taekwondo.git`

- Alternatively, to open the workspace in Gitpod, you can [click here](https://gitpod.io/#https://github.com/nhamidi90/kw-taekwondo)

## Future improvements
* The news page will grow in size as more items are added so pagination could be introduced
* There is potential for  the site to grow by adding more for current students such as a learning section which can include videos on patterns, theory etc.
* Add fully functional contact form
* As more pictures are added to the gallery it would be good to group those from the same event together

## Credits

### Content

* [Level up taekwondo](https://leveluptaekwondo.com/2018/02/22/13-benefits-taekwondo-will-make-want-black-belt/) was used to write up reasons for doing taekwondo
* My own taekwondo teacher [Tamsin Davis](https://www.taekwondo4all.com/) has also given me lots of information on what happens during lessons and the grading system through attending her classes
* [United Tae kwon do](https://utkd.org/for-students/five-tenets) was used to take information on the tenets of taekwondo
* I also used [Wikipedia](https://en.wikipedia.org/wiki/Taekwondo) to look up the origins of taekwondo
* [Eurolinguiste](https://eurolinguiste.com/martial-arts-vocabulary-in-korean/) was used to check some spelling of korean words

### Media

* All media came from [Pexels](https://www.pexels.com/) and [Pixabay](https://pixabay.com/)
* [Hero image](https://images.pexels.com/photos/4428290/pexels-photo-4428290.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

Homepage 
 * [Instructor](https://pixabay.com/photos/woman-model-karate-taekwondo-sport-6916304/)
 * [Above quote 1](https://www.pexels.com/photo/man-and-girl-in-martial-arts-bowing-down-7045593/)
 * [Under quote 2](https://www.pexels.com/photo/a-group-of-people-standing-barefooted-while-wearing-taekwondo-uniform-7045673/)

 Gallery
 * [Image 1](https://www.pexels.com/photo/men-in-a-taekwondo-match-10496367/)
 * [Image 2](https://www.pexels.com/photo/children-stretching-outdoors-10496375/)
 * [Image 3](https://www.pexels.com/photo/taekwondo-athletes-shaking-hands-6253170/)
 * [Image 4](https://www.pexels.com/photo/man-people-woman-girl-7045571/)
 * [Image 5](https://www.pexels.com/photo/man-people-woman-relaxation-7045600/)
 * [Image 6](https://www.pexels.com/photo/a-girl-standing-on-one-leg-while-looking-at-the-camera-7990084/)
 * [Image 7](https://www.pexels.com/photo/a-woman-in-white-uniform-standing-barefooted-8779304/)
 * [Image 8](https://www.pexels.com/photo/man-people-woman-girl-7045574/)
 * [Image 9](https://www.pexels.com/photo/a-group-of-people-in-taekwondo-uniform-smiling-together-7045667/)
 * [Image 10](https://www.pexels.com/photo/man-love-people-woman-7045608/)
 * [Image 11](https://www.pexels.com/photo/a-woman-in-taekwondo-uniform-while-standing-near-the-brick-wall-7045657/)
 * [Image 12](https://www.pexels.com/photo/fashion-man-love-people-7045736/)

News
 * [News 1](https://www.pexels.com/photo/close-up-shot-of-a-person-holding-a-black-belt-6253308/)
 * [News 2](https://www.pexels.com/photo/a-man-wearing-white-and-black-hachimaki-7045479/)
 * [News 3](https://www.pexels.com/photo/boys-sparring-on-black-mat-7988768/)

### Tools

* [Color space](https://mycolor.space/) was used to pick a colour scheme
* [Tinypng](https://tinypng.com/) and [iLoveIMG](https://www.iloveimg.com/compress-image) were used to compress images
* [online-convert](https://image.online-convert.com/convert-to-webp) was used to convert images to webp

### Code

* [W3 Schools](https://www.w3schools.com/) and [MDN web docs](https://developer.mozilla.org/en-US/) were both used to look up and remind myself of various HTML and CSS syntax
* The page title shadow effect was done using code from [Kinsta](https://kinsta.com/blog/css-text-outline/) 
<!--
text-shadow:
    3px 3px 2px #000,
    -3px 3px 2px #000,
    -3px -3px 0 #000,
    3px -3px 0 #000;
-->

* [Go make things](https://gomakethings.com/how-to-create-a-sticky-navigation-with-only-css/) Helped me make the navbar sticky using only CSS

<!--
position: sticky;
position: -webkit-sticky;
top: 0;
    
 -->

* The hover effects on classes.html were done using [Hover.css](https://ianlunn.github.io/Hover/#effects)

<!--
.hvr-sweep-to-bottom {
    display: inline-block;
    vertical-align: middle;
    -webkit-transform: perspective(1px) translateZ(0);
    transform: perspective(1px) translateZ(0);
    box-shadow: 0 0 1px rgba(0, 0, 0, 0);
    position: relative;
    -webkit-transition-property: color;
    transition-property: color;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
  }
  .hvr-sweep-to-bottom:before {
    content: "";
    position: absolute;
    z-index: -1;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: #0b3558;
    -webkit-transform: scaleY(0);
    transform: scaleY(0);
    -webkit-transform-origin: 50% 0;
    transform-origin: 50% 0;
    -webkit-transition-property: transform;
    transition-property: transform;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -webkit-transition-timing-function: ease-out;
    transition-timing-function: ease-out;
  }
  .hvr-sweep-to-bottom:hover, .hvr-sweep-to-bottom:focus, .hvr-sweep-to-bottom:active {
    color: white;
  }
  .hvr-sweep-to-bottom:hover:before, .hvr-sweep-to-bottom:focus:before, .hvr-sweep-to-bottom:active:before {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
  }
  
  -->
* [Fontawesome](https://fontawesome.com/) gave me the icons used in the footer and contact page

<!-- All the icons I used
<i class="fa-brands fa-facebook"></i>
<i class="fa-brands fa-instagram"></i>
<i class="fa-solid fa-globe"></i>
<i class="fa-solid fa-phone">
-->

* [Google maps](https://www.google.com/maps) allowed me to embed a map on the contact page

<!-- 
<div id="map">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2422.0434551342764!2d-1.1670193238557287!3d52.62305882859497!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x487760b9c48fc3b7%3A0xb95c8137c0325640!2sThe%20BRITE%20Centre!5e0!3m2!1sen!2suk!4v1699194576379!5m2!1sen!2suk"
                width="90%" height="450" style="border:0;" allowfullscreen="" loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>
-->
* The gallery page was done following the [Code Institue](https://codeinstitute.net/) tutorials and tailored to my site

<!--
#gallery {
    clear: both;
    line-height: 0;
    column-count: 3;
    column-gap: 0;
    margin-left: 50px;
    margin-right: 50px;
}
-->

* [Bootstrap](https://getbootstrap.com/) code was used to create various tools including the navbar for mobile view, contact form and buttons

<!--

Mobile Navbar

    <nav class="navbar navbar-dark">
        <div class="container-fluid">
            <div class=logo-mobile><a href="index.html" aria-label="Go to the home page">Koryo Warriors
                    Taekwondo</a>
            </div>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="index.html"
                            aria-label="Go to the home page">Home</a></li>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="abouttkd.html"
                            aria-label="Learn about taekwondo to see if it interests you">About
                            Taekwondo</a></li>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="classes.html"
                            aria-label="Find out about classes to see if it's right for you">Classes</a></li>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="gallery.html"
                            aria-label="Go to the gallery to see pictures of us training">Gallery</a></li>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="news.html"
                            aria-label="Find out the latest news happening in our club">News</a></li>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="contact.html"
                            aria-label="Click here to contact us for more information">Contact
                            Us</a></li>
                    </li>
            </div>
        </div>
    </nav>

Button

    <a class="btn contact-button" href="contact.html" role="button" aria-label="Book a free session">Book a free
                Session</a>

Contact form

    <div class="col-12 col-sm-6 contact-form-container">
        <div id="contact-form">
            <form action="response.html" method="GET">
                <div class="mb-3">
                     <label for="name" class="form-label">Name:</label>
                    <input type="text" id="name" class="form-control" aria-describedby="name" required>
                </div>

                <div class="mb-3">
                    <label for="email" class="form-label">Email address:</label>
                    <input type="email" id="email" class="form-control" aria-describedby="email" required>
                </div>

                <div class="mb-3">
                    <label for="phone" class="form-label">Phone number:</label>
                    <input type="text" id="phone" class="form-control" aria-describedby="phone">
                </div>

                <div class="mb-3">
                    <label for="message" class="form-label">Message:</label>
                    <textarea class="form-control" placeholder="Leave a comment here" id="message"
                        aria-label="Write a message"></textarea>
                </div>

                 <input type="submit" value="Send!" class="contact-form-button" aria-label="Send">
                     
            </form>
        </div>
    </div>

    -->

* [W3C](https://www.w3.org/International/questions/qa-html-language-declarations#:~:text=When%20the%20page%20contains%20content,Usage%22.) was used to find out how to declare the korean language but I found the language code from [W3 Schools](https://www.w3schools.com/tags/ref_language_codes.asp)

<!--
<span lang="ko">(시작)</span>
-->

## Acknowledgements

* Code Institute - This website would not have been possible without their tutorials and walkthroughs. Tutors and slack community gave me help when I had difficulty
* Tamsin Davis - My taekwondo instructor who gave me lots of information on taekwondo
* Julie Konovalova - My mentor who has given me a lot of guidance throughout this project