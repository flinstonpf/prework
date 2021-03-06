# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Peter Flis

Time spent: 2 hours spent in total

Link to project: https://glitch.com/edit/#!/juicy-vanilla-salt?path=index.html%3A1%3A0

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![https://imgur.com/49BQbjn]


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random to find out how to use Math.random()

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The biggest challenge that I encountered during the creation of this submission was with the randomized array of choices being generated. Coming from a python background I am used to using things such as List comprehensions in order to generate such things. 
I could have done something like array = [random.randint(1,5) for i in range(9)] to accomplish this task. However, since we are using javascript for this project I had to learn how to use javascript's version of random. It was really fortunate that javascript and java share the same random function, so it was rather straightforward to implement after I realized that.
The way I arrived at my solution was through a variety of google searches and I used python as a root for my searching. First I googled if Javascript supports list comprehension and found that unfortunately it does not. As a result, I ended up using a rather simple solution to randomize the values in the array by simply using a for loop and redefining all the values using Math.random.
Overall, it is a problem that I run into alot and it was a simple issue of syntax versus a conceptual issue with my program which made it rather straightforward to resolve.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
My question about web development is how to write effective and maintainable code. Even in a simple program like this one it can easily become convoluted if we keep adding more classes to our program.
I also look forward to backend development part of web development. I know that databases are a critical component and I have worked with those before, but I have yet to work with any Backend APIs or anything complicated to which I am looking forward to.
My interests also lie within the realm of front-end development. I find making sites that are visually appealing is a critical part of any working website. Personally, I have a very poor grasp over this aspect of web development and hope to improve that through my participation in the SITE program.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
If I had a few more hours on this project I would definitely improve the UI of the application. Currently, it is rather barebones and I stuck with what the tutorial provided and made mainly simple changes to the UI. For a simple application like this one the UI and visual appeal are the parts that can improved the most to appeal to a greater audience.
Of course other improvements can be made, like allowing the user to choose a "difficulty" where they can select how many turns they have to progress before winning. The amount of squares or boxes that appear on the screen should also be adjustable by the user.
There could also be a mode that goes on forever and even implements a leaderboard, so the user can see their personal records as well as the records of others. All of these improvements are things I would have done if I had a few more hours to work on this project.



## License

    Copyright Peter Flis

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
