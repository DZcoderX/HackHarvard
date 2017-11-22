# Try it out
 - www.pacmen.online

![Game Preview](https://github.com/x65han/HackHarvard/raw/master/gif.gif)
# Built With
`javascript`, `phaser.js`, `css`, `jquery`, `socket.io`, `html5`, `node.js`, `canvas`, `firebase`

# What it does
The game follows the concept of the original Pacman, but instead of Player Vs Ghosts, it's Player Vs Players. The winner will be the first person who earns 100 points.

## Please use keys: "W", "A", "S" & "D" to navigate.

# Challenges we ran into
The biggest challenge, which is also the biggest highlight of this game, is to deliver a smooth and synchronous multiplayer experience to the gamer. In order to achieve that, we developed a solid NodeJs backend with Web Sockets connected to Firebase, ensuring lightning speed data transfer with zero delays. Since the team has limited exposure to Phaser, a HTML5/Canvas gaming framework, the UX are limited and may glitch upon excessive data input. However, we implemented many software design patterns such as singleton and object pool to enhance UI efficiency.

# Accomplishments that we're proud of
Certainly, we are proud to deliver a project that works, the functionalities it offers and the potential it holds. The SDK provides both the backend and the database in a Three-Tier Architecture, only short an UI for the specific platform. Consequently, the game is not only limited to the current web platform, rather it can be expanded to other platform (desktop, mobile or VR) easily when connected to our backend SDK.

# What we learned
Most importantly, the team learned collaboration. Under few hours of sleep, we felt like constant communication and cooperative team work is crucially important to our success. Accessing the situation and ordering tasks in appropriate sequence boosted our efficiency greatly.

# What's next for PacMen
There are countless possibilities for this game. We only had time to launch Level 1 of the game. There are more levels to come and more awesome interactive features to come such as fire spitting, teleporting and special power ups etc.
