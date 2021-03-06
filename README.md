# The Worlds Greatest Memory Game

![mockup](https://github.com/fergusthompson/Worlds-most-amazing-memory-game/blob/master/wireframes/webpage%20mockup.png?raw=true)

The goal of this project is to build a visually appealing memory game in a comic book style using the marvel universe as the theme.I want it to 
really stand out and look impressive for the user. Ease of understanding will be key so that the user can jump straight in with no issues.
As its quite a simple layout it will need to be clean with complementing colours.  I want something the user will enjoy and come back to play again.


## Contents
---
 - [UX (User experience)](#ux--user-experience-)
  * [User Goals:](#user-goals-)
  * [User Stories:](#user-stories-)
    + [Gary](#gary)
    + [Steve](#steve)
    + [Graham](#graham)
    + [Colin](#colin)
  * [Site Owner Goals:](#site-owner-goals-)
- [User Requirements and Expectations](#user-requirements-and-expectations)
  * [Requirements:](#requirements-)
  * [Expectations:](#expectations-)
- [Design Choices](#design-choices)
  * [Fonts:](#fonts-)
  * [Colours:](#colours-)
  * [Styling:](#styling-)
- [Wireframes:](#wireframes-)
- [Features developed:](#features-developed-)
- [Features To be Developed](#features-to-be-developed)
- [Technologies Used:](#technologies-used-)
  * [Languages;](#languages-)
  * [Tools and Libraries:](#tools-and-libraries-)
- [Testing:](#testing-)
  * [Testing stories](#testing-stories)
- [User testing](#user-testing)
    + [Gary](#gary-1)
    + [Steve](#steve-1)
    + [Graham](#graham-1)
    + [Colin](#colin-1)
- [Overall:](#overall-)
  * [Responsiveness -](#responsiveness--)
  * [Design -](#design--)
- [Features:](#features-)
  * [Click counter -](#click-counter--)
  * [flip cards with matching pictures -](#flip-cards-with-matching-pictures--)
- [Bugs](#bugs)
  * [Bugs during development](#bugs-during-development)
  * [known Bugs](#known-bugs)
- [Deployment:](#deployment-)
- [Closing Notes:](#closing-notes-)
- [Credits:](#credits-)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>



## UX (User experience)

### User Goals:
* A website that offers an easily understandable memory game.
* Attractive call to action to encourage high level of engagement.
* good visual interaction.
* Interact with the website on desktop, tablet and mobile.
    

### User Stories:

* as a user i expect the game to work when i play.
* as a user i expect the cards to flip when i click them.
* as a user is expect to be able to see it porperly when im playing.

#### Gary
"As a user i want to be able to understand the game very quickly once i start playing."

#### Steve

"Too may games out there are hard to get to grips with and as a user i'm looking for something easy and fun when i play the game"

#### Graham

"as a user when i go online to play a game i dont want to have advertising shoved down my throat for ages before i get to play a game
so i expect to be able to play quickly once i load up the page"

#### Colin

"as a user I want something i can pck up quickly on my breaks at work therefore i expect 
something that doesnt take a long time to learn once i start playing."

### Site Owner Goals:

* Offer a fun game for people to play
* Make an appealing looking site for players.
* Keep it simple and addictive.


## User Requirements and Expectations

### Requirements:
* game must be easy to understand.
* Content displayed in visually appealing manor.
* Information on how to play where necessary.
* Must be fun to play.

### Expectations:

* To be visually appealing.
* To be able to understand the game easily.
* If they dont understand they will need information on how to play.
* Fun!

## Design Choices 
The theme for this game is going to be comic book Marvel characters. 
The colour scheme will need to be bright and appealing and try to 
co inside with the imagery of the marvel universe characters used on each of the 
memory game tiles. 

### Fonts:
I chose to use the font Anton as it was the closest i could find to a comic book style font as the actual marvel font is 
copywritten. but i think it fits in well with the style.

### Colours:
Using knowledge from prior research of the marvel comic books the colours will
need to be bright and eye cacthing with a darker background and I will try to match the colour scheme to
the imagery of the marvel comic book characters used.

* background-color: #061435 dark blue 
* Tile colour: #ed1d24 red
* lettering colour: #fff white

These are the colours I'll be using:

![color pallete](https://github.com/fergusthompson/Worlds-most-amazing-memory-game/blob/master/wireframes/colours%20for%20marvel%20game.png?raw=true)


### Styling:
I choose a comic book style font and used the colours from the marvel logo in the 
theme for the rest of the site.


## Wireframes:

All the wireframes can be found <a href="https://github.com/fergusthompson/Worlds-most-amazing-memory-game/tree/master/wireframes">here</a>. for desktop tablet and mobile.


## Features developed:
* click counter
* Flip Cards with matching pictures

## Features To be Developed
* I would have liked to add a timer but didnt have time.
* I would have liked to add difficulty settings but also didnt have the time.

These features were on my wireframes but where then left out as development went on. I chose to put the click counter where the timer would have been to keep in line with the same kind of layout.

## Technologies Used:


### Languages;
* HTML
* CSS
* JavaScript


### Tools and Libraries:
* <a href="https://github.com/">GIT</a>
* <a href="https://getbootstrap.com/">Bootstrap</a> 
* <a href="https://fonts.google.com/">google fonts</a>
* <a href="https://jquery.com/">jquery</a>

## Testing:

The site is responsive over different screen sizes with custom layouts where appropriate. The site has been tested on Mozilla Firefox, Google Chrome and safari and works as intended.The site was tested on an android phone, Iphone, Ipad, laptop, and desktop. All site functions work as intended.

The console displays no errors during site testing

During planning for this project i knew that i needed to have good testing in place for during and after the projects build/completion, thanks to the layout being organised in the wireframes i was able to select what feature to work on, organise how i was going to approach each section and follow my templates to check that it had been implemented correctly and works as expected. In future projects i would look to include more automated testing to help me with my tests.

The following tests have been used to ensure proper site functionality:

    
* <strong>W3C HTML Validator</strong>: This validator checks the markup validity of Web documents in HTML. it returned a warning of no headers in the section elements but the javascript add all the html when the site loads so this is ok.
* <strong>W3C CSS Validator</strong>: This validator checks the markup validity of Web documents in CSS. no errors were found.
* <strong>JSHint</strong>: A static code analysis tool for JavaScript.  code works ok but it asks me to donwload (ES6) alot.
* <strong>autoprefixer css online</strong>: checked the css so it works on safari and other platforms.

### Testing stories

Firstly I put up my project on the peer review slack channel. After a few days i only got one review but it was as follows.
* "one thing i will note is when i played i got all pairs with the last click but classed this as a fail!i'd consider a favicon as it's throwing an error to the console.remember to add a little annotation to your css but in general nice project build. The images are a little stretched i would consider just updating the images to the correct ratio, just a nitpick!"
once i received this i went back to my project and fixed the clicking bug as explained in my bugs section as well as the images being slightly stretched thats also explained in the bugs section. Annottation was added to the css.
* I had a friend and family play the game, they enjoyed it and found it easy to understand. There was no issues duirng play.

## User testing 

#### Gary
"i was able to understand the game very quickly once i start playing."

#### Steve

"the game was super easy to understand and fun. images on iphone could have been set up better."

#### Graham

"No advertising and quick to pick up. enjoyed the game and found it visually appealing"

#### Colin

"Good game although very simple it was easy to understand and found it eye catching"


## Overall:

### Responsiveness -


* <strong>Plan</strong>  : I knew that this project needed to be FULLY responsive and mobile friendly therefore the obvious option 
to use Bootstrap as this HTML Framework I'm most comfortable using. Testing using dev-tools throughout and also a final test of the 
entire site after completion.
* <strong>Implementation </strong>: Throughout writing my HTML code making sure to use appropriate bootstrap class modifiers to provide correct 
breakpoints for the content. Testing breakpoints was relatively simple thanks to the easy to use Bootstrap, i only really modified a 
few breakpoints after writing the majority of my HTML.
* <strong>Result</strong> : The Responsiveness of the site works as expected, no elements or content escape their boundaries or are hard to see on any device.
* <strong>Verdict </strong>: This test has passed and therefore the site is responsive.

 ### Design -
* <strong>Plan</strong> :The overall design of the site had to be bold and use exciting colours and imagery. 
Using vibrant colours like red, blue and white provide great contrast. 
* <strong>Implementation</strong> : Adding these colours through css allowed me to easily re use them for the different elements on the page.
* <strong>Result</strong> : The colours chosen work well for the theme of the site.
* <strong>Verdict </strong> : This test has passed and the overall colour scheme fits well for the purpose of the site.


## Features:

### Click counter -

* <strong>Plan</strong> : During planning i decided to add a click counter which was used as a countdown to wether or not a user won or lost the game. if all the cards where matched before the click counter went down they won. if not they lost.
* <strong>Implementation</strong> : using javascript i was able to make a click counter that worked on every click the user made while playing the game.
* <strong>Result</strong> : The click works effortlessly and cleanly. This is also fully responsive.
* <strong>Verdict </strong> : This test passed as the click counter works on all devices.

### flip cards with matching pictures -

* <strong>Plan</strong> : the main aim of the game was to match cards that showed up when the user clicked on them and they would have to remember them to find the matching cards.
* <strong>Implementation</strong> : i used javascript to make the cards flip when the user clicked on them by adding a class with another image called flip. i learned this from youtube.
* <strong>Result</strong> : the cards flip over then the user clicks and they stay flipped over when two cards are matched.
* <strong>Verdict </strong> : the cards stay matched and flip back if they dont on all devices with no issues.


## Bugs

### Bugs during development

* My wincodition variable had a `+-` instead of a `+=` which meant i couldnt get the code to work for a long time. To fix the issue i had a tutor look to point me in the right direction which helped massively.
* When i wanted to duplicate the array of heroes at the beginning of my code i couldnt seem to find a way without writing them out twice.  A student saw my code snippet and helped me out.
* I was having trouble using `""` and `''` when writing out html code in javascript.  My mentor reminded me about template literals which fixed the issue.
* Image sizing has been a massive issue on the site as the hero images will not stay the same as the back face marvel logo images. still need to fix this.
* i tried making a `shuffle function` but kept failing because i wasnt using a capital M for the `math.random`. i had a friend look at it and he pointed it out for me.
* The `shuffle function` then didnt work once i added the html function at the top so i had to add a new way of shuffling the cards which did it before they were written into the html.  it didnt work for a long time as i had the wrong spelling in the function after a lot of inspection i found the problem.
* The `gameRef.innerHTML` variable was actually `gamreRef.appendchild()` but this didnt work and i couldnt work out why so after some research i changed it to the code you see now as `gameRef.innerHTML()` which did the trick.
* game wasnt working on iphone so passed the css through an autoprefixer and it fixed the issues.
* If you were on your final click and you won the game by getting the last pair on your last click the lose screen was coming up.  i built a new `function` which the took the win and lose condititons in the same function instead of 2 different ones and it esemed to do the trick.

### known Bugs

* the image sizing when the card is flipped is wrong. ive tried all sorts of things to change it like changing from `px` to `%` then i tried to re size the images using photoshop and re load them back in but that didnt work either.  I think the issue is coming from the way im flipping the cards using the css.
* the cards are not exactly central on ipad but they look ok, theyre slightly off but it affects the iamges once margin or padding is alterered.
* if you click too quickly on the cards before they turn back over when its checking for a match then the click counter goes down.

## Deployment: 

Marvel memory game was developed on GitPod, using git and GitHub to host the repository.

When deploying the marvel memory game I used GitHub, the following steps were made:

* Opened up GitHub in the browser.
* Signed in using username and password.
* Selected my repositories.
* Navigated to ' <strong>fergusthompson/Worlds-most-amazing-memory-game</strong> '.
* In the top navigation clicked '<strong>settings</strong>'.
* Scrolled down to the GitHub Pages area.
* Selected '<strong>Master Branch</strong>' from the '<strong>Source</strong>' dropdown menu.
* Clicked to confirm my selection.
* Marvel memory game is now live on GitHub Pages.

## Running memory game Locally

<strong>Cloning memory game from GitHub</strong>:

* Navigate to '<strong>fergusthompson/Worlds-most-amazing-memory-game</strong>'.
* Click the green '<strong>Clone or Download</strong>' button.
* Copy the <strong>url</strong> in the dropdown box.
* Using your favourite <strong>IDE</strong> open up your preferred <strong>terminal</strong>.
* Navigate to your desired file location.
* Copy the following <strong>code</strong> and input it into your terminal to clone Worlds greatest memory game.

``` git clone https://github.com/fergusthompson/Worlds-most-amazing-memory-game.git ```



## Closing Notes:

Developing this project has taught me alot about how to provide users needs based on their interaction, working with new concepts has pushed my knowledge further and has helped me better understand how to manipulate this type of code. In the future I would like to implement other features like difficulty settings and a timer. This was my first timeusing javascript and therefore was a challenge to get to grips, however thanks to helpful documentation, and a few hints here and there from tutors/mentor I was able to achieve a solution in-line with the user requirements.

## Credits: 

* youtube - tips on making the card flipping functions (vanilla javascript tutorial)
* google - all phohos used were found on google. also font was from google
* Coolors.co - I made my colour pallette on their site
* cacoo.com - I made my wireframes on their site an imported them


And a special thanks to my mentor <a href="https://github.com/eventyret">Simon</a> for all his help


