# Canary - Milestone Project 1

This is a website for my band, Canary. Since I have moved to Sweden and Canary were based in Australia, we are no longer playing together. However, I thought it would be fun to frame this milestone project in a more personal context. Since we are not currently performing, the website is based in an alternate universe where Canary are still an active band.


## Demo
You can see the website live on [GitGub Pages](https://cronugs.github.io/canarythirddraft/index.html).


## UX
I went through several iterations in the design process, starting with what I thought was an over-the-top abstract design with bold colours. As I worked, I found myself eliminating elements one by one and after some time and a couple of restarts, came across a design I liked.

You can find the various "drafts" for this assignment in the following repositories;

- Draft 1 - [Repository](https://github.com/cronugs/canary-site) deployed on [GitHub Pages](https://cronugs.github.io/canary-site/)
- Draft 2 - [Repository](https://github.com/cronugs/canary2) deployed on [GitHub Pages](https://cronugs.github.io/canary2/)
- Draft 3 - [Repository](https://github.com/cronugs/canary-processwork) deployed on [GitHub Pages](https://cronugs.github.io/canary-processwork/)

Most importantly, I wanted the site to be simple. Too many visual elements are distracting and take the users attention away from the information that is being presented.

Social media links are front and center on the landing page (twitter links to my own twitter profile since Canary never had one) and examples of the bands work are easily found in the media section. News about upcoming shows, tour dates and upcoming releases are in the news page. Booking the band for an event or making other inquiries is easily accomplished with the contact form.

## Technologies
1. HTML
2. CSS
3. Bootstrap (3.3.7)


## Features
The Canary website features a responsive navmenu. I had originally coded the nav myself, but while I was researching how to make it respond to changes in screen size, I came across a great example using bootstrap on the w3school.com site [here](https://www.w3schools.com/bootstrap/bootstrap_navbar.asp). I restyled it to match the navbar I already had in place and added the appropriate links for js and jquery in my html to enable it to function correctly.

The media page features both soundcloud playlists and youtube videos to showcase the bands work. The youtube videos are hidden in from view in mobile screen sizes

The form on the contact page was originally an example contact form from codepen.io. I modified it quite heavily to fit the style of the site and to only include functions that I needed. The original can be found [here.](https://codepen.io/colorlib/pen/KVoZyv)

The background image of the crows sitting atop the snowdrift has a gradient applied to it. I found how to do this in a stackoverflow answer [here.](https://stackoverflow.com/questions/17134929/overlay-a-background-image-with-an-rgba-background-color)


### Features Left to Implement
In the future I would like to include a youtube playlist adapted for mobile screen sizes as well as an area for photos from live performances or perhaps a social media stream for people to post pics taken at our lives shows.

A scrapbook section with snippets of hand written lyrics taken from notebooks while songs were in development and other art and scribblings.


## Testing
I have done thorough testing using the W3C validators for both HTML and CSS. I have also done fairly extensive testing using [responsinator](www.responsinator.com), to make sure my responsive design worked across screen sizes and orientations.


## Deployment
The site is currently deployed on Github pages [here.](https://cronugs.github.io/canarythirddraft/index.html)

To run the code locally, clone this repository and point your browser to the index.html file


## Credits

### Content and Media
All written content belongs to me. All photos featuring the band belong to Canary. Credit for all media go to the band Canary who wrote and performed all the music on the site. The main background image of the crows in the snowdrift was sourced [here](https://i.pinimg.com/originals/31/f5/c6/31f5c6212a43b5c8abee71a8858e6a78.jpg)

### Acknowledgements
The collapsible Navbar was found at w3schools.com [here](https://www.w3schools.com/bootstrap/bootstrap_navbar.asp).

The contact form was found on codepen.io and is credited to colorlib. it can be found [here.](https://codepen.io/colorlib/pen/KVoZyv)

The code to apply a gradient to an image was found [here.](https://stackoverflow.com/questions/17134929/overlay-a-background-image-with-an-rgba-background-color) Credit belongs to Wladimir Palant whos answer provided the code.
