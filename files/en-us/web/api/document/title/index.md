---
title: Document.title
slug: Web/API/Document/title
tags:
  - API
  - Command API
  - Document
  - HTML DOM
  - NeedsSpecTable
  - Property
  - Reference
browser-compat: api.Document.title
---
{{APIRef("DOM")}}

The **`document.title`** property gets or sets the current title of the document.
When present, it defaults to the value of the [<title>](/en-US/docs/Web/HTML/Element/title).

## Value

A string containing the _document_'s title. If the title was overridden by setting `document.title`, it contains that value. Otherwise, it contains the title specified in the markup (see the [Notes](#notes) below).

```js
document.title = newTitle;
```

`newTitle` is the new title of the document. The assignment
affects the return value of `document.title`, the title displayed for the
document (e.g. in the titlebar of the window or tab), and it also affects the DOM of the
document (e.g. the content of the `<title>` element in an HTML
document).

## Examples

```js
<!DOCTYPE html>
<html>
<head>
  <title>Hello World!</title>
</head>
<body>

  <script>
    alert(document.title); // displays "Hello World!"
    document.title = "Goodbye World!";
    alert(document.title); // displays "Goodbye World!"
  </script>

</body>
</html>
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
