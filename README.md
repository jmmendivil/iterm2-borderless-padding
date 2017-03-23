# iterm2-borderless-padding

## Deprecation Warning

This [functionality](https://github.com/gnachman/iTerm2/pull/283) has now been [incorporated](https://github.com/gnachman/iTerm2/pull/316) into upstream iTerm.

Please use the latest iTerm instead of this repo, which will no longer be updated.

Note: Make sure [this bug](https://gitlab.com/gnachman/iterm2/issues/3568#note_24249237) has been fixed _(test with Monoid)_ before deprecate it.

## Info

This repo contains the patch file used to remove borders and add padding to iTerm2.

![iterm2-borderless-padding](http://i.imgur.com/QsMVfNq.png)

## Install

Simply run `install.sh VERTICAL_PADDING HORIZONTAL_PADDING`. In the screenshot above, I'm using `25` for both padding values.

The binary will be at `iTerm2/build/Development/iTerm2.app`, which you can then move to `~/Applications`.
