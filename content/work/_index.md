+++
title = "Work"
template = "section.html"
+++

A few audio samples, mostly from learning sound engineering. Two patterns are set up below — pick whichever fits a given piece:

**A short, finished track — self-hosted directly on this site.** Drop the file in `static/audio/`, then embed it with a plain HTML5 player (works with no JavaScript):

```html
<audio controls src="/audio/track-name.mp3"></audio>
```

<!-- <audio controls src="/audio/track-name.mp3"></audio> -->

**A longer mix or set — embedded from Mixcloud** instead of hosted here. Better for long-form audio: dedicated player, waveform, no repo bloat, no bandwidth cost. Get the embed code from the Mixcloud share menu and drop the iframe in:

```html
<iframe width="100%" height="120" src="https://www.mixcloud.com/widget/iframe/?feed=%2Fyourusername%2Fyour-mix-slug%2F" frameborder="0"></iframe>
```

<!--
<iframe width="100%" height="120" src="https://www.mixcloud.com/widget/iframe/?feed=%2Fyourusername%2Fyour-mix-slug%2F" frameborder="0"></iframe>
-->

Both examples above are commented out until there's real audio to link — uncomment and fill in the real path/URL when adding a piece.
