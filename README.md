Shutdown Now! 2 is a simple bash script that shuts down your Linux or Mac as quickly as possible.

(Note: This is a statement of intention, not a legal claim.)

TL:DR - If you don't want to read all the instructions or if you just like figuring things out.
- Get the ShutdownNow2 script onto your desktop however you see fit to do so (legally).
- Right click -> "Run as a Program"

* The master branch is up-to-date.  Any other branches are experimental.

Enjoy my first official contribution to open source, 
~ b4t54ndw1ch

Now, for more words, what it is, how it works, why the hell, etc...

I. Shutdown Now! 2  
* Current release: ShutdownNow2

II. How to use this script:
* Copy this repo to your HDD.
* Move the ShutdownNow script onto your desktop 

To run the script for the first time:
* Right click -> "Run as a Program"

Your system should shutdown immediately

III. Shutting down your computer even faster:

Why this script exists and operates the way that it does:
* When I first started programming, I didn't get it: GUI vs CLI
* After a few years, I'm starting to get it.
* Using Pop!OS (my daily driver), it currently takes about 4 button clicks to shut my computer down.  This is something by which I cannot abide, but this is typical and likely started back with MS and Windows or something...don't quote me on that.
* I figured out that running 'shutdown now' in the CLI will do exactly that.  
- Note: The command 'shutdown' will delay the shutdown by 60 sec.
* My typical and personal favorite shutdown sequence is currently:
Super+T, UpArrow, Enter

...or if I've been using Terminal recently I'll do...
Super+T, shutdown now, Enter

* But sometimes I use the CLI quite a bit and I've gotten into 
reverse searching my 'shutdown now' command by using CTRL+R.  This isn't so bad, but...

...can I do something that is just a little faster and more predictable?

IV. Latest changes
Version 2
* Display 'goodbye' message added to script
* Renamed folder from 'sdn' to 'ShutdownNow' for clarity purposes
* Renamed bin file from sdnver(x) to ShutdownNow(x)

V. Upcoming changes:
- Todo: Make script activate with single or double left mouse click
- Todo: Add a button graphic
- Todo: Move ShutdownNow into launcher bar
- Todo: Add timestamp
