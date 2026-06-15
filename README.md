# songs

MP3 songs for the **Story Box** (Session 4) used as a **music player** —
same idea as the `stories` repo, but with music instead of stories.

## How to add a song
1. Add an `.mp3` file to this repo (in the root).
2. Turn on GitHub Pages: **Settings → Pages → Branch: `main`, folder: `/ (root)`**.
3. The robot lists files via the GitHub API and streams each one from
   `https://coolcorexix.github.io/songs/<file>.mp3`.

In the Arduino sketch, point these two lines here:
```cpp
const char* github_api_url   = "https://api.github.com/repos/coolcorexix/songs/contents/";
const String github_pages_base = "https://coolcorexix.github.io/songs/";
```

## ⚠️ Only add music you have the right to share
Please host only your **own recordings, royalty-free, or public-domain** tracks.
Don't upload copyrighted songs ripped from YouTube / streaming services — that
infringes copyright and breaks those services' terms.
