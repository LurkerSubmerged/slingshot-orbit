# Slingshot Orbit

A one-button arcade game that runs in the browser. Orbit a planet, release to slingshot toward the next one, and see how far you can climb.

## Run

No install or build step. Open `slingshot_orbit_game.html` in any modern browser.

## How to play

- **Hold** (mouse, touch or `Space`) to attach to a planet whose gravity range you are in.
- **Release** to launch off the orbit in a straight line.
- Each new planet you attach to gives **+1 score**. Orbit and launch speed increase as your score grows.
- You crash if you hit a planet, leave the sides of the screen, or fall below the screen.

Your best score is stored in the browser (`localStorage`).

## Tech

Single self-contained HTML file: HTML, CSS and vanilla JavaScript on a `<canvas>`, with sound effects from the Web Audio API. No dependencies.

## Project structure

```
slingshot_orbit_game.html   # the whole game
README.md
```
