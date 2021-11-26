# Gam&Play
Welcome! https://fabiocmad.github.io/portfolio_project_2-gameplay/

# *HTML/CSS/Javascript website for gamers.*
This website was designed for gamers enthusiasts. We have a main page explaining about the game history and hot to play it. A page for the rack, paper, scissors game itself, and a third page for users to submit a feedback form.

![Am I Responsive?](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/356618dd763254433abfa9b31e5a84f631873b5c/assets/images/testing/Screenshot%202021-11-25%20at%2022.58.31.png)

# Table of Contents
On the top left of this GitHub readme file, we can find the Table of Contents for quick search on topics within this document.
<p align="center">
   <img src="assets/images/testing/Screenshot 2021-11-25 at 23.05.22.png"/>
</p>

**A live version on the website can be found** [here](https://fabiocmad.github.io/portfolio_project_2-gameplay/)

## Initial Wireframes
Initial idea was to create a list of option of games for the user to choose from. Considering complexity of the project and deadline I had to adjust the idea accordingly and end up choosing a Rock, Paper ans Scissors game.

![Wireframe](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/7ec1654e184deb5df3fb3b5f20888879056a7ee2/assets/images/testing/Screenshot%202021-11-18%20at%2017.17.06.png)
![Wireframe](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/7ec1654e184deb5df3fb3b5f20888879056a7ee2/assets/images/testing/Screenshot%202021-11-18%20at%2017.17.16.png)
![Wireframe](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/7ec1654e184deb5df3fb3b5f20888879056a7ee2/assets/images/testing/Screenshot%202021-11-18%20at%2017.17.25.png)

# Color Palette
Initially had chosen black, white and orange, and decided to change orange to lightSalmon along the way as its a soft color with less contrast and better visibility comparing to the others.
![Palette](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/ad780cada9534d1b70c8f8abd1b43c8100ef0dcd/assets/images/testing/Screenshot%202021-11-25%20at%2023.29.53.png)

## Features
### Existing Features
Main page and logo/heading. Header consistir of links to homepage (main), the game, and the feedback form on the nav bar. There's an image on the left hant side, and two sections on "About the game" and "How to play". Social media icons on the bottom link user to the respective websites and open on a new page.
![Main](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/ad780cada9534d1b70c8f8abd1b43c8100ef0dcd/assets/images/testing/main.png)

Feedback Form Page

![Feedback](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/b67661d901d3a0f205eaa44613559027b942c5d8/assets/images/testing/feedback.png)

#### About the game
Use will choose on each roung the choice of play, it can be selected by clicking on the rock, paper or scissors icons. The Javascript behind the website will randomly select an option to play as the computer against the user. Scores are updated acccordingly to who wins, and the who reaches five points first is the winner.

#### Selecting your move
For draws, a gray shadow behind the button selected will appear, and the score wont change.

![Draw](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/ad780cada9534d1b70c8f8abd1b43c8100ef0dcd/assets/images/testing/grayChoice.png)

For user wins, a green shadow appears and user score increases by one point.

![Win](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/ad780cada9534d1b70c8f8abd1b43c8100ef0dcd/assets/images/testing/greenChoice.png)

For computer wins, a red shadow appears and computer score increases by one point.

![Lose](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/ad780cada9534d1b70c8f8abd1b43c8100ef0dcd/assets/images/testing/redChoice.png)

At the end of 5 rounds a message is prompted to the user telling the user has ended and have the choice to continue playing if wishes to do so. If continues, the score is reseted to zero and the user can start a new game.

## Testing
A series of testings were done to ensure that the user experience will be up to standards and provide a overall great experience, with no broken links nor bugs (bugs were found and will be shows at next topic). The tests and results were the following:


Testing - Responsiveness | Result
------------ | -------------
Click on header logo brings refreshes pages for main image | Pass
Game Page adapts and change number of score to phone size  | Pass
Headers and Paragraphs adapts and respond according to screen size  | Pass
Feedback form test are sent to "https://formdump.codeinstitute.net/" | Pass

Testing - Game | Result
------------ | -------------
Whoever reachs 5 points the relevant message is prompted | Pass
Score increases depedning on who got the point  | Pass
score resets after reaching 5 points | Pass
Computer choise ramdmly generated for a fair result  | Pass

Testing - Footer | Result
------------ | -------------
Click on Social Media Facebook opens a new Facebook tab Page | Pass
Click on Social Media Twitter opens a new Twitter tab Page | Pass
Click on Social Media YouTube opens a new YouTube tab Page | Pass
Click on Social Media Instagram opens a new Instagram tab Page | Pass

### Validator testing
* HTML index - No errors were returned when passing throught the official [HTML Validator](https://validator.w3.org/nu).
![Index](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/ce9ce9906b094c7b2c315e15ef2403596de2cb4e/assets/images/testing/htmlCheckerIndex.png)

* HTML feedback - No errors
![Feedback](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/ce9ce9906b094c7b2c315e15ef2403596de2cb4e/assets/images/testing/htmlCheckerFeedback.png)

* HTML Game - No errors
![Game](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/ce9ce9906b094c7b2c315e15ef2403596de2cb4e/assets/images/testing/htmlCheckerGame.png)

* CSS - No errors
![Css](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/ce9ce9906b094c7b2c315e15ef2403596de2cb4e/assets/images/testing/cssValidator.png)

* Javascript - No errors
![js](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/ce9ce9906b094c7b2c315e15ef2403596de2cb4e/assets/images/testing/jsHint.png)

### Unfixed Bugs
On mobile I see that the responsiviness of two divs on the main page are blocking the end of the content within the paragraph from being read, On next steps of the project I would continue working to fix that type of error.
![error](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/d5ec5a87c8b19bf0d29ffbd952fdbb0ec70ec339/assets/images/testing/bugMobile.png)

## Deployment
Please see below the process of deployment for this website

- The site was deployed to GitHub pages
   - In the GitHub repository, navigated to the Settings tab
   - From the source section drop-down menu, selected the Master Branch
   - Once the master branch has been selected, the link for the page and a green sign that the site was deployed was shown (https://fabiocmad.github.io/portfolio_project_2-gameplay/)



## Acessibility
![Acessibility](https://github.com/fabiocmad/portfolio_project_2-gameplay/blob/e9ede968723872b07f46fe8143740ff7bcd2bd60/assets/images/testing/acessibility.png)

## Credits
* https://learn.codeinstitute.net/dashboard - "Writing your readme.md file" / "Positioning and Hero Image lesson" / "Best Practices" / "UX Strategy Plane" / "Love Running Project" - Meet Up Times lesson to understand positioning of image on my project.
* https://fonts.google.com/ - Google Fonts
* https://fontawesome.com/ - Font Awesome
* https://github.com/ - GitHub
* https://developer.chrome.com/docs/devtools/ - Chrome Tools
* https://learn.shayhowe.com/html-css/writing-your-best-code/ - Code practices
* https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f - Best practices
* https://google.github.io/styleguide/htmlcssguide.html#General - Style rule guides
* https://guides.github.com/features/mastering-markdown/ - Mastering markdown language
* https://www.pinclipart.com/pindetail/iRbhhmx_thanks-again-i-tried-your-suggestion-of-increasing/ - Logo Image
* https://www.youtube.com/watch?v=jaVNP3nIAv0 - Game Tutorial
* https://www.gettyimages.ie/detail/video/paper-rock-scissors-game-on-black-background-stock-footage/1179347461 - Background Image
* https://codebeautify.org/htmlviewer - Code review
* http://ami.responsivedesign.is/# - Am I responsive


