# ScreenFork

Sketchapp plugin that exports screen and their variants based on the layer prefix.

![variant_1](https://github.com/screenfork/ScreenFork/blob/master/images/variant_1.png)
![variant_2](https://github.com/screenfork/ScreenFork/blob/master/images/variant_2.png)

## How it works

* To create a fork of a given Artboard add “&” prefix to any layer, group or symbol.
* Plugin exports only Artboards that are marked as exportable in Sketch.
* You can scale any scren fork by adding “Size” value.
* Use “Suffix” to add custom endings for scaled forks.
* Set export format as you do now by choosing it from a dropdown (works only with .png and .jpg).
* To export to a different folder add a path in the Artboard name.
* Pages or Artboards that have a prefix of “-“ are ingored during the export.

![exportable](https://github.com/screenfork/ScreenFork/blob/master/images/exportable.png)

## Name conventions:
* {Page}-{ArtboardName}.png or .jpg
* {Page}-{ArtboardName}-{Fork}.png or .jpg
* Spaces are changed to “-“

## Shortcuts

![shortcuts](https://github.com/screenfork/ScreenFork/blob/master/images/shortcuts.png)