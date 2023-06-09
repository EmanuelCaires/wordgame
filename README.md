# wordgame

The WordGame is a simple JavaScript game where players take turns guessing the name of an animal based on its picture. The game keeps track of each player's score, and the first player to reach a score of 5 wins.

![](wireframes/alldevices.png)

# Table of Contents
* [UX](#ux "UX")
    * [User Goals](#user-goals "User Goals")
    * [User Stories](#user-stories "User Stories")
    * [Site Owners Goals](#site-owners-goals)
         * [Requirements](#requirements)
         * [Expectations](#expectations)
     * [Design Choices](#design-choices)
        * [Fonts](#fonts)
        * [Colours](#colours)
        * [Structure](#structure)
    * [Wireframes](#wireframes)
        * [Deployment](#deployment)
    * [Features](#features)
        * [Existing Features](#existing-features)
            * [Landing Page](#landing-page)
            * [Testing](#testing)
    * [Tech Stacks](#tech-stacks)
        * [Languages](#languages)
        * [Tools](#tools)
    * [Credits](#credits)
* Ux

## User Goals
* Guess the Animal: Your primary goal is to guess the name of the animal displayed in the image correctly.

* Score Points: Each correct answer earns you one point. The game keeps track of your score, so try to accumulate as many points as possible.

* Compete with Others: Challenge your friends or family members to beat your score. The game supports multiplayer, allowing multiple players to take turns guessing the animals.

* Achieve Victory: The first player to reach a score of 5 wins the game. Strive to be the first to achieve this milestone!

* Improve Animal Knowledge: The game presents various animal images, providing an opportunity to learn and expand your knowledge of different species.

* Quick and Engaging Rounds: The game generates random animals for each round, ensuring that every game session is unique and exciting.

* Reset and Restart: If you want to start a new game at any time, click the "Reset" button. This will reset the scores and generate a new animal image, allowing you to begin a fresh round.

## User Stories
* As a player, I want to test my animal knowledge and see if I can correctly identify different species based on their pictures.

* As a competitive player, I want to compete with my friends or family members to see who can earn the highest score in the Animal Guessing Game.

* As a learner, I want to use the Animal Guessing Game as an educational tool to improve my knowledge of various animals and their characteristics.

* As a casual player, I want to enjoy a quick and engaging game session that offers entertaining challenges without requiring a significant time commitment.

* As a multiplayer enthusiast, I want to have the option to play the game with multiple players, allowing us to take turns and see who can reach the winning score first.

* As a beginner, I want clear instructions on how to play the game, including how to enter my guess, check the answer, and understand the feedback provided.

* As a returning player, I want the ability to reset the game easily and start a new round with fresh animal images and scores. section with free weights and other equipment.

## Site Owners Goals
* As the site owner, my goal is to create an enjoyable and engaging experience for young age players who want to test their animal knowledge.

* I aim to provide a visually appealing and user-friendly interface that enhances the gameplay and encourages users to continue playing.

* I want to encourage social interaction and friendly competition by implementing multiplayer functionality, allowing players to compete with their friends or family members.

* I strive to foster a learning environment where players can expand their knowledge of different animals and their characteristics.

* I aim to ensure that the game is accessible to a wide range of users, regardless of their level of experience or expertise in animals.

* I want to regularly update the game by adding new animal images and expanding the question bank, providing fresh challenges for players.

* I value user feedback and suggestions, as they help me improve the game and address any issues or concerns that players may have.


## Requirements
* A web browser: The game is built using HTML, CSS, and JavaScript and can be played on any modern web browser.

* Internet connection: The game requires an internet connection to load the necessary assets, such as animal images.



## Expectations
*Fun and Challenging Gameplay: The WordGame offers an entertaining and engaging experience that challenges your animal knowledge and identification skills. Enjoy the thrill of guessing animals based on their pictures!

* User-Friendly Interface: The game features a clean and intuitive interface that allows for easy navigation and interaction. The input field for entering guesses, the submit button, and the feedback display is designed to be straightforward and user-friendly.

* Randomized Animal Images: Each round of the game presents a random animal image, ensuring a unique and unpredictable gameplay experience. You can expect a diverse range of animals to guess, keeping the game fresh and exciting.

* Immediate Feedback: The game provides immediate feedback on your answers. You'll know right away if your guess is correct or incorrect, allowing you to learn and improve with each attempt.

* Multiplayer Capability: The WordGame supports multiplayer functionality, enabling you to compete with your friends or family members. Take turns guessing the animals and see who can achieve the highest score or reach the winning score first.

* Scoring System: The game keeps track of your score as you progress. Each correct guess earns you a point, and the current scores of all players are displayed on the screen. Strive to achieve the highest score or be the first to reach the winning score!

* Educational Value: The game offers an opportunity to expand your knowledge of different animals and their characteristics. Whether you're a nature enthusiast or simply looking to learn something new, the Animal Guessing Game provides an enjoyable way to explore the animal kingdom.

* Resetting the Game: If you want to start a new game or reset the scores, you can easily do so with the provided "Reset" button. This allows you to begin fresh rounds and compete again for the highest score or victory.

# Design Choices

## Fonts
In order to move away from the basic fonts available, I have used 
[Google Fonts](https://fonts.google.com/ "Google Fonts") 
to find a text that best suits the feel of the website.
 For the main text, I have chosen 
 [Roboto](https://fonts.google.com/specimen/Roboto "Roboto") 
 as I feel it has a sharp, simple and easy-to-read look. 
 To make the headers stand out from the text.


I will explain the uses of the various colours below, starting from top to bottom.

## Colours
 * `rgb(252, 151, 8)` - This colour will be used as h1.

 * `rgb(255, 255, 255)` - This colour will be used on h2 paragraphs and butoon background color.

 * `rgb(238, 27, 55)` - This colour will be used as a  reset bottom colour and feedback.

 * `rgb(22, 93, 6)` - This colour will be used as a  submit bottom colour.

## Structure
I will be building my website with a mobile-first mindset using the iPhone 5/SE (320px) as the smallest screen size for styling to look good on. The screen size breakpoints that I will be using are from [Bootstrap breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/ "Bootstrap").

| Screen Size | Breakpoint |
| ----------- | ---------- |
| x-small     | <576px     |
| small       | => 576px   |
| medium      | => 768px   |
| large       | => 992px   |
| x-large     | => 1200px  |

## Wireframes
I have used [Balsamic](https://balsamiq.com/wireframes/ "Balsamic") to develop my wireframes for my website. I initially created the mobile version and then the wireframes and then scaled it up for both tablet and desktop. Because a requirement is to give little but quality information to the user to make them want to engage with the club, a one-page website is used. This gets the user through the content and quickly to the contact form and details via scrolling or directly via the navigation bar.

The wireframes are below:

###   [desktop view](wireframes/wireframesdesktop.jpg)

###   [phone view](wireframes/wireframesmobile.jpg)

###   [tablet view](wireframes/wireframestablet.jpg)

# Features

## Existing Features

## Landing Page
+ The landing page image gives the user instant knowledge of what is involved in the webpage, the images show the different types of devices that the page can load.

## Desktop
![](wireframes/desktoppage.jpg)

## Mobile
![](wireframes/mobilepage.jpg)

## Tablet
![](wireframes/tabletpage.jpg)

## Deployment
Following writing the code and then committing and pushing it to GitHub, this project was deployed using GitHub by the following steps.

+ Navigate to the repository on Git Hub and click 'Settings'.
+ Then select 'Pages' on the side navigation.
+ Select the 'None' dropdown, and then click 'Master'.
+ Click on the 'Save' button.
+ Now The website is now live on https://emanuelcaires.github.io/wordgame/
+ If any changes are required, they can be done, committed and pushed to GitHub and the changes will be updated.

## Testing
+ I feel that the site has hit the goals required by all parties. 
The site responds nicely to all different screen sizes, 
the images look clean and sharp on all device sizes with very little, 
 
+ During the validation process of my HTML and  CSS, I encountered a few minor issues that required attention. After making the necessary amendments, I revalidated the HTML and CSS it successfully passed without any errors.

- HTML (index.html) validator [results]("https://validator.w3.org/")
    
![](wireframes/htmlchecker.jpg)


- CSS validator [results]("https://jigsaw.w3.org/css-validator/")

![](wireframes/cssvalidator.jpg)

- LightHouse Desktop

![](wireframes/lighthousedesktop.jpg)

- Lighthouse Mobile

![](wireframes/lighthousemobile.jpg)


## Introduction
This document provides an overview of the tests conducted on the JavaScript code using Jest. Jest is a popular testing framework for JavaScript that offers a simple and intuitive approach to writing tests. The tests aim to validate the functionality and behaviour of the provided JavaScript code.

+ Test Suite: Animal Guessing Game
The Animal Guessing Game is responsible for the functionality of a game where players guess the name of an animal based on an image displayed on the screen.

javascript
+ Test Case 1: generateAnimal should set a new animal image

test('generateAnimal should set a new animal image', () => {
  generateAnimal();

  const animalImage = document.getElementById('animal-image');
  const animalSrc = animalImage.src;

  expect(animalSrc).not.toBe('');
});

+ Test Case 2: checkAnswer should increment the score for the current player on the correct answer

test('checkAnswer should increment the score for the current player on correct answer', () => {

const answerInput = document.getElementById('answer-input');
  answerInput.value = 'bear';

  const player1ScoreElement = document.getElementById('player1-score');
  const player2ScoreElement = document.getElementById('player2-score');

  checkAnswer();

  if (currentPlayer === 1) {
    expect(player1ScoreElement.textContent).toBe('Player 1: 1');
    expect(player2ScoreElement.textContent).toBe('Player 2: 0');
  } else {
    expect(player1ScoreElement.textContent).toBe('Player 1: 0');
    expect(player2ScoreElement.textContent).toBe('Player 2: 1');
  }
});

+ Test Case 3: resetGame should reset the game state

test('resetGame should reset the game state', () => {

  const player1ScoreElement = document.getElementById('player1-score');
  const player2ScoreElement = document.getElementById('player2-score');
  const feedbackElement = document.getElementById('feedback');
  const submitButton = document.getElementById('submit-button');
  const answerInput = document.getElementById('answer-input');

  player1ScoreElement.textContent = 'Player 1: 2';
  player2ScoreElement.textContent = 'Player 2: 3';
  feedbackElement.textContent = 'Incorrect answer';
  submitButton.disabled = true;
  answerInput.value = 'wrong answer';

  resetGame();

  expect(player1ScoreElement.textContent).toBe('Player 1: 0');
  expect(player2ScoreElement.textContent).toBe('Player 2: 0');
  expect(feedbackElement.textContent).toBe('');
  expect(submitButton.disabled).toBe(false);
  expect(answerInput.value).toBe('');
});

## Conclusion
The tests conducted on the JavaScript code using Jest aimed to verify the correctness of the game functionality. 
By testing the generateAnimal, checkAnswer, and resetGame functions, we ensure that the game operates as intended. 
Additional tests can be added to cover other functions or edge cases as required.

The tests help identify and prevent potential issues, ensuring the reliability and robustness of the code. 
Regularly running these tests during development can provide confidence in the code  behaviour and facilitate maintenance and future enhancements.


# Tech Stacks

## Languages
   
* [HTML](https://en.wikipedia.org/wiki/HTML "HTML")

* [CSS](https://en.wikipedia.org/wiki/CSS "CSS")

* [JS](https://en.wikipedia.org/wiki/JavaScript "JAVASCRIP")

* [Google Fonts](https://fonts.google.com/ "Google Fonts")

## Tools

* [Gitpod](https://www.gitpod.io/ "Gitpod")

* [Balsamic](https://balsamiq.com/wireframes/ "Balsamic")

* [W3C HTML Validation Service](https://validator.w3.org/ "W3C HTML")

* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/ "W3C CSS")

* [Bootstrap](https://getbootstrap.com "Bootstrap")

* [Google Fonts](https://fonts.google.com/ "Google Fonts")
                
## Credits
                
* For code testing, my soon Matias Caires

* For Content and style inspiration,

* [picresize](https://picresize.com/)

* [123rf](https://www.123rf.com//)

