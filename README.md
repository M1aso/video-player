# Video Player Sample

This repository provides a minimal example of using the [Plyr](https://github.com/sampotts/plyr) library to play an MP4 file. It is entirely static so it can be deployed to GitHub Pages.

## Files

- **index.html** – HTML page with the Plyr player.
- **video.json** – Configuration file containing the video URL, poster image and autoplay flag.

## Running locally

Open `index.html` in your browser or serve the directory with any static file server, e.g.

```bash
npx serve .
```

## Deploying to GitHub Pages

1. Commit these files to the main branch of your repository.
2. Enable GitHub Pages in the repository settings using the main branch.
3. Visit the published site to see the video player in action.

You can change the URLs in `video.json` to point to your own MP4 and poster image.
