<h2>Overview: </h2>
Scrambled Scrolls is a rogue-like word game with the core gameplay of Scrabble. Our game consists of five stages, each stage being harder to clear. If the player fails to clear a stage, they fail the game and the game will restart. Players fail to clear a stage if their ending score is below the required score for the stage.

<h2>Rules:  </h2>
    1. The game is single player.
    2. Tile Bag: A pool of additional tiles is drawn from throughout the game, replenishing players' hands after each turn.
    3. Forming Words: On a player's turn, they must form a valid word:
        - The word must be placed horizontally or vertically.
        - The word must connect with existing tiles on the board if it is not the first move.
    4. First Word: The first word must be placed so that one of its tiles covers the center square, which is a Double Word Score.
    5. Scoring: The score for each word is the sum of the letter values, adjusted by any bonus squares that the tiles occupy. If any tile lands on a Double Word or Triple Word square, the   entire word score is multiplied accordingly.
    6. Tile Replacement: After a player places tiles on the board, they draw new tiles from the tile bag to bring their hand back to 7 tiles.

Instructions to run game:

1. Install express to host the web app:
`npm install express`

2. Run the app:
`node app.js`

3. Go to the local host:
`http://localhost:3000/`




<h2>Sample Gameplay</h2>

![Link Name](/SampleScroll.png)  

<h3> Authors: </h3>
<ul>
    <li>Wilson Zheng (wjz224) </li>
    <li>Ryan Zheng (ryz224) </li>
    <li>Andy Shen (shs322) </li>
</ul>
