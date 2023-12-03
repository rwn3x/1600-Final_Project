# HTML Plug-ins
#### Plug-ins are computer programs that extend the standard functionality of the browser.

## Plug-ins:
#### Plug-ins were designed to be used for many different purposes:
- To run Java applets
- To run Microsoft ActiveX controls
- To display Flash movies
- To display maps
- To scan for viruses
- To verify a bank id

## The &lt;object&gt; Element:
#### The &lt;object&gt; element is supported by all browsers.
#### The &lt;object&gt; element defines an embedded object within an HTML document.
#### It was designed to embed plug-ins (like Java applets, PDF readers, and Flash Players) in web pages, but can also be used to include HTML in HTML:

### Example:
```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```

#### Or images if you like:

#### Example:
```html
<object data="audi.jpeg"></object>
```

## The &lt;embed&gt; Element:
#### The &lt;embed&gt; element is supported in all major browsers.
#### The &lt;embed&gt; element also defines an embedded object within an HTML document.
#### Web browsers have supported the &lt;embed&gt; element for a long time. However, it has not been a part of the HTML specification before HTML5.

#### Example:
```html
<embed src="audi.jpeg">
```

##### The &lt;embed&gt; element can also be used to include HTML in HTML:
#### Example:
```html
<embed width="100%" height="500px" src="snippet.html">
```
