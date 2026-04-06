# eledmunds15.github.io

Personal site for Ethan Edmunds.

## Editing content

All text, links, and data live in **`content.json`**. Edit that file to update any copy — `index.html` is the design shell and never needs to be touched.

## Previewing locally

Because `index.html` loads `content.json` via `fetch()`, you need a local server — opening the HTML file directly in a browser will block the request.

```bash
python3 -m http.server
```

Then open [http://localhost:8000](http://localhost:8000).
