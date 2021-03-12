# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **NAME**

Time spent: **#** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

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
* [ ] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [x] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## GIFs

3 Mistakes being made:
![](http://g.recordit.co/jF4aQau1nJ.gif)

Button Demonstration
![](http://g.recordit.co/dowBFLtUbB.gif)

Gameplay(with speed-up)
![](http://g.recordit.co/HvJBQymzbr.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.w3schools.com/css/css_align.asp
https://www.w3schools.com/howto/howto_css_round_buttons.asp
https://stackoverflow.com/questions/9419263/how-to-play-audio
https://stackoverflow.com/questions/8488005/how-to-put-a-jpg-or-png-image-into-a-button-in-html/8488022


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
    
    Though somewhat embarrassing, my main problem in this challenge was the logic behind the guessing,  more specifically it was the losing at 3 mistakes and ending the game at the right time when winning. I learned a very valuable lesson in why to deal with problems as they come, instead of letting them stack up for later. 
	With my first attempt at the logic branching of the guess function I overcomplicated the conditional statements. However, the code compiled and loaded the site so I kept going with it and attempted to play the clues faster every time a guess is correct, while trying to balance the best number turns and speed to to go until the game is won. On top of that, I attempted to add a “3 lives” feature where 3 incorrect guesses would lead to the losegame function running. I kept trying to fix bugs and find what was breaking the project, but kept creating more confusion and trouble for myself. 
	In the end, I scrapped the main function and the extra functions I made for these features. I rebuilt it from scratch with help from the guess function provided and added minor conditional statements (2-3 lines) for these basic additional features. Although time consuming, this was the best choice I feel I could have made because it gave me a fresh look on what I was trying to do- unclouded by the prior confusion of jumbled, bugged code. 



3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

    My biggest question and what seems like the biggest mystery to me after this completing project is networking protocol and making a web site/web app realtime or online. I'm not entirely sure what the proper term is but I would be greatly interested in creating something that multiple users can interact with at the same time-from across the world! I'd like to learn what routing and services go into making a dream like this happen, but with that knowledge I could make applications that are interactive- anything from a chatroom & messaging platform, to a fun multiplayer game where friends can play together from their own devices!


  
4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    If I had more hours to work on this project in between classwork I would happily implement animated features to the buttons and other aspects of the project. It's my personal belief that a severely underrated and underrepresented portion of web development is design. I believe that the aesthetics behind a project, regardless of the function or purpose of it, play a major role in shaping how the user feels when interacting with the project. I would like to revisit this project once I have accumulated more knowledge and experience with css and javascript, in order to create a better (and more fun!) user experience. 



## License

    Copyright [Adam Korczak]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.