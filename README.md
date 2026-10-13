# Neon Snake

LINK - https://claude.ai/artifact/FrvFhDnwbUJuR6e3MzqtHf 



Neon Snake is a version of the classic snake game that runs entirely in your browser. There is no server, no backend, no database and no API keys. The whole game is one file of HTML, CSS and JavaScript.

**Play it:** https://bennorani-cpu.github.io/neon-snake/

## Features

* **Four modes**

  * **Solo:** chase a high score with 3 lives.
  * **vs AI:** race a computer snake for the food. Choose Easy, Medium or Difficult.
  * **2 Players:** two people on one keyboard (WASD vs arrow keys), or two direction pads on a phone.
  * **AI Duel:** watch two computer snakes fight. Press any arrow key to take over.
* **3 lives** shown as hearts. After a crash you come back at length 4 and keep your score.
* **Five foods:** apple, banana, cherries, grapes and a rare watermelon, each worth different points and growth. There are also gold stars.
* **Power-ups:** Slow-mo, Ghost (pass through everything) and Double points.
* **Combos:** eat again within 3.5 seconds to raise the multiplier, up to x8.
* **Five maps:** Open Field, Arena, Pillars, Crossroads and Tunnels, with wrap-around edges or solid walls and obstacles.
* **Eight snake skins**, including animated Rainbow and striped Tiger.
* **Daily challenge:** a new goal every day, such as "Eat 5 bananas in one game" or "Beat the AI on Medium", with a day streak.
* **Music:** a deep/Afro house groove generated live in the browser. You can also load an audio file from your own device; it never leaves your browser.
* A tall 9:16 board, a neon synthwave background, particle effects and generated sound effects.

## Controls

|Action|Keyboard|Phone|
|-|-|-|
|Move (Solo, vs AI)|Arrow keys or WASD|Swipe or direction pad|
|Move (2 Players)|Player 1: WASD · Player 2: arrow keys|Each player gets a direction pad|
|Start or restart|Enter|Play button|
|Pause or resume|Space, P or Esc|Pause button|
|Mute sound effects|M|Sound button|

## Rules

* Hitting a wall, a block or your own tail costs a heart.
* In versus, hitting the other snake's body costs you a heart. A head-on crash costs both snakes a heart.
* In versus, the first snake to lose all 3 hearts loses. If the 3-minute clock runs out, the snake with more hearts wins, then the higher score.
* After a respawn you blink for 2 seconds and can pass through snakes.

## Run it locally

Download `index.html` and open it in any modern browser. Nothing needs to be installed or built.

## How it works

* **Graphics:** drawn on an HTML canvas. The board is 18 × 30 cells, and the snake slides smoothly between cells.
* **Sound and music:** created with the Web Audio API. No audio files are bundled.
* **AI snakes:** find paths to food with breadth-first search and check that they can still reach their own tail before committing. Higher levels also avoid the rival's head and skip food the rival will reach first.
* **Saved data:** best scores, settings, daily challenge progress and your streak are stored in your browser's local storage. They stay on your device.

## Credits

Built with Claude Code.

