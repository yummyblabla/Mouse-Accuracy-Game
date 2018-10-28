# Mouse-Accuracy-Game
HTML5 Canvas game developed for BCIT-COMP1536

For this assignment, the class was given a task of making a primitive clicking game using image tags and making the images apparate to a random location on the page. The limitations were that we can only use Javascript, HTML, and CSS. No libraries such as jQuery.

I decided to use HTML canvas to make the game more dynamic, which allowed me to have more control over some of the extra features I added, such as the game and difficulty modes.

<br>

<b>Game Modes:</b>

<i>Survival Mode</i>

Player starts with 5 lives. They will lose a life if they do not kill a respawning zombie within 3 seconds.

<i>Timed Mode</i>

Player has to kill as many zombies as they can within 30 seconds. An extra zombie is added to the screen every 5 seconds.

<br>

<b>Difficulty Modes:</b>

<i>Easy</i>

Image size: 150px * 150px

<i>Normal</i>

Image size: 100px * 100px

<i>Hard</i>

Image size: 75px * 75px

<b>How Scoring is Calculated:</b>

Player Score += Player's Current Accuracy * 100 / Difficulty(Image Size)

<br>

You can try out the game at http://www.yummyblabla.com/portfolio/mouse-click-accuracy-game.html
