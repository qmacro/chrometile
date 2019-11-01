# ChromeTile

This is basically the excellent extension [Tiling Window Manager for ChromeOS](https://chrome.google.com/webstore/detail/tiling-window-manager-for/aikaaejchodabfpkipfonnekofgepakh) but with a small modification that I made which adds the ability to shrink or expand the margins on the fly, via keyboard shortcuts. 

I did this by adding a couple of new commands to the `manifest.json` file and then implementing them in the `background.js` script, with a new function `adjustMargin`.

## How to use

1. Clone this repository
1. In Chrome, goto the [Extensions](chrome://extensions) page
1. On that page, switch on Developer Mode
1. Then, on the same page, use the "Load Unpacked" feature to load the extension, selecting the location of the clone (select the actual directory itself, e.g. `chrometile`).

Then you're all set and can use the extension as normal (use the extension's options to configure the keyboard shortcuts). 

## Disclaimer

All the awesomeness of this extension is from the original author - please see the links in the extension's home page. 
