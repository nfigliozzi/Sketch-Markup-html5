# Sketch-Markup-html5
Sketch To html is a proto sketch beta to save artboards tree (and folders) as a html.

# What's the idea?
Using the Artboard tree folder model, traduce it to the HTML DOM to acelerate the html markup work of a web.
I want to include this functionallitys:
  - Create htmls files (from artboards) and partials htmls code (from folders)
  - Assign a tag deppending the group folder name (or a element name in case). Give a hierarchy tag name if no "tag name".
  - Attach a class depending the element name, the element style and text style.
  - Create a html5 tag dictonary to asign names to folders and elements with a key shortcut. (to help in the sketch file orgnanization)
  
and sCSS ?!
  - Write Sass (or post css) file using the sketchfile folder tree, the hierchy and the classes assigned on the html.

# What's doing now?
By now, have two functions in the menu with the shorcuts.
  - "Set html tag" A dictonary of some HTML5 tags, that asign that tag to the current selection name.
  - "Export Html" that create an alert with a partial code (in case of folders) and a full code for Artboards (in progress).

Exports limitations:
  - Assign tag name, doesnt recognize if are the corrects.
  - Assign clases only from the name, didn't check element style.
  - Improvements in the UI implementation cooming soon.
