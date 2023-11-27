# TESTING

## Compatibility and responsiveness

## Validator testing

### HTML

Home page

About Taekwondo page

Classes page

Gallery page

News page

Contact Us page

Response page

### CSS

## Lighthouse report

Home page

About Taekwondo page

Classes page

Gallery page

News page

Contact Us page

Response page

## Bugs

1)	Creating a responsive website
*	When using float properties to align the divs, they would not move beneath each other when the window was resized smaller and the content would instead overlap. 
*	To solve this I used bootstrap’s grid system on most pages

2)	Creating a sticky navbar
*	I wanted to have the navbar going across the hero image sitting a few cms from the bottom. When adding code to make it sticky, it would either move from its original intended position or only be sticky and visible for as long as you could see the hero image.
*	I realised the problem occured when the navbar is placed inside the header. I am aware that the navbar is conventionally placed inside the header but for this purpose I had to bring it underneath the header.
*	When I tried to position the navbar above the hero image it wouldn’t work so I decided to discard that idea and just keep it sticky.

<!--
.nav-main {
    position: sticky;
    position: -webkit-sticky;
    top: 0;
    z-index: 1;
    text-align: center;
    align-items: center;
    background-color: #4B4453;
    height: auto;
    width: 100%;
}
-->

3)	Creating mobile menu
*	Because my navbar is not positioned at the top I had to create a separate navbar for mobile view.
*	I tried to add the toggle button into the existing top bar but it messed up the layout
*	Again I found out it had to be outside of other elements
*	I then used media queries to toggle the visibility of both navbars and the top bar

<!--
HTML

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
                            <a class="nav-link active" aria-current="page" href="index.html"
                                aria-label="Go to the home page">Home</a></li>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="abouttkd.html" aria-label="Learn about taekwondo">About
                                Taekwondo</a></li>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" aria-current="page" href="classes.html"
                                aria-label="Find out about classes">Classes</a></li>
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
                                aria-label="Click here to Contact us">Contact
                                Us</a></li>
                        </li>
                </div>
            </div>
        </nav>


CSS


@media screen and (max-width: 900px) {     
    
    .top-bar {
        display: none;
    }
    
    .nav-main {
        display: none;
    }
}

@media only screen and (min-width: 900px) {
    
    .navbar {
        display: none;
    }
}

-->

