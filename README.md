TelePrompter (without remote control)
===

Forked from <https://github.com/manifestinteractive/teleprompter> and modified for easier localhosting and privacy. Huge thanks to @mrmidi for creating the original project!

- Removed remote control and all code using Google Analytics (which from my understanding was set up to track almost all interaction with the UI).
- Added support cleaning up pasted rich text from Apple's TextEdit.
- Overlay window and marker adapt size/position based on selected font size.
- Removed QR code plugin (as it is no longer needed).
- Removed promtr.tv related metadata from index.html

You can use this version locally by e.g. using the *Live Server* extension for Visual Studio Code, or run a simple webserver in your terminal.

For my personal workflow, I write markdown in Visual Studio Code, then copy text from the markdown preview and paste it into TelePrompter.

> Browser-based TelePrompter *without* Remote Control

![Screenshot](assets/img/social-card.png "Screenshot")
(screenshot shows remote control)

Features
---

- [X] Edit Text in Browser
- [X] Changes Saved Automatically
- [X] Handy Keyboard Shortcuts
- [X] Advanced Controls
- ~~[X] Remote Control Support~~
- [x] No tracking via Google Analytics


Keyboard Shortcuts
---

Key              | Alternatives                            | Description
:---------------:|:---------------------------------------:|:--------------------------
<kbd>↑</kbd>     |                                         | Increase Font Size
<kbd>↓</kbd>     |                                         | Decrease Font Size
<kbd>←</kbd>     | <kbd>PAGE UP</kbd>                      | Slow Down Teleprompter
<kbd>→</kbd>     | <kbd>PAGE DOWN</kbd>                    | Speed Up Teleprompter
<kbd>SPACE</kbd> | <kbd>B</kbd> <kbd>F5</kbd> <kbd>.</kbd> | Start / Stop Teleprompter
<kbd>ESC</kbd>   |                                         | Resets GUI

We also made an effort to make sure your text will be easy to read.   So if you are pasting text from a word document, we'll do some cleaning up to make the breaks flow more easily.

Get Updates
---

Follow this project on GitHub, or you can follow me on Twitter for updates: **[@mrmidi](http://twitter.com/mrmidi "Follow @mrmidi on Twitter")**

#### Do you use this TelePrompter?

[![Buy Me Coffee](https://peterschmalfeldt.com/buy-me-coffee.png)](https://www.paypal.me/manifestinteractive)
