jacobmarshall-react-inline-svg
==============================

React Component to load and inline SVG images, allowing you to target and style SVGs using CSS.


Features
--------
- Easy to use, just add `InlineSVG` components
- Loads SVGs automatically using a `XMLHttpRequest`
- Loads each SVG exactly once, and caches them for repeated use
- Can preload SVGs in advance using `InlineSVG.cache`

Installation
------------

```
$ npm i --save jacobmarshall-react-inline-svg
```


Usage
-----

Include the component:
```html
<script src="https://unpkg.com/jacobmarshall-react-inline-svg@2.0/dist/react-inline-svg.js"></script>
```


Or...
```js
import InlineSVG from 'jacobmarshall-react-inline-svg';
```


Render an inline SVG:

```xml
<InlineSVG src="/path/to/your.svg" className="css-class" />
```


Pre-loading SVGs
----------------

```javascript
InlineSVG.cache.load("/path/to/your.svg");
```


Building from Source
--------------------

To re-build this after making changes in `src`, simply run:

```
$ gulp
```
