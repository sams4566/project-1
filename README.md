# Winston Churchill Biography

The Winston Churchill Biography is a site that has arisen to inform users about the life and achievements of Winston Churchill. Users of the site will be able to find out information about Winston Churchill through a number of different formats such as videos, timelines, images and short facts to help them digest and remember information fast and easily. 

![Am I Responsive Mockup](https://github.com/sams4566/project-1/blob/main/media/winston1.jpg)

## Features
- __Navigation__

  - Featured at the top of the page are four links that assist users with smooth navigation. There are two links to the home page (one in the top left ‘WINSTON CHURCHILL BIOGRAPHY’ and one in the top right ‘Home’), one link to the ‘Early Life’ page and one link to the ‘Timeline’ page.
  - The navigation bar is the same on all three pages which makes the site streamlined and is situated at the top of the page similar to most websites.
  - The contrasting colours of white, grey and black helps establish that the page is set in the early 1900’s due to cameras being in black and white.

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
  - The video allows users to watch a 4 minute video that sums up Winston Churchill's notable achievements. 
  - The length of the video was kept short to keep in line with the home page allowing users to get key information quickly. 

![Video section](https://github.com/sams4566/project-1/blob/main/media/winston5.jpg)

- __The Footer__
  - The footer contains social media links so the user can keep up to date with additions to the site and find relevant pictures and quotes that could be of interest.

![Footer](https://github.com/sams4566/project-1/blob/main/media/winston6.jpg)

- __Early Life__
  - The early life section gives the user more in depth information about Winston Churchill’s early life and accompanies the information with a picture of him as a child.

![Early Life](https://github.com/sams4566/project-1/blob/main/media/winston6.jpg)

- __Timeline__
  - The timeline section allows the user to piece together the different positions Winston Churchill had throughout his career. 
  - The image of St Paul’s Cathedral during the Blitz keeps the page in style with the war time theme.

![Timeline](https://github.com/sams4566/project-1/blob/main/media/winston7.jpg)

- __Future features__
  - Future features would include more pages about each time period of Winston Churchill’s life. These pages can be easily added in the same format as the ‘Early Life’ page by creating a new tab.

## Testing
  - I have tested that all the links on the site work and are responsive alongside all the images loading correctly and the video playing when clicked.
  - I tested this page on different browsers such as Google Chrome, Internet Explorer and Firefox. 
  - This webpage works on all screen sizes at any height between a width of 320px to 1600px. Between these widths the site is easily readable on all devices. These widths were tested using the developer tools in Google Chrome, Internet Explorer and Mozilla Firefox to ensure the page will work on all browsers.

### Validator Testing
- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fsams4566.github.io%2Fwinston-churchill-biography%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fsams4566.github.io%2Fwinston-churchill-biography%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Accessibility
  - The web page was tested through Lighthouse in dev tools and confirmed a high level of accessibility

![Validator](https://github.com/sams4566/project-1/blob/main/media/winston8.jpg)

### Bugs
#### Solved Bugs 

- The video unfortunately wouldn’t play using the below code: 


  <video src="https://www.youtube.com/watch?v=cFUSLK2z6qI&t=6s" controls>
                <p></p>
                <a href="https://www.youtube.com/watch?v=cFUSLK2z6qI&t=6s">Link to the video.</a>
            </video>

  so after trying a number of different methods using an iframe with the below code allowed the video to play at   all screen sizes:

  <iframe width="600" height="400" src="https://www.youtube.com/embed/cFUSLK2z6qI" id="video"></iframe>

  The above code was taken from - https://www.w3schools.com/html/html_youtube.asp 
- The background color #8b8888d5 for the header and footer didn’t appear on Internet explorer. After changing the color a few times the color rgb(169,169,169) worked on all devices.

#### Unfixed Bugs
- No unfixed bugs

## Deployment
The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the repository for winston-churchill-biography and then click on the setting tab.
- Click on the pages tab from the list of options on the left hand side of the page.
- Select ‘main’ from the button displaying ‘None’ under the ‘Source’ sub-section.
- Once saved the page will take a couple of seconds to be uploaded onto the web. The link to the page will be provided above the ‘Source’ sub-section when refreshed
- The live link can be found here - https://sams4566.github.io/winston-churchill-biography/ 

## Credits
### Content
- The facts and information on the home page were from https://en.wikipedia.org/wiki/Winston_Churchill and https://www.biography.com/political-figure/winston-churchill 
- The paragraphs on the ‘Early Life’ page were taken from - https://www.biography.com/political-figure/winston-churchill 
- The timeline information was taken from - https://www.chu.cam.ac.uk/archives/collections/churchill-papers/sir-winston-churchill-chronology/
- The code for the social media links was used from the Code Institute Love Running Project
- The icons throughout the site were taken from [Font Awesome](https://fontawesome.com/)

### Media
- The portrait photo was from - https://en.wikipedia.org/wiki/Winston_Churchill
- The video was from - https://www.youtube.com/watch?v=cFUSLK2z6qI&t=6s 
 -The image of Winston Churchill as a child on the ‘Early Life’ page was taken from - https://www.biography.com/political-figure/winston-churchill 
- The background photo for the timeline was from - https://en.wikipedia.org/wiki/St_Paul%27s_Survives#/media/File:Air_Raid_Damage_in_Britain_during_the_Second_World_War_HU36220.jpg 
- The way to embed the video link in an iframe was found at - https://www.w3schools.com/html/html_youtube.asp
- How to change the width and height of iframes at different screen lengths was found on the following website - https://stackoverflow.com/questions/49419074/how-can-i-change-the-height-of-an-iframe-for-different-screen-sizes
