# Traces of Deer in the Tarim Basin

A standalone visual research page presenting biological, archaeological, and visual evidence for deer in the Tarim Basin—and the limits of what that evidence proves.

The page has no build step or external code dependencies: its CSS and JavaScript are embedded, and responsive image files are stored in `photos/`.

## Download and view

### Download without Git

1. Open the repository on GitHub.
2. Select **Code**, then **Download ZIP**.
3. Extract the downloaded ZIP file.
4. Open `index.html` in a modern web browser.

Keep `index.html` and the `photos/` directory together. Moving the HTML file away from that directory will break its relative image links.

### Clone with Git

```sh
git clone https://github.com/The-One-Who-Speaks-and-Depicts/tarim-deer.git
cd tarim-deer
```

Then open `index.html` in a browser. No package installation or local server is required.

If a browser restricts features on pages opened directly from disk, serve the directory with any static file server. For example, with Python installed:

```sh
python3 -m http.server 8000
```

Visit `http://localhost:8000` in the browser.

The evidence index distinguishes observation, interpretation, and uncertainty. Unknown provenance or location information is intentionally marked rather than inferred.
