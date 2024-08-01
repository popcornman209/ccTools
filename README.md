# ccTools
just a bunch of random computer craft libraries, and tools.

# git
### this is not mine, just modified to fit my usage. [original](http://www.computercraft.info/forums2/index.php?/topic/4072-github-repository-downloader/) (link broken due to cc's website being down)
git program for computer craft
### usage:
```
git <usr> <repo> <local path> <path in repo> <branch>
```
so for example to download all the files in this repo you would do
```
git popcornman209 computerCraft-git /
```
if you dont add the local path, it defaults to a downloads folder.

# spoofnet
this is a "fork" of rednet that allows you to spoof any computer id, so you can pretend to be a computer your not.
### usage
the usage should be nearly the same as rednet, just for many of the functions you have to add the id your spoofing. theres also a below example.
```
require("spoofnet")
open("top",2) -- 2 being the id your pretending to be
broadcast("im computer 2!",nil,2)
```
if some random error happends, its probably broken i didnt have time to test all of the functions.
