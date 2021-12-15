![Advent of JavaScript](https://adventofjavascript.s3.us-east-1.amazonaws.com/2021/advent-of-js-gumroad-cover.png)

# Day 3 - KeyBoard

## OverView
In this project, we're creating a keyboard.
Day 3 of Advent of JavaScript by Amy Dutton

Users should be able to:

- See the keyboard centered on the page
- Whenever a user hovers over a specific key it will change colors 
    - White keys will change to yellow #ffd200
    - Black keys will change to pink #f40082
- When a user clicks on a specific key, it will play an audio clip. 
- The audio clips are numbered, but I did not specifically number the keys. You can pick which key should be associated with each audio file.
- If a user clicks on one key, then immediately clicks on a second key. The 2 files should both play. Meaning, clicking on one key will not stop an existing audio file from playing. 

### Links

- Solution URL: (https://github.com/mod771/KeyBoard)
- Live Site URL: (https://mod771.github.io/KeyBoard/#)

## My Process
I created new constant variables for each audio file and did a event listener for each key.

## What I Learned
- I learned how to create audio files. 

const sound1 = new Audio("audio/key-1.mp3");

- I learned how to play audio files. 

sound1.play();

### Author
- HTML and CSS made for Advent of JavaScript by Amy Dutton
- JavaScript by Paola Silva
