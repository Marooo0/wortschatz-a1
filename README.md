# Wortschatz A1

A vocabulary trainer for Netzwerk neu A1, with flashcards, article and plural review, picture clues, and German pronunciation audio.

## Open the trainer

https://marooo0.github.io/wortschatz-a1/

Hosted with GitHub Pages. The repository and website are public. Your learning progress is stored locally in your browser.

## Run locally

Keep `index.html` and all `pronunciation-*.json` files together. Run `python -m http.server 8000 --bind 127.0.0.1` from this folder and open `http://127.0.0.1:8000`.

The page loads without waiting for the audio library. Audio is downloaded in small groups as needed and cached in a bounded in-memory cache. The original offline single-file export is separate from this web version.
