# Change log

### v0.7.0

* Fix to work with underscore.js 1.5.1 (remove `_.bindAll` and use `.bind` where necessary).
* Listen for `mousedown` event instead of `click` when `clickToSelect` is enabled.

### v0.6.5

* Model views that represent a particular model are now reused between renders.