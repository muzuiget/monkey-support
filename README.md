# Wildmonkey

[中文](./README.zh.md)

Lightweight userscript manager.

## Features

* Lightweight.
* Supports execute userscripts automatically and manually.
* Supports two types of userscripts, JavaScript and CSS.
* Supports all Web Extension browsers, including mobile browsers.

## FAQ

**Is this a replacement for Greasemoneky-like extensions?**

No, it does not support the non-standard JavaScript features used by such extensions, the functions which the name starts with `GM_`.

**Why develop this extension?**

In order to execute simple userscripts on mobile browsers, existing Greasemoneky-like extensions are not optimized for mobile browsers.

## Tutorial

After installation, by default two userscripts are generated for example:

* Use CSS to change the body font to green.
* Use JavaScript to format the JSON text.

You can test these two example userscripts at <https://httpbin.org/headers>.

## Userscript

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

## Feedback

Please use the Issues system of this repository.

## Changelog

### v0.19.1 / 2024-06-25

* Update build configurations.

### v0.19.0 / 2024-06-23

* Replace React with Preact.

### v0.18.0 / 2024-06-03

* Update extension user interface.
* Update to React 18.3.1.

### v0.17.1 / 2024-04-20

* Compatible with Firefox for Android.

### v0.17.0 / 2024-04-16

* Some code refactoring.

### v0.16.2 / 2024-04-08

* Some code refactoring.

### v0.16.1 / 2024-01-06

* Some code refactoring.

### v0.16.0 / 2024-01-03

* Some code refactoring.

### v0.15.0 / 2023-12-28

* Update build configurations.

### v0.14.0 / 2023-10-03

* Add support for Orion browser.

### v0.13.8 / 2023-08-12

* Update build configurations.

### v0.13.7 / 2023-07-08

* Update build configurations.

### v0.13.6 / 2023-06-06

* Update build configurations.

### v0.13.5 / 2023-05-17

* Update build configurations.

### v0.13.4 / 2023-03-18

* Update build configurations.

### v0.13.3 / 2023-02-12

* Update build configurations.

### v0.13.2 / 2023-01-10

* Reduce the icon file size.

### v0.13.1 / 2022-12-28

* Update build configurations.

### v0.13.0 / 2022-12-13

* Cleanup Manifest V2 compatible code.

### v0.12.0 / 2022-12-11

* Upgrade to Manifest V3.

### v0.11.0 / 2022-12-09

* Refactory UI component code.

### v0.10.0 / 2022-12-08

* Refactory UI component code.

### v0.9.0 / 2022-11-29

* Improve some UI component styles.

### v0.8.0 / 2022-11-24

* Improve some UI component styles.
* Replace the icons with Material Symbols.

### v0.7.0 / 2022-11-19

* Refactory for migrating to Manifest V3.

### v0.6.0 / 2022-09-20

* Update build configurations.

### v0.5.1 / 2022-07-31

* Update build configurations.

### v0.5.0 / 2022-06-20

* Upgrade to React 18.

### v0.4.0 / 2022-06-12

* Update build configurations.

### v0.3.0 / 2022-06-11

* Update build configurations.

### v0.2.1 / 2022-06-01

* Update build configurations.

### v0.2.0 / 2022-05-24

* Improve url pattern matching algorithm.
* Update build configurations.

### v0.1.1 / 2022-03-14

* Update build configurations.

### v0.1.0 / 2022-01-02

* First publish release version.
