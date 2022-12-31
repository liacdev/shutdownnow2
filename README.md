Shutdown Now! is a simple bash script that shuts down your Linux or Mac as quickly as possible.

(Note: This is a statement of intention, not a legal claim.)

TL:DR - If you don't want to read all the instructions or if you just like figuring things out.
- Get the sdnver1 script into your home folder however you see fit to do so (legally).
- Run ./sdver1 in Terminal/CLI
- The master branch is up-to-date.  Any other branches are experimental.

Enjoy my first official contribution to open source, 
~ b4t54ndw1ch

Now, for more words, what it is, how it works, why the hell, etc...

I. Shutdown Now! 
* Current release: sdnver1

II. How to use this script:
* Copy this repo to your HDD.
* move the sdnv1 script into your home folder (you can ditch the folder and readme after you get the sdnver1 script)

To run the script for the first time:
* Open Terminal/CLI (Pop!OS allows the Super+T key combination, but there may be others.  I don't remember the Mac command). 
* Run the script by entering:
./sdnver1

Your system should shutdown immediately

III. Shutting down your computer even faster:
* Now that you've stored the command ./sdnver1 into terminal, you can search for it 
using CRTL+R and a few keystrokes.  The filename 'sdnver1' has a lot of quick key combos that will highlight in a reverse search: sdn, ver, dnv, er1, and nve.  
* When the CLI opens in the Home folder and the sdnver1 file is also in the home folder, 
then CTRL+R and any combination mentioned above should be able to call up the command
and quickly shut down yout computer.

IV. Why this script exists and operates the way that it does:
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

V. Upcoming changes:
* Display 'goodbye' message
* Display date and time