# Date Night Box Office

A single-file date night idea generator. Filter by mood, budget, and setting, then pull a ticket for a specific, real activity — not just "go to dinner."

## Run it

No build step, no dependencies. Just open `index.html` in a browser, or serve it locally:

```
python3 -m http.server -d date-night-generator 8000
```

Then visit `http://localhost:8000`.

## Features

- 36 curated date ideas, each tagged by mood (cozy, romantic, playful, adventurous, cultured), budget ($ / $$ / $$$), and setting (indoor/outdoor/either)
- Filter chips narrow the pool before you pull a ticket
- "Pull a Ticket" draws a random matching idea and avoids repeating the last one
- Star a ticket to save it — saved tickets persist in the browser's local storage
