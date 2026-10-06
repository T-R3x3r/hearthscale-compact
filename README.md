# Compact for Hearthscale

A denser Hearthscale: smaller corners, tighter spacing and smaller type.

Compact is a reference theme. It sets only shape, space and type tokens and has no
class rules, so the glass, the depth, the motion and every colourway stay as they are.
Read `theme.css` to see how little a theme needs to change the feel of the whole app:
one value, `--space`, sets the density, because every inset, gap and size in
Hearthscale is a count of it. Three row tokens keep the rows of a conversation list
on whole pixels.

Compact is the first worked example of the theme guide in Hearthscale's developer
documentation, [Examples: Compact and Cupertino](https://hearthscale.com/docs/developers/themes/examples).

## Install

1. Copy this folder into your themes folder. In Hearthscale, open
   **Settings > Appearance > Themes folder**. Its `manifest.json` must sit directly
   inside `themes/compact/`.
2. Select **Compact** in the Theme picker. A colourway you wear keeps working on top.

## Change it

Clone this repository anywhere and start Hearthscale's development desktop from a
source checkout with `HEARTHSCALE_DEV_THEME` naming the clone. The development desktop
lists the folder as Compact, whatever the folder is called, and applies each save of
`theme.css` at once. See [Make a theme](https://hearthscale.com/docs/developers/themes#develop).
