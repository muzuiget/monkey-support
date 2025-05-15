# Docs

## Settings

### Type

Two types are supported:

* `Page Style` Execute CSS code.
* `Page Script` Execute JavaScript code.

When `None` is selected, the code will not executed, equivalent to a draft or disabled status.

### Urls

URL patterns to execute the code automatically.

The format is [Match Patterns](https://developer.mozilla.org/zh-CN/docs/Mozilla/Add-ons/WebExtensions/Match_patterns), use `*` to represent zero or more characters, and one pattern per line.

But the following restrictions are added:

* Not supports the special pattern `<all_urls>`.
* `scheme` can only be `http` or `https`.

When no URL is matched, a clickable button is displayed on the extension popup page, and the user can click the button to execute the code manually.

