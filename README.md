# Winston Churchill Biography

The Winston Churchill Biography is a site that has arisen to inform users about the life and achievements of Winston Churchill. Users of the site will be able to find out information about Winston Churchill through a number of different formats such as videos, timelines, images and short facts to help them digest and remember information fast and easily. 

![Am I Responsive Mockup](https://github.com/sams4566/project-1/blob/main/media/winston1.jpg)

## Features
- __Navigation__

  - Featured at the top of the page are three links that assist users with smooth navigation. There are two links to the home page (one in the top left ‘WINSTON CHURCHILL    BIOGRAPHY’ and one in the top right ‘Home’) and one link to the ‘Timeline’ section.
  - The navigation bar is the same on both pages which makes the site streamlined and is situated at the top of the page similar to most websites. 
  - The contracting colours of white, grey and black helps establish that the page is set in the early 1900’s due to cameras being in black and white. 

![Nav bar](https://github.com/sams4566/project-1/blob/main/media/winston2.jpg)

- __Portrait and supporting paragraph__

  - The portrait is used to help users quickly establish that the page is regarding Winston Churchill as they are likely to have seen a picture of him before. The image is the first thing users see when they enter the site due to the animation that zooms the image towards the user. 
  - The supporting paragraph gives a brief summary about who Winston Churchill is which could be all the user needs to gain a quick understanding. 

![Portrait and supporting paragraph](https://github.com/sams4566/project-1/blob/main/media/winston3.jpg)

- __Interesting Facts Section__
  - The interesting facts section helps the user digest short and snappy facts that may be of interest to accompany the paragraph above. 
  - They all include an icon that helps highlight their respective facts.
  - The number of facts was limited to five so that the user can quickly read them before going onto other sections of the page.

![Interesting Facts Section](https://github.com/sams4566/project-1/blob/main/media/winston4.jpg)

- __Video Section__
  - The video section is to allow users to watch a short 4 minute video that sums up Winston Churchill's notable achievements. 
  - The video is short so that if users would like a quick summary of Winston Churchill they can get it from the front page. 

![Video section](https://github.com/sams4566/project-1/blob/main/media/winston5.jpg)

- __The Footer__
  - The footer contains social media links so the user can keep up to date with additions to the site and find relevant pictures that could be of interest.

![Footer](https://github.com/sams4566/project-1/blob/main/media/winston6.jpg)

- __Timeline__
  - The timeline section allows the user to piece together the different positions Winston Churchill had throughout his career. 
  - The background image of St Paul’s Cathedral during the Blitz keeps the page in style with the war time theme.

![Timeline](https://github.com/sams4566/project-1/blob/main/media/winston7.jpg)

- __Future features__
  - Future features would include in-depth information about each time period of Winston Churchill’s life. The site at the moment is very much the key facts to help users build up a quick picture of Winston Churchill’s life. The site gives a basic structure to allow adding more pages easily.

### Testing
  - I have tested that all the links on the site work and are responsive alongside all the images loading correctly and the video playing when clicked.
  - I tested this page on different browsers such as Google Chrome, Internet Explorer and Safari. 
This webpage works on all screen sizes from 320px upwards and is easily readable on all devices. This was tested using the dev tools device toolbar.

### Validator Testing
- HTML
  - No errors were returned when passing through the official W3C validator
- CSS
  - No errors were found when passing through the official (Jigsaw) validator
- Accessibility
  - The web page was tested through Lighthouse in dev tools and confirmed a high level of accessibility

![Validator](https://github.com/sams4566/project-1/blob/main/media/winston8.jpg)

### Bugs
- Solved Bugs 
The video unfortunately wouldn’t play using the below code:

<video src="https://www.youtube.com/watch?v=cFUSLK2z6qI&t=6s" controls>
                <p></p>
                <a href="https://www.youtube.com/watch?v=cFUSLK2z6qI&t=6s">Link to the video.</a>
            </video>

so after trying a number of different methods using an iframe with the below code allowed the video to play at all screen sizes:

<iframe width="600" height="400" src="https://www.youtube.com/embed/cFUSLK2z6qI" id="video">
</iframe>

The above code was taken from - https://www.w3schools.com/html/html_youtube.asp 

- Unfixed Bugs
No unfixed bugs

### Deployment
The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the repository for project-1 and then click on the setting tab.
- Click on the pages tab from the list of options on the left hand side of the page.
- Select ‘main’ from the button displaying ‘None’ under the ‘Source’ sub-section.
- Once saved the page will take a couple of seconds to be uploaded onto the web. The link to the page will be provided above the ‘Source’ sub-section when refreshed
- The live link can be found here - https://sams4566.github.io/project-1/

### Credits
- Content
  - The facts and information on the home page were from both https://en.wikipedia.org/wiki/Winston_Churchill and https://www.biography.com/political-figure/winston-churchill 
  - The timeline information was taken from - https://www.chu.cam.ac.uk/archives/collections/churchill-papers/sir-winston-churchill-chronology/
  - The code for the social media links was taken from the Code Institute Love Running Project
  - The icons throughout the site were taken from Font Awesome

- Media
  - The portrait photo was from https://en.wikipedia.org/wiki/Winston_Churchill
  - The video was from https://www.youtube.com/watch?v=cFUSLK2z6qI&t=6s 
  - The background photo for the timeline was from https://en.wikipedia.org/wiki/St_Paul%27s_Survives#/media/File:Air_Raid_Damage_in_Britain_during_the_Second_World_War_HU36220.jpg 
  - The way to embed the video link in an iframe was found at - https://www.w3schools.com/html/html_youtube.asp
  - How to change the width and height of iframes at different screen lengths was found on the following website - https://stackoverflow.com/questions/49419074/how-can-i-change-the-height-of-an-iframe-for-different-screen-sizes 
