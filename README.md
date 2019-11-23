# obamenu
Obamenu 1.1.8

Obamenu is the grandfather of creating menues on Openbox. 

However, overtime it has languished at version 1.1.7, with no active development. In truth, there has been
very little need for development of this little script - yet time has not been kind. 

Standards have changed, and the once icon-filled menu has lanugished. This version will now include the default icons
if the other icons are not found.

As .desktop files are also used to control interaction with MIME types, obamenu ends up installing several copies of the same
icon. This version attempts to remove such duplicates (with varying success)

It also includes better support for programs that require complex starting paramaters, like GIMP 2.10, which is a flatpack
piece of software so wouldn't start using the old obamenu. This has been fixed by a re-working of the process
used to create menu items. 

This version is still under development, but the Master branch is stable and eminantly usable.
