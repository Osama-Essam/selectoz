## SelectOz
  > V 1.1

### Description
JavaScript layer for select boxes

## Features
 * Multiple select
 * Keyboard events
 * Easy to style
 
## HTML
``` html 
<!-- select container -->
<select>
    <option>
    </option>
    ...
</select>

<script src='selectoz-plugin.js'></script>
<!--</body>-->
```

## CSS
``` html 
<link href='selectoz-style.css' rel='stylesheet'>
```

## JavaScript
```javascript
window.onload = function () {
    selectoz({
        icon: {
            focus: 'fa fa-chevron-up',
            blur: 'fa fa-chevron-down'
        }
    });
};
```
