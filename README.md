# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Abigail Paharsingh**

Time spent: **10** hours spent in total

Link to project code: (https://glitch.com/edit/#!/small-cheerful-passionfruit)
link to project webpage: (https://small-cheerful-passionfruit.glitch.me)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn


The following **additional** features are implemented:

- [x] Added a counter for the number of mistakes. 

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

## This is what happens when I lose!
![required features lose](https://github.com/abbypaharsingh/codepathprework/blob/main/SimpleMemoryGameLose_required.gif)
## This is what happens when I win!
![required features win](https://github.com/abbypaharsingh/codepathprework/blob/main/SimpleMemoryGameLose_required.gif)
## Optional Features!!
![optional features](https://github.com/abbypaharsingh/codepathprework/blob/main/SimpleMemoryGame_optional.gif)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://developer.mozilla.org/en-US/docs/Web/CSS/color_value,
https://stackoverflow.com/questions/5836833/create-an-array-with-random-values,
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random,
https://stackoverflow.com/questions/351409/how-to-append-something-to-an-array,
https://www.delftstack.com/howto/javascript/javascript-float-to-int/,
https://www.w3schools.com/jsref/met_win_setinterval.asp,
https://www.geeksforgeeks.org/how-to-add-update-an-attribute-to-an-html-element-using-javascript/,
https://www.w3schools.com/js/js_htmldom_html.asp,
https://masteringjs.io/tutorials/fundamentals/string-concat#:~:text=The%20%2B%20Operator,used%20to%20concatenate%20two%20strings.&text=You%20can%20also%20use%20%2B%3D,for%20a%20%3D%20a%20%2B%20b%20.&text=If%20the%20left%20hand%20side,hand%20side%20to%20a%20string.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)


In the process of creating this submission, my biggest problem was syntax errors. The first error was that after I added sound to my buttons, they stopped changing colors.  I retraced my steps in the code, trying to figure out the source of the issue. After searching for some time unsuccessfully, I took a break and came back with a fresh mind to see my code from a different perspective. It turns out I made a capitalization error and that small mistake caused this problem. My second problem was another syntax error, but this time I was able to find it more quickly after my experience with the first. So I combed through line by line and compared with the code provided in the instructions. It was just missing a comma. 
Overall, working with the optional features  also proved challenging because I have never worked with HTML, CSS or JavaScript before. I had to search the internet to figure out how to implement each task. This took much longer than I expected. One of the problems I had here was that I misunderstood how “Math.random” worked. It was causing the game to crash because it was returning numbers 0 to 5 instead of 1 to 6. I fixed this by adding 1 to the calculations. When I saw this project at first, I was very intimidated, but I ended up really enjoying it and felt proud of my finished product. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 


I have never done web development before, and so everything about this pre-work was intriguing to me and raised many questions.:
- Is it standard to use multiple languages in web development? 
- How do they work together if they are different languages? 
- Why can we only do some tasks in CSS and others in JavaScript? 
- Do programmers generally use IDE’s for web development?
- How does one manage a large website, with different webpages and complex applications?
- How does deploying a website work?
- How does one make complex animations?
- How do websites store data, for example user information and product information?
- How do websites and phone applications stay in sync?
- What are the pros and cons for a mobile app vs a mobile friendly webpage? 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours, I would add several levels to the game. Each level would have more buttons, some levels would have all buttons the same color but with different sounds. Others would have all the same sound with different colors. Or some combination of both of these things, i.e two buttons with the same color or three with the same sound. I might also add a points system that could be used to gain an extra guess or hints. I would probably make the mistake counter look better, and add an exciting congratulatory message when the player wins each round. 



## Interview Recording URL Link

[My 5-minute Interview Recording](https://smith.zoom.us/rec/share/D5P2omHGuv1lUMHecKZxeOHybBTvlyjVbrcxa5fJkNuUKQLvCHwW9kxgepknV3SF.INCMyAmGBE_YE4WF?startTime=1648830969000)


## License

    Copyright [Abigail Paharsingh]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
