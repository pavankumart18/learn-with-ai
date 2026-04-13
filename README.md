# Course Atlas Site

This folder contains the built static site for the lecture knowledge base.

## Files

- `index.html` - homepage with lecture grid, cross-video concept graph, and process section
- `video.html` - per-video study page
- `data.js` - embedded site data for videos, concepts, transcripts, quizzes, and study materials
- `assets/` - local images used by the site

## Run

Open `index.html` in a browser to use the site.

## Notes

- Sketchnote images and thumbnails are stored inside `assets/`
- The site still uses online resources for fonts, D3, and YouTube playback
- `data.js` still contains some legacy audio paths, but the current UI does not use the local audio player
