# Making Your First Game in Java

Source code for a video game project tutorial on the **Learn Code By Gaming** YouTube channel.

Watch it here: COMING SOON


# Project Ideas

## ![Green Circle](images/green-circle.png) Beginner

- Change the colors that are being used.
- Change the image files that are being used.
- Change how many points you get per coin.
- Make instance or class variables to control hardcoded values like the ones just mentioned.
- Use WASD instead of arrows for movement.
- Change the dimensions of the game board.
- Make a new coin appear whenever the player picks one up.
- Change the tile size.
  - Remember to update your image files, or scale the images.

## ![Blue Square](images/blue-square.png) Intermediate

- Make coins disappear after some time.
  - By ticks, or using a separate timer, or after the player has moved so many squares.
- Make more coins appear at random intervals.
- Replace the checkered background with an image.
- Player and Coin share a lot of commonalities. Create a parent class that both of these classes extend from to reduce code duplication.
- Make a special coin that looks different and is worth more points.
- End or restart the game when all coins are collected, or when a certain score is reached.
- Decide what winning means, then redraw the whole canvas with a celebration graphic when you win the game.
- Add a game clock.
  - Could count up or down.
  - Could replace the score or be in addition to the score.
  - Display it like the score.
- Keep track of high scores.
  - In a single play session.
  - Or across all sessions by reading/writing to a file.
- Allow the player to wrap around the edges of the board.

## ![Black Diamond](images/black-diamond.png) Advanced

- Add obstacles to block player movement.
- Add an object type that reduces your score when touched. Or maybe it ends the game.
- Make an object type that moves around on its own. Could be like the ghosts from pacman.
- Add sounds.
  - When a player moves, or picks up coins.
  - A constant sound track.
  - A sound that plays when you first open the game.
- Implement delta movements to only allow players to move one tile per tick. 
  - Can play around with the tick rate when developing this.
  - React to both pressed and released.
  - Can enable diagonal movements.
  - Fixes the issue caused by holding down a key, and makes for a more responsive experience.
- Make the total game area larger than the portion of that grid we see in the game window. 
  - So maybe the viewport moves as the player approaches an edge.
  - Or maybe the player stays in the middle and the whole viewport moves with the player whenever the player moves.
- Think about other keyboard keys that might perform some other action.
  - Can be as simple as changing some colors in the game.
  - Or maybe you've got health potions to restore player health.
- Add more scoreboard/HUD elements.
  - Maybe move this off of the game board itself, to some designated area on the canvas. I recommend still using just the single JPanel if you want to do this.
- Eliminate the grid concept altogether and use pixel positions instead.

## ![Double Black Diamond](images/double-black-diamond.png) Expert

To dive even deeper into developing your Java 2D game, I recommend checking out this series of tutorials for guidance and inspiration: https://zetcode.com/javagames/
