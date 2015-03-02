# fix_pyuic
Fix pyuic converted PyQT design files, add a main and make executable.

I use pyuic4, and it creates a skeleton class with all the correct parent/child objects, but it doesn't go all the way and make an executable demo. This script does just that. If you're using the designer and hit CTRL-R to see the preview, it's basically that preview, but now you can review it from the same class you'll later be inheriting from.
