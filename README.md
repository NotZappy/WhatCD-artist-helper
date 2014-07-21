# What.CD :: Artist Helper
This userscript is designed to make it easier to add artists and work with the artist list on torrent group pages. It features a bunch of tools, described below.

## The Tools
### Toggle Edit Tools
This is basically what was proposed by Pringo in [this thread](https://what.cd/forums.php?action=viewthread&threadid=158080). It hides alias IDs and delete links as well as the "Add Artist" box. There's also an option to do this automatically, available via a User Script Command in the GreaseMonkey menu (as "What.CD Artist Helper: Turn autotoggle of editing tools on/off").

### Float the "Add Artists" box
I didn't know a better name, so I used what it technically does, it sets the "Add Artist" box to float: right. There's a bit more stylesheet stuff involved of course and you'll end up with the "Add Artist" box being the complete browser window height on the right and not affected by scrolling the page (it has its own scrollbar once there are enough artist boxes). Can be useful when you have a big torrent where you have to add a lot of artists based on the description or filelist. It allows you to do this without having to scroll up and down all the time.

### Add _ALL_ the artist boxes
A little link similar to [+] that will automatically add as many boxes as the site allows (100).
