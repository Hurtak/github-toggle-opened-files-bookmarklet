# Toggle opened/collapsed files in GitHub pull-request

Bookmarklet that:

- collapses files that are currently opened
- opens files that are currently collapsed

Useful for reviewing large PRs where you collapse files when clicking the reviewed button, and then you need them quickly un-collapsed to do some quick search. This utility will toggle all collapsed/un-collapsed files, you can do your search, and then you run it again to get back to original state.

<img src="preview.gif" alt="Bookmarklet preview" width="864" height="802" />

## Put inside your bookmarks

```js
javascript:[...document.querySelectorAll('[aria-label="Toggle diff contents"]')].forEach(_ => _.click())())
```
