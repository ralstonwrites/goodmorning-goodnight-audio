# GoodMorning/GoodNight

Five-track static EP player and audio files, ready for GitHub Pages.

- Place `01.mp3` through `05.mp3` inside the `audio/` directory.
- Edit the `TRACKS` list in `index.html` to enter the real song titles.
- Publish from branch `main`, folder `/ (root)` under Settings > Pages.
- GitHub Pages automatically serves this site's MP3s via native HTML5 audio.
- For the Neocities mirror, replace `YOUR-GITHUB-USERNAME` in its copy of `index.html`.

Track playback advances on the real `ended` event, not a timer.
