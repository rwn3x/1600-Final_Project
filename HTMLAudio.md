# HTML Audio
#### The HTML &lt;audio&gt; element is used to play an audio file on a web page.

## The HTML &lt;audio&gt; Element
#### To play an audio file in HTML, use the &lt;audio&gt; element:

### Example:
```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
```

## HTML Audio - How It Works
#### The controls attribute adds audio controls, like play, pause, and volume.
#### The &lt;source&gt; element allows you to specify alternative audio files which the browser may choose from. The browser will use the first recognized format.
#### The text between the &lt;audio&gt; and &lt;/audio&gt; tags will only be displayed in browsers that do not support the &lt;audio&gt; element.

## HTML &lt;audio&gt; Autoplay
#### To start an audio file automatically, use the autoplay attribute: 

### Example:
```html
<audio controls autoplay>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
```
#### Add muted after autoplay to let your audio file start playing automatically (but muted):

### Example:
```html
<audio controls autoplay muted>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
```

## HTML Audio Formats
#### There are three supported audio formats: MP3, WAV, and OGG. The browser support for the different formats is: 
| Browser | MP3 | WAV | OGG |
| ------ | ----- | ------ | ----- |
| Edge/IE | YES | YES | YES |
| Chrome | YES | YES | YES |
| Firefox | YES | YES | YES |
| Safari | YES | YES | NO |
| Opera | YES | YES | YES |

## HTML Audio - Media Types
| File Format | Media Type |
| ------ | ----- | 
| MP3 | audio/mpeg | 
| OGG | audio/ogg | 
| WAV | audio/wav | 

## HTML Audio - Methods, Properties, and Events
#### The HTML DOM defines methods, properties, and events for the &lt;audio&gt; element.
#### This allows you to load, play, and pause audios, as well as set duration and volume.
#### There are also DOM events that can notify you when an audio begins to play, is paused, etc.

## HTML Audio Tags

| Tag | Description |
| ------ | ----- | 
| &lt;audio&gt; | Defines sound content | 
| &lt;source&gt; | Defines multiple media resources for media elements, such as &lt;video&gt; and &lt;audio&gt; | 


