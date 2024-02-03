# PhotoEditor
Photo Editor.
Second level (version 0.2).
The work of the editor is based on the principle of pixel image processing. The change takes place in the "canvas".

It consists of three main blocks:
1.Image color redo block
2.Block for redacting the image size 
3.Block for redacting the image location.

Functionality is realized:
- histogram, with the ability to switch from black and white to color
- file upload
- result saving
- reset all settings
- viewing the result of change (works only in color redo mode)
- image viewing: zooming in, zooming out and moving around
- zoom display when zooming

:( Errors detected during testing  :(-->
- Number field on the "Color" panel does not work correctly. Changes only when changing shooters.
- The width of the "Control view" field does not work correctly.  Especially when loading large images.
- The "Zoom+Move" function works incorrectly after performing the "Resize+Rotate" function. The picture is blended.  

Improve
- Zoom display.
- Connection between "Zoom" and "Move"....


