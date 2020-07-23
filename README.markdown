# Heroes Quiz

## Do you know superheroes real names?

Are you "geek" enough to test your superheroes names knowledge with this quiz?

Superheroes used in this game are from both Marvel Universe and DC Universe.

How many names can you guess in 60 seconds? Wanna play it? Click [here to play](https://codepen.io/riccardo-andreatta/full/PoZVxRZ) with the Superheroes names.

## Description

A JavaScript game created on [CodePen](https://codepen.io/riccardo-andreatta/pen/PoZVxRZ).

In this repository there are 3 folders:
- one contains the distribution game (with compiled styles)
- one contains the source code
- the last one contains the questions (you can improve them and play with your questions, see below for instructions).

### Play with online questions

If you download (or clone) the repository, you can play this game just opening the `index.html` file in the `dist` folder. The game will fetch the hosted online JSON with the questions.

### Play locally

If you want to use it locally and fetch the questions in the `data` folder (you may want to improve them), do the following:
1. change the path in the `script.js` to get the JSON file in the data folder `const url = '../data/heroes-quiz-questions.json';`
2. start a local server
3. host the `index.html` file on the local server (so it will fetch the path for the JSON file correctly avoiding CORS errors)

## Do you want just play the game?

Click [here to play "Heroes quiz"](https://codepen.io/riccardo-andreatta/full/PoZVxRZ).
