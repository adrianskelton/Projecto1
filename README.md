# Mountain Magic Accomodation

This is the static website of Mountain Magic Container Homes available for rent on Airbnb. It is designed to be responsive on all devices and most of all functional so that users can be inticed to book via Airbnb or to contacct the host directly to ask further questions.

![fully responsive website example image 
](https://i.ibb.co/h9jmjQq/screenshot.png)

---

## CONTENTS

* [User Experience](#user-experience-ux).elementor-section.elementor-section-boxed > .elementor-container
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)

* [Features](#features)
  * [General Features on Each Page](#general-features-on-each-page)
  * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)

* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

---
## Target Audience

The target audience is all tourists travelling through the western cape of south africa that may pass through the wilderness area and are looking to stay over at the airbnb. The uniqueness of the accomodation and the amazing views are a big positive in the ease of selling point. The website is fairly basic with a good review from a past guest, beautiful images, a short desription of each of the accomodation options along with a side scrolling gallery, also there is a clearly visible "book now" image link underneath each gallery. Then there is a contact page with a map, contact form and contact details. An airbnb 

## User stories

The content will not change too much so the user experience goals for the first time visitor to returning visitor are essentially the same. These goals are primarily:

### As a tourist I would like to get a feel of the accomodation
Images throughout the site display a good feel of the sorrounding area as well as the accomodation page which shows the two different accomodation options. The review on the first page also gives a good insight on the kind of experiences that a guest has to entice potential guests to book.

### Make booking and communication easy
On the accomodation page there is are clearly visible book now buttons that link the user to airbnb pages to book the accomodation selected, these also have the correct aria labels so that visually impaired users know which accomodation option they are selecting to book. The contact page has more contact details available as well as a contact us form and a map showing directions to the accomodation.

### Make the above equally user friendly on all available devices
By using appropriate media queries to adjust the website to all screen sizes and using flexbox to adapt wider screeen content down to smaller sized content better suited to columns instead of row layout. I made a media query with a breakpoint for screen sizes below 1000px and tested this on chrome and it seems the best option for the user experience. 

## Design

### Colour Scheme

![alt text](assets/images/pallete.png)<br>

The choice of my color scheme was inspired by the nature sorounding this airbnb so it was earthy and green, but also using the colors in the logo of the website, namely the green and orangy red of the aloe plant in the logo. 

### Typography

I went for a google font Lato because it looked clean and modern and was easy to setup. Below is a screenshot of the font.

![alt text](assets/images/typography.png)<br>

### Imagery

The imagery chosen was to showcase the beauty of the area and to entice potential clients to want to book the accomodation. The images were compressed using website TinyPNG.com to maximise performance.

### Wireframes

### Home
![alt text](assets/images/wirehome.png)<br>

### Accomodation
![alt text](assets/images/wireaccomodation.png)<br>

### Contact
![alt text](assets/images/wirecontact.png)<br>

### Mobile view
![alt text](assets/images/wiremobile.png)<br>


I used Balsamiq to design my wireframes.


## Features


### General features on each page

### Navbar

I used a navbar from Bootstrap, below are two views of the desktop view and the responsive mobile view that transforms into a hamburger menu.

![alt text](https://i.ibb.co/kc2gVCx/nav1.png)<br>
Desktop version nav bar
<br><br><br>
![alt text](https://i.ibb.co/qjv7Jk0/navmobile.png)<br>
Mobile version nav bar

### Footer with social media icons

I added three social media icons for instagram, facebook and airbnb. They were sourced from font awesome and I changed the color to the same green color chosen in the color pallette previously mentioned.
<br><br>
<img src="assets/images/features/social.png" alt="pallete" border="0"></a>

## Features by page

### Landing page

The Landing page has a short intro of text describing the accomodation and how popular it is based on reviews and via publications. Then we have a review from a past customer with a portait image of her and a youtube video to the side displaying the containers and the area. I then chose 3 very colourful images that showcase the beauty of the area directly below the above content. I feel that the landing page is a great showcase for the containers and entices the user to click to the next pages where they will hopefully book or at least make an enquiry which is the end goal of the website.

![alt text](assets/images/features/landing.png)<br>

### Accomodation page

The accomodation page features the two options for accomodation with an overview of how many rooms and bathroooms available, a short writeup on the accomodation, a horizontal scrollable gallery as well as a book here link below which takes the user to airbnb where they can book. 

<img src="assets/images/features/accomodation.png" alt="pallete" border="0"></a>

### Contact page

The contact page features a google map that was embedded via google maps and a contact form, the thank you message in the popup box after submitting the form is a simple alert javascript function. The third column in the row is just the basic contact details of the bnb's.

<img src="assets/images/features/contact.png" alt="pallete" border="0"></a>

I then like to add a screenshot of each page of the site here, i use [amiresponsive](https://ui.dev/amiresponsive) which allows me to grab an image of the site as it would be displayed on mobile, tablet and desktop, this helps to show the responsiveness of the site.

### Future Implementations

I would like to more review which would be changed everytime the landing page is visited.

### Accessibility

Be an amazing developer and get used to thinking about accessibility in all of your projects!

This is the place to make a note of anything you have done with accessibility in mind. Some examples include:

Have you used icons and added aria-labels to enable screen readers to understand these?
Have you ensured your site meets the minimum contrast requirements?
Have you chosen fonts that are dyslexia/accessible friendly?

Code Institute have an amazing channel for all things accessibility (a11y-accessibility) I would highly recommend joining this channel as it contains a wealth of information about accessibility and what we can do as developers to be more inclusive.

## Technologies Used

**Github** - Used for storage of my site and for publishing online.<br>
**Codeanywhere** - The IDE used for editing my site and pushing changes.<br>
**Python** - Used python 3 via terminal to preview my site using a local http server.<br>
**HTML5** - The core of the site was built with HTML version 5.<br>
**CSS** - CSS was used to style the website and define fonts and layout.<br>
**Bootstrap** - Bootsrap was used to align items and create items such as the Navbar, accordion, carosel, flipcards, forms etc.<br>
**Google Maps** - Google maps embed from Google inc.<br>
**Youtube** - Videos embedded from Youtube.<br>
**Font Awesome** - Social Media icons from Font Awesome.<br>
**Google Chrome** - The website was built and tested in google Chrome.<br>
**TinyPNG Website** - Used to compress images so they load faster.<br>
**Codebeautify Website** - Used to clean up css and html code<br>
**Favicon Generator Website** - Converted PNG file that I made from the logo using photoshop and converted it into a favicon on website favicon.io<br>
**Imagebb** - Website used to host images for readme


### Languages Used

HTML, CSS, Javascript

### Frameworks, Libraries & Programs Used

**Bootstrap** - for the responsiveness of the website despite having to add a media query for the 1000px breakpoint so that the site looked better on mobile and tablets. I also used bootstrap code for the navbar.  <br>
**Github** - I used GitHub for the storage of my site and Gitpages to pubish my website
Make sure to include things like git, GitHub, the program used to make your wireframes, any programs used to compress your images, did you use a CSS framework like Bootstrap? If so add it here (add the version used).<br>
**Photoshop** - Used photoshop for some of my image resizing.

## Deployment & Local Development

👩🏻‍💻 View an example of a completed Deployment & Local Development section [here](https://github.com/kera-cudmore/TheQuizArms#Deployment)

### Deployment

I deployed everything my website onto gitpages.

### Local Development

To clone the repository:

1. Log into your account on github
2. Go to the repository of this project /adrianskelton/Projecto1/
3. Click on the code button, and copy your preferred clone link.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal, paste the link you copied in step 3 and press enter.


#### How to Fork

To fork the repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, adrianskelton/Projecto1
3. Click the Fork button in the top right corner.


#### How to Clone

To clone the repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, kera-cudmore/TheQuizArms
3. Click on the code button, select from the options to clone with HTTPS, SSH or GitHub CLI and copy the link shown thereafter.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.


## Testing

## Manual TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.



* [Index Page W3C HTML Validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Ffoundintranslationsodaci.herokuapp.com%2F) - Pass

### Lighthouse

I used Chrome's Lighthouse developer tool to check my sites performance, it was being slowed down by large images before compression but then faired well after compression. Below are the final results.

### Index

![alt text](assets/images/lightindex.jpg)<br>

### Accomodation
![alt text](assets/images/lightaccomm.jpg)<br>

### Contact
![alt text](assets/images/lightcontact.jpg)<br>

### Accessibility tester

I used this to check how my site was rated for its accessibility, this led me to add more aria-labels as well as changing alt descriptions for the book here links as I realised having two buttons that both said "book here" could be more confusing that two seperate descriptions that included which container you were booking.
  
Use this part of the README to link to your TESTING.md file - you can view the example TESTING.md file [here](milestone1-testing.md)

### Full Testing

Full testing was performed on the following devices:

* Laptop:
  * Macbook Pro 2021 14 inch screen
* Mobile Devices:
  * iPhone 13 pro.
  * iPhone 11 pro.
  * Phone X.

Each device tested the site using the following browsers:

* Google Chrome
* Safari
* Firefox

Additional testing was taken by friends and family on a variety of devices and screen sizes. A Big thank you to [Megan](https://github.com/Medusas71) for taking the time to thoroughly test the site for me.

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| `Navbar` |
|  |  |  |  |  |
| Mountain Magic Logo & Title | When clicked the user will be redirected to the home page. | Clicked Logo and title | Redirected to the home page. | Pass |
| Home Page Link | When clicked the user will be redirected to the home page.| Clicked link | Redirected to the home page. | Pass |
| Accomodation Link | When clicked the user will be redirected to the accomodation page. | Clicked link | Redirected to the accomodation page. | Pass |
| Contact Link | When clicked the user will be redirected to the Contact page. | Clicked link | Redirected to the contact page | Pass |
| --- | --- | --- | --- | --- |
| `Footer` |
|  |  |  |  |  |
| Social Icons | When clicked the user will be redirected to the appropriate social media pages. | Clicked icon | Redirected to the social media page. | Pass |
| --- | --- | --- | --- | --- |
| `Home Page` |
|   |   |   |   |
| Register link in the blurb | When clicked the user will be redirected to the register page. | Clicked link  | Redirected to the register page | Pass |
| Search link in the blurb | When clicked the user will be redirected to the search page. | Clicked link | Redirected to search page | Pass |
| --- | --- | --- | --- | --- |
| `Accomodation Page` |
| Username input - empty | This is a required field so the form should not submit if empty | Tried to submit the form with this field empty | Tooltip tells me this field is required | Pass |
| Password input empty | This is a required field so the form should not submit if empty | Tried to submit the form with this field empty | tooltip tells me this field is required |  Pass |
| log in button | Saves the user to session and redirects to the profile page. Flash message shown welcoming the user | Submitted form | Redirected to the profile page and flash message shown | Pass |
| Incorrect username or password used | A flash message should display saying username/password incorrect - this is defensive programming - not letting user know which input is incorrect | Incorrect username/password entered | Message flashes to let the user know they have entered an incorrect username/password | Pass |
| Link to register page |  This should redirect the user to the register page | Clicked link | Redirected to the register page | Pass |

| `Register Page` |
| | | | | | |
| Username input | The username should be 5 characters minimum | Entered username less than 5 characters long | tooltip lets the user know they have not entered enough characters | Pass |
| Username input - empty | The username is a required field, so should not submit with no value | Tried to submit form with no value entered | Tooltip lets user know this value is required | Pass |
| Username input | If username is in use, message should flash to user | entered an in use username | Message flashed to say username already in use | Pass|
| Email input | The email input should include an email address  | Entered plain text | Tooltip tells user to use an email address here | Pass |
| Email input - empty | The email is a required field, so should not submit with no value | Tried to submit form with no value entered | Tooltip lets user know this value is required | Pass |
| Password input | This field should be at least 5 characters long | Entered password less than 5 characters long | Tooltip tells user the password should be at least 5 characters long | Pass |
| Password input - empty | The password is a required field, so should not submit with no value | Tried to submit form with no value entered | Tooltip lets user know this value is required | Pass |
| Register button | Should redirect user to the log in page and a registration successful message flashed | Created new user and submitted form | Redirected to the log in page and message flashed | Pass |
| `Search Page` |
|   |   |   |   |  |
| Search feature | A search is performed when the user enters a search term | Searched for rabbits | The search returns book results | Pass |
| Search feature. - Error | If there is an error with the search, a flash message is displayed to let the user know there was a problem and directs them to try again. | Searched for bulldogs | The search doesn't return a result (please see known bugs No 2), and a flash message is displayed to the user | Pass |
| Shelve this book button on search result book (user signed in) | When the user clicks the shelve this book button they should be redirected to the add review page | Clicked button while signed in | Redirected to the add review page and book information pre-populated | Pass |
| Shelve this book button on search result book (user not signed in) | When the user clicks the shelve this book button they should be flashed a message to let them know they need to be logged in to shelve a book and be redirected to the log in page | Clicked button while not signed in | Redirected to the log in page and flash message displayed | Pass |
| `Bookshelves Page` |
|   |   |   |   |  |
| Add a bookshelf button | When the user clicks this button they should be taken to the add a bookshelf page | Clicked button | Redirected to the add a bookshelf page | Pass |
| Bookshelf accordion | When the user selects a bookshelf, the accordion opens to display the edit and delete bookshelf buttons | Clicked shelf | Accordion opened to display edit and delete buttons | Pass |
| Edit bookshelf button on bookshelf accordion | The user should be taken to the edit bookshelf page with the selected bookshelf pre-populated in the input | Clicked button | Taken to the edit bookshelf page. Input pre-populated with the current bookshelf name | Pass |
| Delete button on bookshelf accordion | When the user clicks the delete button a modal should pop up asking the user to confirm they wish to delete the bookshelf and that by deleting the bookshelf all books associated with the shelf will be deleted too | Clicked button | Modal popped up and displayed the confirm deletion message | Pass |
| Delete Button on Deletion modal| When the user clicks the delete button the bookshelf should be deleted along with any books that were associated with the shelf. A flash message will confirm deletion and the user is redirected to the bookshelves page | Clicked button | Bookshelf deleted together with associated books and a flash message displayed success. Redirected to the bookshelves page | Pass |
| Cancel button on deletion modal | When the user clicks the cancel button the modal should close | Clicked button | Modal closed | Pass |
| `Books Page` |
|   |   |   |   |  |
| Accordion button | Open/close the accordion | Click button | Accordion opens and closes | Pass |
| Edit button on book | When the edit button is clicked the user should be taken to the edit review page with the inputs pre-populated with the values stored in the database for that book | Clicked button | Redirected to the edit review page. Books details filled in with previously saved information | Pass |
| Delete button on book | When the user clicks this button a modal should pop up asking the user to confirm they wish to delete this book | Clicked button | Modal popped up to confirm if I wanted to delete the book | Pass |
| Delete button on modal | When clicked the book should be deleted | Clicked button | Book Deleted from books page | Pass |
| Cancel button on modal | When clicked the modal should close | Clicked button | Modal closed | Pass |
| `Add Bookshelf Page` |
| Bookshelf input | Should prompt the user to enter a shelf name if left blank | Left blank and clicked add bookshelf button | Tooltip tells you this field needs to be filled in | Pass |
| Add Bookshelf button | Saves the new bookshelf to the database, redirects the user to the bookshelves page and flashes message to let the user know successful | Clicked button | Bookshelf saved to the database, redirected to the bookshelves page and flash message to save bookshelf created successfully | Pass |
| `Edit Bookshelf Page` |
| Input | This should be pre-populated with the bookshelf selected | Checked input against the bookshelf selected |Input pre-populated with the bookshelf selected | Pass |
| Input - no value entered | The form requires this field be filled in before submission | Left input blank | Tooltip lets me know this field is required | Pass |
| Edit bookshelf button | When clicked the updated shelf name should be saved to the database, the user redirected to the bookshelves page and a message flashed to let them know updated successfully | clicked button | Updated bookshelf name added to the database, redirected to bookshelf page and flash message shows update has been successful | Pass |
| `Add Review Page` |
|   |   |   |   |   |
| Title input | This is a required field so should ask for a value to be entered if empty. This field should be pre-populated with the book information selected in the search | Input was pre-populated. Cleared the input | Tooltip told me it is a required field | Pass |
| Author input | This is a required field so should ask for a value to be entered if empty. This field should be pre-populated with the book information selected in the search | Input was pre-populated. Cleared the input | Tooltip told me it is a required field | Pass |
| Bookshelf dropdown | This should be populated with all the bookshelves associated with the user | Checked to see if all my created bookshelves were displayed | Only my bookshelves are displayed | Pass |
| Star Ratings | These should be able to be selected to choose your rating | clicked random ratings | The rating was saved to the database | Pass |
| Review Field | This is an optional field. Any information entered should be saved to the database | Text entered | Text saved to the database | Pass |
| Notes Field | This is an optional field. Any information entered should be saved to the database | Text entered | Text saved to the database | Pass |
| Add Review Button | This should add the review to the database and redirect the user to the books page and flash a message to let the user know the book was saved successfully | Clicked button | Review saved to database and redirected to books page, message flashed to let me know book saved successfully | Pass |
| `Edit Review Page` |
| Title input | This is a required field so should ask for a value to be entered if empty. This field should be pre-populated with the book information saved to the database | Input was pre-populated. Cleared the input | Tooltip told me it is a required field | Pass |
| Author input | This is a required field so should ask for a value to be entered if empty. This field should be pre-populated with the book information saved to the database | Input was pre-populated. Cleared the input | Tooltip told me it is a required field | Pass |
| Bookshelf dropdown | This should be populated with all the bookshelves associated with the user | Checked to see if all my created bookshelves were displayed | Only my bookshelves are displayed | Pass |
| Star Ratings | These should be able to be selected to choose your rating. Rating saved to the database should be displayed | Rating saved to the database displayed. Clicked random rating to change the rating | The rating was saved to the database | Pass |
| Review Field | This is an optional field. Previously saved review should display here. Any information entered should be saved to the database | Saved review text displayed. Text Changed | Text saved to the database | Pass |
| Notes Field | This is an optional field. Previous saved notes should display here. Any information entered should be saved to the database | Notes previously saved to the database displayed, text changed | Text saved to the database | Pass |
| Edit Review Button | This should add the updated review to the database and redirect the user to the books page and flash a message to let the user know the book was saved successfully | Clicked button | Review saved to database and redirected to books page, message flashed to let me know book saved successfully | Pass |
| `Error Page` |
|   |   |   |   |   |
| Home page link | Redirects the user to the home page | Clicked link | Redirected to home page | Pass |

 - - -


## Credits


### Code Used

The navbar I used was from bootstrap.  (https://getbootstrap.com/docs/4.0/components/navbar/)
To make the youtube video responsive I found this css code clip (https://yoast.com/how-to-make-youtube-videos-responsive/)
Pop-up Modal used from (https://codepen.io/imprakash/pen/GgNMXO) modified to suit my websites color scheme and style
Photogallery used on accomodation page (https://codepen.io/maxvoltar/pen/eYOPdMG)
Tip used to not target all ul and li tags but only the above photogallery (https://stackoverflow.com/questions/49995250/css-global-change-to-all-ul-li-except-specific-id-or-class)

### Content

I wrote all of the content for the website, though I did get some information from mountain magic's website such as how many rooms and bathrooms of each container unit.

###  Media

As my brother owns the container homes this was another reason to use this as my project as it made aquiring the images and video content easy without having to ask for permission from somebody I did not know. Images that were not from my brother was the portrait image for the reviewer on the home page which I get from royalty free website pexels.com (https://www.pexels.com/photo/woman-wearing-white-shirt-with-white-flower-on-her-ear-3586798/)
The other 3 images above the footer on the home page are my own.

  
###  Acknowledgments

I would like to thank my mentor Narender as well as all the users on slack for all their opinions and code reviews. 