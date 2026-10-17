# SafeDex

Project website for **Pushing Dexterity and Safety for In-Hand Object Pose Reaching That Works Remarkably Well**.

The site is a static GitHub Pages project. Open `index.html` directly or serve the repository with any static file server.

## Replacing media placeholders

The page marks every pending asset with a dashed placeholder and a suggested filename. Add final media under `static/media/`, then replace the corresponding placeholder block in `index.html` with an `<img>` or `<video>` element.

Suggested assets:

- `teaser.mp4` — headline demo reel
- `knife.mp4`, `lightbulb.mp4`, `rubber-duck.mp4`, `wineglass.mp4` — object demonstrations
- `method.png` — training and safety-filter pipeline
- `results.png` — performance/safety trade-off figure
- `applications.mp4` — long-horizon downstream tasks

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.
