# pebble
A web proxy that can be run anywhere

Based off of [ading2210/sandstone](https://github.com/ading2210/sandstone/)

USAGE:

in `<head>`
```html
<script src="https://cdn.jsdelivr.net/gh/rhenryw/pebble@main/src/pebble.min.js"></script>
```

anywhere you want there to be an iframe
```html
<p eg-url="https://example.com"></p>
```

FULL EXAMPLE

```html
<!DOCTYPE html>
<html>
  <head>
    <script src="https://cdn.jsdelivr.net/gh/rhenryw/pebble@main/src/pebble.min.js"></script>
  </head>
  <body>
    <p eg-url="https://example.com"></p>
  </body>
</html>
