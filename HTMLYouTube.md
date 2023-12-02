# HTML YouTube Videos
#### The easiest way to play videos in HTML, is to use YouTube.

## Struggling with Video Formats?
#### Converting videos to different formats can be difficult and time-consuming.
#### An easier solution is to let YouTube play the videos in your web page.

## YouTube Video Id:
#### YouTube will display an id (like tgbNymZ7vqY), when you save (or play) a video.
#### You can use this id, and refer to your video in the HTML code.

## Playing a YouTube Video in HTML:
#### To play your video on a web page, do the following:
- Upload the video to YouTube
- Take a note of the video id
- Define an &lt;iframe&gt; element in your web page
- Let the src attribute point to the video URL
- Use the width and height attributes to specify the dimension of the player
- Add any other parameters to the URL (see below)

### Example:
```html
<iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY">
</iframe>
```

## YouTube Autoplay + Mute:
#### You can let your video start playing automatically when a user visits the page, by adding autoplay=1 to the YouTube URL. However, automatically starting a video is annoying for your visitors!
#### Add mute=1 after autoplay=1 to let your video start playing automatically (but muted).

### YouTube - Autoplay + Muted:
```html
<iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY?autoplay=1&mute=1">
</iframe>
```

## YouTube Playlist:
#### A comma separated list of videos to play (in addition to the original URL).

## YouTube Loop:
#### Add loop=1 to let your video loop forever.
#### Value 0 (default): The video will play only once.
#### Value 1: The video will loop (forever).

### YouTube - Loop:
```html
<iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY?playlist=tgbNymZ7vqY&loop=1">
</iframe>
```

## YouTube Controls:
#### Add controls=0 to not display controls in the video player.
#### Value 0: Player controls does not display.
#### Value 1 (default): Player controls display.

### YouTube - Controls:
```html
<iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY?controls=0">
</iframe>
```







