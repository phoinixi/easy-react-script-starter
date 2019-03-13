
# Game of Life

> Smallpdf coding challenge.

## The Challenge

Write a simple version of the [game of life](https://en.wikipedia.org/wiki/Conway's_Game_of_Life) with the stack ES6+JSX, React and Redux.

This challenge should take you a couple of hours and your are free to choose which feature to implement. There is no time pressure. Just notify us by email when you are done.

We are going to look at your code in terms of simplicity, structure and style. Please also write an imaginary todo list in this repository of what could be changed or added in the future.

# Francesco's experience

First at all, thanks for this opportunity. I had a lot of fun doing this assignment.
I have being reading React code in the past, but this was the first time that I was writing some code with React/Redux.

# How much time I have invested?

At beginning I needed some time to get used to Redux, except that, I have invested around 4 hours.

# Assumption, limitations and uglyness

- The out of bound cells are just considered dead (assumption)
- set/clear timeout with an external variable to the App component is not pretty (uglyness)
- Since it's a POC everything is done in the App component, ideally we would have multiple components

- Once you are playing, the only way to stop that is to press 'pause', so any other button/action will have effect but the game will keep playing. (limitation) Possible solution to that are:
- Other button are disables during play
- Other button press, also pause the game


# Possible TODO list

1. Fix the buttons behaviour (or disable them) during play
2. Configurable board size and game speed
3. Initial board configuration editable by the user
4. Adds tooltips (for desktop) to the controls (or better descriptions)
5. Show some statistics: alive cells, dead cells
6. Improve game algorithm
