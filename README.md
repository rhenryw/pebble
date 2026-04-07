# pebble
A web proxy that can be run anywhere (local, `data:` link, html file)

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
```

Styling
---

You have to do `div` and `iframe`

```html
<html>
  <head>
    <script src="https://cdn.jsdelivr.net/gh/rhenryw/pebble@main/src/pebble.min.js"></script>
    <style>
      html, body {
        margin: 0;
        padding: 0;
        width: 100%;
        height: 100%;
        overflow: hidden;
      }

      body > div {
        width: 100% !important;
        height: 100% !important;
        display: block !important;
      }

      iframe {
        border: none;
        width: 100%;
        height: 100%;
        display: block; 
      }
    </style>
  </head>
  <body>
    <p eg-url="https://example.com"></p>
  </body>
</html>
```


Why `eg`?
 > Because it's inconspicuous and probably nothing else has taken it. Also it was called EasyGame before (it used to only load gamedistro games)


TODO
---

- [x] Basic implementation

- [ ] Custom logic (non-sandstone)

- [ ] World domination
