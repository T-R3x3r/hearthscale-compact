# Developing Compact

`README.md` is the text the Marketplace shows under **About** on the listing of Compact, so it is written for the people who install it. This file is for the people who work on it.

Compact is a reference theme. It sets only shape, space and type tokens and has no
class rules, so the glass, the depth, the motion and every colourway stay as they are.
Read `theme.css` to see how little a theme needs to change the feel of the whole app:
one value, `--space`, sets the density, because every inset, gap and size in
Hearthscale is a count of it. Three row tokens keep the rows of a conversation list
on whole pixels.

Compact is the first worked example of the theme guide in Hearthscale's developer
documentation, [Examples: Compact and Cupertino](https://hearthscale.com/docs/developers/themes/examples).

## Change it

Clone this repository anywhere and start Hearthscale's development desktop from a
source checkout with `HEARTHSCALE_DEV_THEME` naming the clone. The development desktop
lists the folder as Compact, whatever the folder is called, and applies each save of
`theme.css` at once. See [Make a theme](https://hearthscale.com/docs/developers/themes#develop).

## Releasing

A release is a GitHub release whose tag is the `version` in `manifest.json`, without
a `v`, with the archive that `hearthscale pack .` writes attached. See
[Publish to the Marketplace](https://hearthscale.com/docs/developers/publish).

## Licence

MIT. See `LICENSE`.
