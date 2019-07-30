# Paramore

This is a static website, designed to provide adequate information about the 2004 band, Paramore. This is a single page website with 5 seperate sections; Home, About, Services, Media and Contact (contact form for potential customers who will need to provide a name, email and a description of their event, in order to get a Service quotation).

## UX

My goal in the design was to make it as easy as possible to access information on the site while striving for a minimalist design. I went with the red color because it attracts attention, and is associated with love (for music).

The page is designed for new, old and prospective fans of Paramore. In the "About" section, I gave an overview of who Paramore are, and pointed out a few of their achievements in the music industry, for the users that aren't familiar with the band. In the "Services" section, a list of genres the Band's music is categorised in, to provide an insight for new and potential fans/customers. A button linked to a contact form is found in this section too, for easy access to the "Contact section". In the "Media" section, 2 embedded videos and 2 audio files are provided for all users to have a feel of the band's best selling hits. In the "Contact" section, a form containing "Name", "Email" and "Event description" fields (all required). This is where potential customers will request a service quotation from the band, explaining briefing the type of event they have planned. In the Footer, links(Icons) to music sites like Spotify and Youtube are provided for users that are looking for a wider library of the band's music.

## Features

In this project the Navigation bar is fixed at the top, and each section can be accessed using the links provided in the Nav bar, which are linked to their corresponding name. I used the scroll-behavior property in CSS to achieve a smooth scroll, although this may be limited to certain browsers. Safari in particular does not respond to this function, so the page hastily scrolls to the section selected in the Nav bar.

Below the Navigation bar are 3 images constantly sliding over each other. I used the Carousel plugin in Bootstrap to achieve this. Left (previous) and Right (next) arrows are provided on either side to navigate through the images, as well as, 3 dots to select each image.
 
The images in the "About" and "Services" sections have a hover effect styled over them. The images are transparent, blended in well with the background, when the mouse cursor is away from them. When hovered over the opacity increases, therefore, brightening the images. 

### Features Left to Implement

In the future I'd like to add another section, that will have information on upcoming events, for example where the band is performing next, where to get tickets (link this to https://ticketmaster.ie) etc. 

## Technologies Used

1. HTML5
2. CSS3
3. Bootstrap (https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js)

## Testing

The navigation bar was satisfactory, it responded well on every device I manually tested it on. On a mobile device it displays as a collapse menu, triggered when touched. It remains collapsed unless touched. Works fine on the iphone (5s, 7 and X), Samsung S7, Oneplus (3t and 6t) and on a Sony Xperia Z3. Overall all the features on the navigation bar work fine on most of the windows machines I tested it on. The smooth scroll feature, however, does not work on the Safari browser on an IOS machine. I may need to implement some JavaScript in the future to achieve compatibility. 

The Carousel works fine on all devices listed above, although, I had to add some media queries to fix the margin-top of the images, because they were being pushed up towards the navigation bar.

The button in the "Services" section should take you to the contact form. I tested this on all the devices listed above, and it's very functional. 

The 2 embedded Videos work fine on all the listed devices above, the audio files, however, seemed to not work on the Iphone X (I wasn't able to resolve this issue, still not sure why it never worked). 

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit.

## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://chizkay.github.io/UCFD-Milestone-Project/ into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

## Credits

### Content
- The Carousel Plugin was taken from [here](https://www.w3schools.com/bootstrap/bootstrap_carousel.asp)
- The "About" section was taken from [here](https://en.wikipedia.org/wiki/Paramore)
- The "Service" section was written by me.

### Media

- I created the logo  [here](https://www.canva.com/)
- The photos used in this site were obtained from a "Paramore image google search"
- The background image was obtained from a "Background image google search"
- The videos were obtained from Youtube.
- The audio files were taken from my local drive (I used an MP3 video converter to convert them from an mp4).

### Acknowledgements

- I received inspiration for this project from The WhiskeyDrop Landing page(https://github.com/Code-Institute-Solutions/BootstrappingYourNextBigIdea-BS4/)
