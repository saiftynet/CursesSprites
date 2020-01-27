# CursesSprites
A Perl module that can be used to developed console games

Multiple games already exist that can be played from the console.  This module will (hopefully) simplify the generation of games of a more sophisticated nature with multicharacter/multi-line sprites, motion, edge and collision detection, animated sprites, gravity and interbody attraction, acceleration/deceleration, and surface interactions.  It is at a very early stage of development.

The motivation is to develop a set of requiremenst for a more comprehensive games development platform, which may be used for other graphical backends.  Games backend already exist for Perl.  The focus of this one is simplicity, and the goal to develop a minimal set of methods that allow sophisticated game development with many of the features one might expect form graphical games, on the console.

In order to do this Curses is required. Curses provides many of the features that allow manipulation of the console display.

Two modules are provided.  Sprite.pm which cotains the sprite methods, and Scene.pm that provides the background.




