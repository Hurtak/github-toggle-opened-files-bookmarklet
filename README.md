# Toggle opened/collapsed files in GitHub pull-request

Bookmarklet that

- collapses files that are currently opened
- opens files that are currently collapsed

<img src="preview.gif" alt="Bookmarklet preview" width="864" height="802" />

## Put inside your bookmarks

```js
javascript:[...document.querySelectorAll('[aria-label="Toggle diff contents"]')].forEach(_ => _.click())())
```
