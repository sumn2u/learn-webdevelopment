# Media Elements

HTML media elements allow you to add audio and video content to your web pages.

To add audio content, you can use the `<audio>` element. The `src` attribute of the `<audio>` element specifies the URL of the audio file, and the `controls` attribute adds audio controls to the element, such as a play/pause button and a volume slider.

Here is an example of how to add an audio player to an HTML document:

```css
<audio src="/audio/song.mp3" controls></audio>
```

To add video content, you can use the `<video>` element. The `src` attribute of the `<video>` element specifies the URL of the video file, and the `controls` attribute adds video controls to the element, such as a play/pause button and a volume slider.

Here is an example of how to add a video player to an HTML document:

```css
<video src="/video/movie.mp4" controls></video>
```

Both the `<audio>` and `<video>` elements support various attributes that allow you to control the behavior and appearance of the media element, such as the `autoplay` attribute, which starts playing the media automatically, and the `loop` attribute, which causes the media to start over when it reaches the end.

Here is an example of how to use the `autoplay` and `loop` attributes:

```css
<audio src="/audio/song.mp3" controls autoplay loop></audio>
```

You can also use the `<source>` element inside the `<audio>` and `<video>` elements to specify multiple sources for the media, allowing the browser to choose the best source based on its availability and compatibility.

```bash
<audio controls>
  <source src="/audio/song.mp3" type="audio/mpeg">
  <source src="/audio/song.ogg" type="audio/ogg">
  Your browser does not support the audio element.
</audio>
```
