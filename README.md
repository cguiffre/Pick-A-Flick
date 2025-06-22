# Pick-A-Flick

A small browser game for ranking movies through head-to-head battles. The logic is contained in a single HTML file.

## How to use
1. Open `Movie Battle.html` in any modern browser.
2. Create a new battle or select an existing one.
3. Choose a genre and click **Continue Battle**.
4. Click the movie poster you prefer to record your choice. Rankings update automatically.
5. Use **View Rankings** to see your movie rankings for the current battle.

## Features
- Fetches movie data from TMDb using a demo API key.
- Multiple battles can be created and saved in your browser's local storage.
- Random movies are shown from the selected genre and cached to reduce API calls.
- Keeps stats on battles, ties and skipped matches.

## How the code works
- HTML, CSS and JavaScript are combined in `Movie Battle.html`.
- Movies are requested from TMDb by genre, cached, then displayed two at a time.
- User choices are tracked in local storage to rank movies within a battle.
- Rankings and battle data persist locally so you can continue later.

## Notes
This project only uses client side code. Simply open the HTML file locally; no server setup or build step is required.
