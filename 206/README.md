# Breakout // Arcade Lab

A standalone Breakout game with an optional Q-learning AI paddle pilot. No build step or dependencies are required.

## Play

Open `index.html` in a modern web browser, then select **Start game**. The AI pilot can be enabled at any time with the **AI pilot** button.

## Controls

- **Move the paddle:** Left/Right arrow keys, `A`/`D`, or move the pointer over the playfield.
- **Pause or resume:** `Space` or the game button.
- **Touch:** Use the on-screen arrow buttons on small screens.
- **Reset:** Select **Reset** to start a new game.

## AI pilot

The optional pilot uses a small Q-learning model to choose paddle movements based on the ball's predicted landing position and the paddle's position. It learns from catches, brick hits, and missed balls. The model is saved in this browser's local storage, so learning can persist between visits in the same browser.

The game and AI run locally in the browser; there is no server or external service.
