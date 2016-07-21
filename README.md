# HyperAmbient - A HyperTerm theme that responds to ambient light changes

![Demo](https://github.com/jamox/hyperambient/blob/master/hyperambient.gif)

Due to changing lightning conditions using just one color scheme rarely suffices. Especially when moving from indoors to sunny outdoors a dark color scheme that looked incredible inside is almost unreadable.
Thus the terminal color scheme should react to ambient light changes!

Let me introduce HyperAmbient - the HyperTerm theme that that changes the color scheme to fit the current ambient lighting conditions.

The theme toggles between [hyperterm-solarized-light](https://www.npmjs.com/package/hyperterm-solarized-light) and  [hyperterm-solarized-dark](https://www.npmjs.com/package/hyperterm-solarized-dark)

NOTE: Currently underlying implementation for accessing ambient light only works in OSX.

## How install

Install HyperTerm and add hyperambient to plugins in ~/.hyperterm.js.

## How to use

It automatically checks for ambient light changes and changes color shceme if neccesary - keep on using hyperterm for a while when ambient lightning condition change.

Should you want the changes to reflect immediately you'll need to make a Full Reload to all plugins (shift + cmd + R)

## TODO

- [x] Automatically change color scheme when lightning conditions changes
- [ ] Make themes configurable
- [ ] Make threshold configurable

