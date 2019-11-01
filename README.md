# ChromeTile

This is basically the excellent extension [Tiling Window Manager for ChromeOS](https://chrome.google.com/webstore/detail/tiling-window-manager-for/aikaaejchodabfpkipfonnekofgepakh) but with a small modification that I made which adds the ability to shrink or expand the margins on the fly, via keyboard shortcuts. 

I did this by adding a couple of new commands to the `manifest.json` file and then implementing them in the `background.js` script, with a new function `adjustMargin`.

