# Flapcaster

Flapcaster is a minimalist Flappy Bird inspired game built with HTML5 canvas and the Farcaster FArcade SDK. Fly the alien through gaps in the obstacles and try to survive as long as possible.

## Setup

1. Clone this repository or download its contents.
2. No build step is required because the game runs entirely in the browser.

## Running the Game

Open `index.html` with any modern web browser. You can double-click the file or serve the directory with a static file server and navigate to the page. Use the mouse or touch to flap and avoid crashing into obstacles.


## Cheat Codes

Click the **Enter Code** button at the top of the title screen to reveal a text box for entering cheats. While this field is open codes aren\'t triggered until you press **Submit** (or hit Enter). You can also type a secret code on your keyboard when the form is hidden. The button and form hide automatically once the game begins and reappear the next time the title is shown. When a valid code is submitted a short message will appear in the HUD.

Available codes:

- **GOLD** – turns the alien a shiny gold color.
- **ALIENP** – loads an alternate alien sprite.
- **RAINBOW** – applies a shifting rainbow mask to the alien.

More codes can be added by editing the `CHEATS` object inside `index.html`.

