# Aperture layout for corne, based on soundmonster

=How to install=

Add aperture as a corne keyboard keymap on your existing qmk firmware:

```
cd qmk_firmware/keyboards/crkbd/keymaps
git submodule add git@github.com:Edorka/qmk_crkbd_aperture.git aperture
```

QMK firmware for Corne keyboard inspired on Aperture laboratories (TM)

Features:

* Modern OLED support (many thanks to @drashna):
  * Proper orientation
  * Graphic layer indicator ↑ ↓
  * Graphic modifier indicator ⌘ ⇧ ⌥  ⌃
* Similar enough to the default keymap so you can easily port your custom keymap to it
* Mac-friendly (Command and Option on the thumbs)
* Vim-friendly (Esc, `:` and Ctrl on the thumbs)
* Full per-key RGB Matrix support out of the box (you still have to go through the nightmare of soldering yourself though 😉)
