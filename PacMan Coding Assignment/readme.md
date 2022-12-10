# Pac-Man Movement Exercise

## PacMan Assignment

If you've ever played an arcade game, then you're familiar with Pac-Man!

This is the game where the player controls PacMan who travels inside a maze trying to eat all the dots while avoiding the colorful ghosts.

You're not going to build the full PacMan game in this activity. However, you will be building a feature of this game, which displays and moves PacMan from one side of the screen to the other.

## Multiple Ways of Solving The PacMan Problem: setTimeout vs. setInterval
As a programmer, you'll quickly find that there are multiple ways to solve the same problem. Here, you'll put that concept into practice by making PacMan move using a new function.

In the video, Dr. Williams used `setTimeout` to calculate the movement of PacMan. Here, you are going to solve it using `setInterval`. While working through this new way of solving the problem, you should also consider what tactics help you. This will make you a better developer.

To use setInterval you will need to structure the function in a different way from when you used `setTimeout` with the video. Instead of passing in two arguments to `setTimeout`, you will pass four arguments to `setInterval`. The first extra one is called `pos`, which stands for position, and is already set at 0 on line 2. The second extra argument is `pageWidth`, which is calculated for you on line 3.

The starter code included will help you get up and running. The starter code you see on the right contains the following items:

- images folder: This folder contains the images representing Pac-Man at different stages (mouth open, mouth closed).
- index.html: This is the HTML file that displays your Pac-Man.
- pacman.js: This contains the PacMan animation JavaScript starter code.
Please check out all the files before you start coding this activity. You can read through the code comments in pacman.js to find out what each line of code does. Also, you can see the PacMan images to visualize its movement animation.

## Your task in this activity is to update the starter code to add screen edge detection to the Pac-Man animation:

- At line 34 on the pacman.js file, add a `setInterval` call to run every 200 milliseconds
- Update the `checkPageBounds` function to allow PacMan to reverse his trajectory once the PacMan image hits the edge of the screen on the x-axis
Hint: setInterval allows you to run a function repeatedly, starting after the interval of time, then repeating continuously at that interval.

## Tasks

- Update checkPageBounds to reverse Pac-Man direction upon hitting the edge of the screen
- Add a setInterval call to run every 200 milliseconds