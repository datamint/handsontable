* make sure after react project is compiled, to change the paths to
* es/react-handsontable.mjs ->
* handsontable/handsontable/tmp
* this is necessary because handsontable makes npm packages from the builds.
* in order to ship this as a custom build, this change is necessary.