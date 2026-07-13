# ao3-light-dark-mode-shifting-skin
A mashup of a bunch of different site skins, culminating in this monstrosity that works nicely for me.

## Instructions
There are four skins in this system, each play a significant role in making this work across devices.
The main one, the one that is going to be active, is Base Code. This one is the base of all the other skins, setting up styling, fonts, sizes, shaping. It hides buttons, adds scrolling, and has three parent skins.

When creating this skin you need to scroll down to advanced, hit more, and add three parent skins. The order doesn't matter. 1. Light Mode, 2. Dark Mode, and 3. Mobile Fix. Update the skin.

Final step: hit use. 

Light Mode, Dark Mode, and Mobile Fix all use the "Media" section of advanced.

- Light Mode: Scroll on the media checkbox list to find "(prefers-color-scheme: Light)". Select that box, hit update.
- Dark Mode: Scroll on the media section to find "(prefers-color-scheme: Dark)". Select it.
- Mobile Fix: Scroll on the media section to find "only screen and (max-width: 42em)". Hit that checkbox. 

What this does is it ensures that these skins are only activated when certain criteria is met. The colour scheme one is fairly self explanatory: it uses the browser's theme to determine which one to use. The width one takes into account the dimensions of the browser, this means that shrinking the width of the browser on desktop will activate mobile mode. Tablet screens may be fucked up but yknow what that's a problem for future me. 
