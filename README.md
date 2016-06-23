## Glacier
*Next generation WC3*

### What is this?
This repository houses all of the public-facing info for Glacier. It contains the maps that are published on Glacier, and the modules (dependencies) that those maps can use. The client downloads all of those files from this repo.

### What is Glacier?
Glacier is a WC3 suite that is built on top of SharpCraft. Essentially, it loads .dll's into the game. At a bigger picture, this means that map developers can leverage virtually any functionality that can be written in C#, the language SharpCraft and the .dll's are written in.

### What does it mean for me?
Map developers have long had to make maps with certain limitations: no control over networking, no filesystem or I/O, etc. That ends today. Glacier is a gaming client that manages maps (much like Steam), and sets the user up with the needed dependencies automatically. 

Maps will utilize amazing new functionality including:
 * a file system API that allows maps to read and write data (e.g. save codes, units, heroes, etc.), 
 * add external resources such as large audio files without importing them into the map, and 
 * fine-tune networking which can by-pass B.Net servers, therefore allowing unlimited # of players, re-sync, real-time games, and
 * **much, much more!**

### How do I get started?
(We're currently working very hard to develop the client and will post it soon. The application is cross-platform.)

### Authors and Contributors
Glacier is written by @chiefofgxbxl.  
Experimental map design and JASS ports written by @derdan.  
SharpCraft is written by MindWorX on The Hive.

### Support or Contact
(We're working on public documentation and the wiki. If you need anything for now, PM @chiefofgxbxl)
