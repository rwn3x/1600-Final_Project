# HTML Video
#### The HTML &lt;video&gt; element is used to show a video on a web page.

## The HTML &lt;video&gt; Element
#### To show a video in HTML, use the &lt;video&gt; element:

### Example:
```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```

## How it Works
#### The controls attribute adds video controls, like play, pause, and volume.
#### It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.
#### The &lt;source&gt; element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.
#### The text between the &lt;video&gt; and &lt;/video&gt; tags will only be displayed in browsers that do not support the &lt;video&gt; element.

## HTML &lt;video&gt; Autoplay
#### To start a video automatically, use the autoplay attribute:

### Example:
```html
<video width="320" height="240" autoplay>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
```
#### Note: Chromium browsers do not allow autoplay in most cases. However, muted autoplay is always allowed.
#### Add muted after autoplay to let your video start playing automatically (but muted):

### Example:
```html
<video width="320" height="240" autoplay muted>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
```

## HTML Video Formats
#### There are three supported video formats: MP4, WebM, and Ogg. The browser support for the different formats is:
| Browser | MP4 | WEBM | Ogg |
| ------ | ----- | ------ | ----- |
| Edge | YES | YES | YES |
| Chrome | YES | YES | YES |
| Firefox | YES | YES | YES |
| Safari | YES | YES | NO |
| Opera | YES | YES | YES |

## HTML Video - Media Types
| File Format | Media Type |
| ------- | ------ | 
| MP4 | video/mp4 | 
| WebM | video/webm |
| Ogg | video/ogg |

## HTML Video - Methods, Properties, and Events
#### The HTML DOM defines methods, properties, and events for the <video> element.
#### This allows you to load, play, and pause videos, as well as setting duration and volume.
#### There are also DOM events that can notify you when a video begins to play, is paused, etc.

## HTML Video Tags
| Tag | Description |
| ------- | ------ | 
| &lt;video&gt; | Defines a video or movie | 
| &lt;source&gt; | Defines multiple media resources for media elements, such as &lt;video&gt; and &lt;audio&gt; |
| &lt;track&gt; | Defines text tracks in media players |


