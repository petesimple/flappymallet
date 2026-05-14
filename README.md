Flappy Mallet

One mallet. Infinite bad decisions.

Flappy Mallet is a tiny air hockey inspired browser game where you guide a flying mallet through a chaotic tunnel of goals, rails, bonus pucks, and questionable physics.

It is built as a single file web game and is ready to host on GitHub Pages.

Play it here:

https://petesimple.github.io/flappymallet/

What is this?

Imagine Flappy Bird wandered into an air hockey tournament, got heckled by the table, and decided to become a mallet.

That is Flappy Mallet.

Tap, click, or press space to flap upward. Avoid the obstacles, collect yellow bonus pucks, chase the high score, and blame the table when gravity gets rude.

Features

* Mobile friendly tap controls
* Desktop click and spacebar controls
* Air hockey themed flying mallet
* Scrolling goal obstacles
* Yellow bonus pucks for extra points
* Practice Mode
* Best score saved locally in the browser
* Blitz Mode every 10 point threshold
* Goofy game over messages
* GitHub Pages ready
* No server required

How to Play

* Tap, click, or press Space to flap
* Avoid the top and bottom rails
* Fly through the goal gaps
* Collect yellow pucks for bonus points
* Keep going as long as possible
* When you crash, blame the table

Blitz Mode

Blitz Mode kicks in when your score reaches or passes each 10 point threshold.

Examples:

* 10 points triggers Blitz Mode
* 20 points triggers Blitz Mode
* 30 points triggers Blitz Mode
* If a bonus puck jumps you from 9 to 11, Blitz Mode still triggers

During Blitz Mode:

* The game speeds up
* The mallet glow changes from blue to red
* A BLITZ MODE badge appears
* Everyone briefly questions their life choices

Bug Fix Shoutout

Big shoutout to Alex for catching the first known Blitz Mode bug.

Originally, Blitz Mode only triggered if the score landed exactly on 10, 20, 30, etc. Since bonus pucks can add 2 points, a player could jump from 9 to 11 and skip Blitz Mode entirely.

That has been fixed. Blitz Mode now triggers when the player reaches or passes the next 10 point threshold.

The Flappy Mallet Rules Committee reviewed the complaint and ruled in Alex’s favor.

Hosting on GitHub Pages

1. Create a new GitHub repository named flappymallet
2. Add the game file as index.html
3. Add this file as README.md
4. Go to the repository settings
5. Open the Pages section
6. Set the source to the main branch
7. Visit your published site

For Pete’s version, the live URL is:

https://petesimple.github.io/flappymallet/

Local Development

Because this is a single file game, you can open index.html directly in a browser.

For a simple local server, you can also run:

python3 -m http.server 8000

Then visit:

http://localhost:8000

File Structure

flappymallet/
  index.html
  README.md

Future Ideas

* Add sound effects
* Add a tournament mode
* Add character skins
* Add Photon Doubles themed obstacles
* Add a leaderboard
* Add a share score button
* Add controller support
* Add more ridiculous game over messages

Credits

Created by Pete Lippincott with a heroic assist from the air hockey practice crew.

Special bug feedback credit to Alex.

Built for the air hockey community, the Photon Doubles crowd, and anyone who has ever blamed a table with complete confidence.

License

This project is currently shared as a fun community mini game. Add a license if you plan to make the repository public for reuse or contributions.
