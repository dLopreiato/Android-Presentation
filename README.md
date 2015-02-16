# Android Presentation

This repository contains all of the materials for the presentation given on March 4th, 2015 at the Pennsylvania State
University's ACM meeting. For an outline of the presentation, don't forget to check out the outline.md file.

The presentation can be viewed [here](http://dlopreiato.github.io/Android-Presentation/).

Most of the media in the presentation was recorded by myself on my phone. As a note to myself, this is the ffmpeg
command that makes the video smaller and webm format.
```
ffmpeg -i PATH_TO_INPUT -vf scale=720:-1 PATH_TO_OUTPUT
```
This next one not only scales it, but also takes the first 4.5 seconds of the video.
```
ffmpeg -ss 00:00:00 -t 00:00:04.5 -i PATH_TO_INPUT -vf scale=720:-1 PATH_TO_OUTPUT
```