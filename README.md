# CursesSprites
A Perl module that can be used to developed console games

Multiple games, in multiple genres already exist that can be played from the console.  This module will (hopefully) simplify the generation of games of a more sophisticated nature with multicharacter/multi-line sprites, motion, edge and collision detection, animated sprites, gravity and interbody attraction, acceleration/deceleration, and surface interactions.  It is at a very early stage of development.

The motivation is to develop a set of requiremenst for a more comprehensive games development platform, which may be used for other graphical backends.  Games backend already exist for Perl.  The focus of this one is simplicity, and the goal to develop a minimal set of methods that allow sophisticated game development with many of the features one might expect form graphical games, on the console.  Modern consoles allow UTF characters so more feature rich sprites may be used.

In order to do this Curses is required. Curses provides many of the features that allow manipulation of the console display.

A single module is provided.  CursesSprites.pm which contains the sprite methods, as well as the background and surfaces they interact with.  The module handles drawing and interaction in a singlethreaded manner with universal "tick".  At the end of each tick all the sprites are updated (position, velocity etc), conditions (collisions with other sprites and contact with scenery) and events tested, and appropriate reaction triggered. 

This is not yet ature enough for CPAN.  For that to happen several games will have to be produced to prove that this has a real-life applicability.  For each *genre* of game produced, the version number will be notched up by .1 . Examples of generes may be simple puzzles, maze type games, bouncing games, top down RPG, platformers, topdown shooters, scrolling shooters. All of these exist, of course, but might be interesting to have one framework that has the capability deliver multiple types of console games easily in Perl.







