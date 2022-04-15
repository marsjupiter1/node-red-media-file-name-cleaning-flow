# node-red-media-file-name-cleaning-flow

This node-red flow is a demonstration of using node-red to iterate a directory tree and rename files according to some rules.
Specifically it's looking for filenames that do not conform with:

https://kodi.wiki/view/Naming_video_files/TV_shows#Episode_Groups

and rather ruthlessly and crudely cleaning and renaming them.
the actual rename is NOT connected and currently it only deals with folders under a folder called "tv seasons"
It will output the actions it would intend to take.
Seems to work with both windows11 and linux.

It should be easy enough to extend to other bad file patterns.

