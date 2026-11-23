# Music & Creation

To add a work, upload a web-ready audio file (such as an MP3) into this folder. In `misc.html`, replace the placeholder in `#music-works` with an entry like this. Add another article for each piece; optional credits or links to a score can go after the audio player.

```html
<article class="section">
  <h3>Title of the piece</h3>
  <audio controls preload="none" style="max-width: 100%" aria-label="Listen to Title of the piece">
    <source src="music/your-piece.mp3" type="audio/mpeg">
    Your browser does not support audio playback.
  </audio>
  <p><a href="music/your-piece.mp3">Download the MP3</a></p>
</article>
```

Replace both example paths and both instances of the example title. For a recording hosted elsewhere, you can link to it instead of uploading a copy. Anything uploaded to this public repository is public.
