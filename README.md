# Culture Bridge globe

The globe displays anonymous country markers for videos listed in `videos.json`. Each entry has a country name, approximate country coordinates, an illustrated avatar file, and an array of Google Drive file IDs with each video’s width and height. Multiple IDs appear as selectable videos. Drive files must remain viewable by the public for the embedded player to work.

## Run locally on Windows

```powershell
cd C:\Users\email\OneDrive\Documents\learningbridge\culturebridge-pages
python -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000/ and press Ctrl+C in the terminal to stop. Refresh after changes.

Commit and push changes to `main` to publish through GitHub Pages at https://justinhyu6.github.io/culturebridge/.
