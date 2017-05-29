# Rullo Clone

### Background

Rullo is a simple 1-player math game
[(demo here)](http://www.coolmath-games.com/0-rullo)
where the player's objective is to remove tiles from the board until
every single row and column sum up to their objective sum.

### Functionality and MVP

With this clone of Rullo, the minimum viable product (MVP) will achieve:

* Successfully randomized board with only one single solution
* Handle game logic in removing tiles from the game
* Have a quick demo to show the player how to play

For possible bonus/stretch goals, the product will:

* Utilize different randomization algorithms in order to change difficulty
* Allow for the user to edit board parameters to raise difficulty

### Wireframes

[Link to wireframes](docs/wireframes.pdf)

The wireframes above display the general outline of the board and the
on-hover effects to be used. On-hover of a tile, the objective sum will
instead display the current sum in order to aide the user.

### Architecture and Technologies

The project is initially planned to utilize the following:

- 'HTML5 Canvas' and an extra javascript library for display and rendering.
- Vanilla javascript to handle the game logic
- Webpack to bundle the file.

### Steps

(Note: Currently under HIR contract, so steps have no strict timeline)

#### Step 1

- Decide between the different available libraries (EaselJS, pixi.js,
  Three.js, and PlayCanvas).
- Get libraries working and make toggleable buttons/tiles.

#### Step 2

- Create random board generator.
  - Making sure that only a single solution exists
  - Making sure the board is smartly randomized to prevent obviously easy puzzles
- Create render for board

#### Step 3

- Handle game logic and user interface features.
- Make sure game is styled sufficiently

#### Step 4

- Add how-to-play demo/guide to game
- Implement scalable difficulty.
  - Allow users to change grid size
  - Allow users to change range of numbers for each tile.
