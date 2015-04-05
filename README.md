# Another `position: sticky` polyfill

Other polyfills either required extra libraries or made the CSS styling very rigid. This polyfill simply allows an element to be set as position sticky when a user scrolls below the element on the page - the most common use of the property value.

## Usage

Add:

```
<script src="sticky-polyfill.js" type="text/javascript"></script>
```

...and...


```
<link href="sticky-polyfill.css" rel="stylesheet">
```

...or just add the two rules to your own stylesheet.

## Support

This polyfill is currently only tested in Chrome 41, it uses CustomEvents, so versions older than IE9 will have issues. However, this is only used for debouncing the scroll event, so a fix could easily be applied to extend support further.

