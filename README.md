# I Can Guess Your Card

A simple browser-based card magic trick built with pure HTML, CSS and JavaScript.

Think of a card, follow three quick steps, and the application will correctly identify the card you selected.

No server, no database, no external libraries, and no images are required.

## Live Demo

🎴 Try it now:

**https://krystomasz.github.io/three-step-card-trick/**

## How It Works

The application uses a classic mathematical card trick based on:

- A 24-card deck
- Three rounds of card distribution
- User selection of the pile containing the chosen card
- A deterministic card positioning algorithm

After three selections, the chosen card is always located in a known position and can therefore be revealed.

## Features

- Single-file application
- Pure HTML, CSS and JavaScript
- No dependencies
- No build process
- Works offline
- Responsive layout
- Unicode card symbols (♠ ♥ ♦ ♣)
- Can be hosted on GitHub Pages

## Deck

The game uses a 24-card deck:

| Rank | Suit |
|--------|--------|
| A | ♠ ♦ ♣ ♥ |
| K | ♠ ♦ ♣ ♥ |
| Q | ♠ ♦ ♣ ♥ |
| J | ♠ ♦ ♣ ♥ |
| 10 | ♠ ♦ ♣ ♥ |
| 9 | ♠ ♦ ♣ ♥ |

Total cards: **24**

## Running Locally

Simply open:

```text
index.html
```

in any modern web browser.

No web server is required.

## GitHub Pages Deployment

1. Create a new public repository.
2. Upload `index.html`.
3. Open:

   Settings → Pages

4. Configure:

```text
Source: Deploy from a branch
Branch: main
Folder: /(root)
```

5. Save.

Your game will be available at:

```text
https://your-username.github.io/repository-name/
```

## Browser Compatibility

Tested with:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

Any modern browser with ES6 support should work correctly.

## Project Structure

```text
.
└── index.html
```

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript (ES6)

## License

This project is released under the MIT License.

Feel free to use, modify and distribute it.

## Author

Created as a modern implementation of a classic card prediction trick using only web technologies.
