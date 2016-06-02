# ScreenFork

ScreenFork is the Sketchapp plugin that export screens and their variants based on Layer prefix.

* To create a fork of a given Artboard add “&” prefix to any layer, group or symbol.
* Plugin exports only Artboards that are marked as exportable in Sketch.
* You can scale any scren fork by adding “Size” value.
* Use “Suffix” to add custom endings for scaled forks.
* Set export format as you do now by choosing it from a dropdown (orks only with .png and .jpg).
* To export to a different folder add a path in the Artboard name.
* Pages or Artboards that have a prefix of “-“ are ingored during the export.

a) {Page}-{ArtboardName}.png or .jpg
b) {Page}-{ArtboardName}-{Fork}.png or .jpg
c) Spaces are changed to “-“