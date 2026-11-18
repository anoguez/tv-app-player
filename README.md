# Perrito TV player page

A single static page that hosts YouTube's official embedded player for Perrito TV on
LG webOS TVs. YouTube's player only plays inside a page with a real web address,
and the TV app runs from a local file, so it shows this page in a frame and
controls the player through messages.

The page contains no keys, tokens or user data. It only accepts commands from the
app that framed it, and only reports player state (playing/paused, time, errors).

Served by GitHub Pages at https://anoguez.github.io/tv-app-player/
