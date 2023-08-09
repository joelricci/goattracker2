# GoatTracker v2.76
## Silver Fork 
##### Macbook related fixes and improvements
\
Editor by Lasse Öörni (loorni@gmail.com)  
HardSID 4U support by Téli Sándor.  
Uses reSID engine by Dag Lem.  
Uses reSID distortion / nonlinearity by Antti Lankila.  
Uses 6510 crossassembler from Exomizer2 beta by Magnus Lind.  
Uses the SDL library.  
GoatTracker icon by Antonio Vera.  
Command quick reference by Simon Bennett.  
Patches and further development by Stefan A. Haubenthal, Valerio Cannone, Raine M. Ekman,
Tero Lindeman, Henrik Paulini and Groepaz.  
Microtonal support by Birgit Jauernig.  
Silver Fork fixes and additions by [Joel Ricci](https://github.com/joelricci)
Undo system by Jason Page

---
Distributed under GNU General Public License
(see the file COPYING for details)  

Covert BitOps homepage:
http://covertbitops.c64.org  

GoatTracker 2 SourceForge.net page:
http://sourceforge.net/projects/goattracker2  

<br>

## Revision history

This fork is based on the official above version of Goat Tracker. See [readme.txt](../readme.txt) for full history.

Additional changes in this fork:

- Undo edits using CTRL/CMD+Z (Thanks to Jason Page)
- Toggle ReSID interpolation and filter patch (distortion) mode by clicking INT/FP or press SHIFT+F9.
- Fine vibrato (FV) setting is now saved to config.
- Macbook keyboard insert support using ALT/OPTION+BACKSPACE or FN+SHIFT+BACKSPACE.
- Deleting rows now works correctly on a Macbook keyboard
- Delete using fn + backspace on a Macbook keyboard
- Backspace works as expected when entering filenames
- Better support for some USB keyboards (unwanted characters)
- Build instructions for MacOS (see separate [txt file](../build_instructions_macos.txt))
- Builds on Intel macOS 11 and later
