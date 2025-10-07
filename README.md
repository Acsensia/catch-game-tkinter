# catch-game-tkinter

A catch game developed on Python with the help of Tkinter library with the goal of getting a high mark for my uni assignment
- A game centered around getting a record score by playing multiple game rounds
- The player can move horizontally on the playing field and has to ‘catch’ certain entities falling from above with different speeds and in different directions by timing their movement and colliding with them at the right time, as otherwise the player's health value will decrease until it hits 0 and the game ends with the final score being saved into the in-game leaderboard; at the same time, some of the falling entities should be avoided as they cause the player to lose health upon being ‘caught’; some entities have an effect on the general flow of the game instead (for example, slowing down or speeding up movement of the player and the entities for a certain amount of time); the player can also choose between two movement distances (steps) - a small step and a larger one
- Three levels of difficulty with different initial values of player health, player and entity speeds, max numbers of entities et cetera
- A colored leaderboard that displays the date and time of the start of the game, the difficulty selected and the final score; serialized (stored locally on disk every time the game is closed and loaded into the game every time it is opened)
- Object-oriented approach applied
- An in-game manual present
