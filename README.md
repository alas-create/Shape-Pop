# Shape Pop

A tap-to-smash arcade game. Shapes fall from the top of the screen. Tap them before they reach the bottom.

## How to play

- Tap or click shapes to pop them.
- Each shape has a point value: circle 1, square 2, triangle 3, diamond 4, star 5.
- Quick taps in a row build a combo. Every 5 hits raises the multiplier, up to 5×.
- Bombs fall too. Popping a bomb costs a life.
- Letting a normal shape fall off the bottom also costs a life.
- You start with 3 lives. The game speeds up every 20 seconds.

Desktop: press Space or Enter to start or restart.

Your best score is stored in the browser's localStorage.

## Run it

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Tech

Single HTML file with inline CSS and JavaScript, using the Canvas 2D API. The font is Fredoka from Google Fonts.

## License

MIT
