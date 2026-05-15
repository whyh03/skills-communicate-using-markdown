# Daily Learning
## Morning planning
- [ ] Check out the [github blog](https://github.biog/) for topic ideas.
- [ ] Learn about [Github Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first biog post into an actual webpage.
## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://wwww.ffmpeg.org)
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
