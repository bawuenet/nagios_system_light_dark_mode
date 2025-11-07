# Nagios Light/Dark Theme

This is a modification of the Nagios 4x default `exfoliation` theme. 
It does support light as well as dark mode and will switch based on the CSS media selector `prefers-color-scheme` which is browser controlled.

## Modifications

 - Instead of hardcoding color codes all over the place, they are now centrally defined as
   [CSS custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/--*) in common.css
 - No modification of the light theme.
 - Dark theme with new colors.

## Installation

Replace the existing `html/stylesheets` directory contents of your Nagios Core 4.x installation
with the contents of the `stylesheets` subfolder from this repo.

## License status
The `exfoliation` theme is shipped with Nagios Core which is GPLv2 licensed. 
The `exfoliation` theme itself however is labeled with an MIT-ish license.
