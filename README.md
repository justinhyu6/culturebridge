# Culture Bridge globe

Interactive globe for the Learning Bridges WordPress hero. Country labels use the site navy, cream, and gold palette, with overlap avoidance. Avatars open profile cards. The sphere fits the shorter side of the embed and has no atmosphere glow.

## Run locally on Windows

Open PowerShell and run:

```powershell
cd C:\Users\email\OneDrive\Documents\learningbridge\culturebridge-pages
python -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000/ in your browser. Press Ctrl+C in PowerShell to stop the server. Refresh the browser after editing index.html.

## Publish

Commit and push changes to main. GitHub Pages publishes from the repository root:
https://justinhyu6.github.io/culturebridge/

The WordPress iframe automatically loads the published version. Its dimensions come from the WordPress hero CSS; the globe fills its shorter side while keeping the whole sphere visible.
