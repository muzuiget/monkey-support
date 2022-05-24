Wildmonkey
==========

[中文](./README.zh.md)

Lightweight userscript manager.

Features
--------

* Lightweight.
* Supports execute userscripts automatically and manually.
* Supports two types of userscripts, JavaScript and CSS.
* Supports all Web Extension browsers, including mobile browsers.

FAQ
---

**Is this a replacement for Greasemoneky-like extensions?**

No, because it does not support the non-standard JavaScript features used by such extensions (aka GM API), part of GM API may be compatible with polyfill in the future.

**Why develop this extension?**

In order to execute simple userscripts on mobile browsers, existing Greasemoneky-like extensions are not optimized for mobile browsers.

Tutorial
--------

After installation, by default two user scripts are generated to execute on [https://www.example.com/]():

* Use JavaScript to change the title to `Hello World`.
* Use CSS to change the body font to green.

You can manage userscripts in the extension settings page.

Userscript
----------

TODO

Feedback
--------

Please use the Issues system of this repository.

Changelog
---------

### v0.2.0 / 2022-05-24

* Improve url pattern matching algorithm.
* Update build configurations.

### v0.1.1 / 2022-03-14

* Update build configurations.

### v0.1.0 / 2022-01-02

* First publish release version.
