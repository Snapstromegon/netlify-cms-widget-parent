# Netlify CMS Widget Parent

A Netlify CMS widget to select directory parent for an entry

## Usage

Example for using in an HTML file

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Content Manager</title>
  </head>
  <body>
    <script src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>
    <script src="https://unpkg.com/netlify-cms@^2.0.0/dist/netlify-cms.js"></script>
    <script src="https://unpkg.com/@netlify/netlify-cms-widget-parent@^1.0.0/dist/netlify-cms-widget-parent.js"></script>
    <script>
      const parentWidget = window.NetlifyCmsWidgetParent;
      CMS.registerWidget('parent', parentWidget.control, parentWidget.preview);
    </script>
  </body>
</html>
```
