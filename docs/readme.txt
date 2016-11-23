        M.U.G.E.N

  Version 1.0
  18 Jan 2011

  (c) 1999-2011 Elecbyte


About
-----

M.U.G.E.N is a 2D fighting game engine with many customizable
components.

Please visit our forums at elecbyte.com for support, bug reports and
other useful resources.

This distribution includes a sample character Kung Fu Man. You
can check his movelist in the readme file in his directory:
  chars/kfm/



Updates
-------

See history.html for updates.



Contents
--------

I.      M.U.G.E.N Info
II.     Key Configuration
III.    Running the Game
IV.     Game HotKeys
V.      Speed Issues
VI.     Memory Issues
VII.    Known Issues / Notes
VIII.   Sample Content
A.      License Agreement
B.      Acknowledgements


=====================================================================
I. M.U.G.E.N Info
=====================================================================

M.U.G.E.N may be used free-of-charge for non-commercial purposes.
For other uses, please contact us.  Refer to Appendix A for the full
license text.


System requirements
-------------------

Operating System: Microsoft Windows XP SP2 or newer required.

CPU: Intel Core Duo or equivalent recommended for HD resolutions.

Memory: 512 MB or more (actual requirements may vary based on
character and stage complexities).


What M.U.G.E.N?
---------------

M.U.G.E.N is a 2D fighting game engine, originally released in 1999.
M.U.G.E.N was originally designed for users to create games that
matched the technology level of 2D fighters from the mid '90s.
However, it quickly evolved to become highly customizable, allowing
very fine control over each character's behavior.  In fact, there
are custom games for M.U.G.E.N that don't behave like your typical 2D
fighter.

The majority of content created for M.U.G.E.N tend to be distributed
as individual characters, stages or motifs (motifs are like themes,
that control the look and feel of the game).  Assembling a game is as
simple as downloading the content of your choice, and configuring
M.U.G.E.N to know about it.

M.U.G.E.N is designed to be used by people with little or no
programming experience, but with some artistic talent and patience to
learn.  Of course, having some programming background does give you a
bit of a headstart.  However, if you are just looking to play with
downloaded content, all you need to know is how to unzip files and
edit a text file.

M.U.G.E.N is also an acroymn for something, but we forgot
what it is. :)

Here's a sampling of features you can find in M.U.G.E.N:
- Customizable title screen, character select screen, life and power
  bars, game sound effects, fonts and more.
- Characters can have any number of sounds and sprites of any size
  limited by your computer's memory.
- Choose from multiple resolutions, ranging from 320x240 up to full
  HD at 1920x1080.
- Cutscenes.

Game Engine
- Use up to 7 buttons for a character.
- Regular moves, special moves, super moves, etc.
- Projectiles and special effects.
- Move cancels and combos, multi-part moves and throws.
- What your character can do is defined by a scripting language (and
  your imagination).


How M.U.G.E.N?
--------------

M.U.G.E.N was originally developed for DOS in C using DJGPP and
Allegro, an excellent compiler and gaming library respectively.
Today, M.U.G.E.N is built for Microsoft Windows using Visual Studio
Express and SDL.


Where M.U.G.E.N?
----------------

http://elecbyte.com/mugen


Why M.U.G.E.N?
--------------

To tell you the truth, we were making a shooting game and all of a
sudden it turned into this.  Although we were making a shooting game
in the beginning, we noticed that there weren't any good commercial
fighting games on the PC at the time.  Some of the inspiration came
from early engines like SFIBM.


Who M.U.G.E.N?
--------------

If you want to contact us about something, please use the contact
form on our website.
http://elecbyte.com/


When M.U.G.E.N?
---------------

I don't quite remember when we started this project, but it was
sometime around 1997 or 1998.  Our first public release version was
9X.06.27.



=====================================================================
II. Key Configuration
=====================================================================

This is the default key configuration. You can change it from the
options menu when you run the game.

Button      Player 1      Player 2
------      --------      --------
  Up        Up arrow      W
 Down       Down arrow    S
 Left       Left arrow    A
Right       Right arrow   D
  X         L             R
  Y         semicolon     T
  Z         double-quote  Y
  A         comma         F
  B         period        G
  C         slash         H
Start       Enter         U

If you have a joystick, you can enable it through the options screen.
Press F1 to access Input Config and set up your joystick from there.
Press left/right on the joystick type option to enable or disable
the joystick for each player.



=====================================================================
III. Running the Game
=====================================================================

From Explorer, double-click mugen.exe to start.

Main menu        Function
---------        --------
Arcade           Go 1 on 1 against the computer
Versus           Go 1 on 1 against your friend
Team Arcade      Play various team-up modes against the computer
Team Versus      Play various team-up modes against your friend
Team Co-op       Gang up against the computer with your friend
Survival         See how long you can last in an endless battle!
Survival Co-op   Play survival mode with your friend as a partner
Training         Try out moves and combos
Watch            Watch AI-controlled characters fight
Options          Set up basic game options
Exit             Quit from M.U.G.E.N

For "Arcade" mode, the key you hit will determine which side you play
on. If you chose with one of Player One's keys, your character will
play on the left side. If you chose with Player Two's keys, you will
start on the right side.

For the "team" modes, you first choose what team mode you would like
to play in. Press up/down to choose a mode. Some modes, such as Turns
mode, allow you to set the number of players on a team by pressing
left/right. Press a key to choose an option. In "Team Arcade", after
selecting your players, you have a choice of your opponents' team
mode. These are the different kinds of team modes:
  Single - Just you alone. Your character has 2 rounds.
  Simul  - You and a partner at the same time. Your team has 2 rounds.
  Turns  - You and up to 3 partners. When one character is KOed, the
           next will join in. Each character has 1 round.
The characters' starting life will be adjusted according the number
of players on each side.

Team Co-op is slightly different. The only team mode allowed is
Simul, which is automatically selected. Player One first gets to
select his character, followed by Player Two selecting the partner
character. When Player Two is done, Player One chooses the opponent's
team mode.

In Survival mode, there is an endless stream of opponents. The
objective is to beat as many opponents as possible. The game is over
when your team gets KOed. You can choose to play alone or in a team.
Single player mode gives you highest life points and healing (when you
win a round). The more players you have on your team, the less damage
each player can take, and the less each healing you get after each
round.

In "Watch" mode, first choose the team mode and characters to be on
Player One's side, then do the same for Player Two.


Switching order in Turns mode
-----------------------------

When you are playing Turns team mode, you can change your team order
during one of these situations:

1. right before the match start loading
2. after you lose a round, and right before the next round is loaded

The order switching is achieved by holding a directional button down.
Hold forward to rotate your team order by one member forwards. Hold
back to rotate your team order by one member backwards. If you have
4 available members, you can rotate it by 2 members by holding up.
Note that you can only rotate with members that have not yet been
KO'ed.

Here is a chart to clarify the way it works.

	         starting team
            1 2 3 4  |  1 2 3  |  1 2
           ----------+---------+------
 hold fwd:  2 3 4 1  |  2 3 1  |  2 1
 hold back: 4 1 2 3  |  3 1 2  |  2 1
 hold up:   3 4 1 2  |  ^      |  ^
            ^           |         |
            |           |         |
     this is the character that will come in


Command-line arguments
----------------------

M.U.G.E.N accepts optional command-line parameters for Quick-VS mode.

The format is (optional parameters are enclosed in square brackets):

  ./mugen [player1 player2 [-s stage]]

For example, to start quick versus between players named KFM and
Suave, you can type:

  ./mugen kfm suave

To play the same two characters in a stage named TEMPLE, type:

  ./mugen kfm suave -s temple

You can specify alternate .def files for your character:

  ./mugen kfm/newkfm.def suave -s temple

Here are other useful command-line options:

 -h            Displays help
 -r <sysfile>  Loads a motif (more information below)
 -p3 <pname>   Loads a character named pname as player3
 -p4 <pname>   Loads a character named pname as player4
 -s <sname>    Loads a stage named sname.def in stages/

For a full list of command-line options, type:

  ./mugen -h


Using motifs
------------

A motif is a custom configuration of the graphics and sounds
used in the game's interface, as well as other things such
as the character roster. The base motif is found in the
data/ directory. Custom motifs are placed as subdirectories
under data/. For example, the "kfm" motif is placed in
data/kfm/, and to use it you would type:

  ./mugen -r kfm

Here's what a motif covers (and which files each is in):
- character roster and stage list (select.def)
- title screen graphics, sounds and music (system.def)
- character screen graphics, sounds and music (system.def)
- versus screen graphics and music (system.def)
- victory screen graphics, sounds and music (system.def)
- option screen graphics, sound and music (system.def)
- filenames of storyboards (logo, intro, credits, etc) (system.def)
- the actual storyboard files
- fight demo options (system.def)
- continue/game over options (system.def)
- fight screen graphics and sounds (fight.def)
  The fight screen includes the life and power bars, "round X"
  images and sounds, common hit sparks and sound effects, etc.

To set the default motif, edit data/mugen.cfg with
a text editor, and change "motif" under [Options].

To install a downloaded motif, first unzip the file into a
new directory.  Open that directory to see if there are files
in it; if so, move that directory into M.U.G.E.N's data/
directory.  If there is a single directory instead, move that
bottom-level directory into the data/ directory.

To make your own motif, create a subdirectory under
data/ with the name of your motif, and copy system.def
into the new directory. If you'd like to edit any other
files besides system.def, make copies of them in your
motif directory and change them there. Any data file
that doesn't exist in your motif directory will default
to the one in the data/ directory, so if you did not
copy select.def over, data/select.def will be used
when you run with your motif selected.

Sample motifs are included: 
mugen1 - A motif designed for 1280x720 resolution.  This is the
         default motif.
big    - Gives you many spaces to put characters.
kfm    - The Kung Fu Man game motif.


Training Menu
-------------

A training menu is available in Training mode. You can choose menu
items with your directional keys and exit Pause Mode by pressing
any attack key or Pause. The following options are available:

Dummy control: Cooperative, AI, or Manual
  When in cooperative mode, the dummy will perform the actions you 
  specify elsewhere in the training menu. When in AI mode, the dummy
  will act like a normal computer opponent. When in manual mode, the
  dummy can be controlled with the opponent's keys.
 
Guard mode: None, Auto
  If guard mode is set to Auto, the dummy will attempt to block most
  attacks. If guard mode is set to None, the dummy will not block any
  attacks.

Dummy mode: Stand, Crouch, Jump, W Jump
  Depending on your selection, the dummy will stand, crouch, or 
  repeatedly jump. If you choose W Jump, the dummy will keep air 
  jumping as long as it can.

Distance: Any, Close, Medium, Far
  If you choose Close, Medium, or Far, the dummy will try to keep the 
  appropriate distance from you by walking forward/backward as 
  necessary. If you choose Any, the dummy will not move forward or 
  backward.

Button jam: None, A, B, C, X, Y, Z, Start
  The dummy will repeatedly mash the selected button. Good for testing
  a character's blocking.

You can minimize the training menu by pressing M while it is active.
Press M again to reenable it.



=====================================================================
IV. Game HotKeys
=====================================================================

These are the hotkeys recognized at the fight screen:

Key       Function
---       --------
Pause     Toggle pause
ScrollLck Frame-step within pause
Esc       Quit

The following hotkeys are for debugging purposes and can be disabled
by setting AllowDebugKeys = 0 in mugen.cfg.

Key       Function
---       --------
F1        Sets Player 2's life to zero
Ctrl-F1   Sets Player 1's life to zero
F2        Sets both players' life to 1
Ctrl-F2   Sets Player 1's life to 1
Shift-F2  Sets Player 2's life to 1
F3        Gives both players full power
F4        Reset the round
Shift-F4  Reloads stage, characters and fight data
F5        Time Over
F12       Take a screenshot (saved to mugen?.pcx)
Ctrl-C    Toggles display of collision boxes, target data (including
          remaining juggle points) and NotHitBy attributes
Ctrl-D    Toggles debug information display
Ctrl-I    Forces both players into stand state
Ctrl-L    Toggles display of the life and power bars
Ctrl-S    Run the game as fast as possible
Ctrl-V    Enable V-sync (stops "shearing")
Ctrl-#    (where # is from 1-4) Toggles AI for the #th player
Ctrl-Alt-# (where # is from 1-4) Enables/Disables the player
Space     Restores full life and power to all players



=====================================================================
V. Speed Issues
=====================================================================

If you find this runs slowly on your machine, there are several
things you can do to improve its performance. You can change these
options in data/mugen.cfg.

Close other applications
  Closing other CPU or memory-intensive applications may speed up
  M.U.G.E.N.

Use the most efficient video mode
  Running in a window can be slow on some systens. Try running in
  fullscreen. Set FullScreen = 1 in mugen.cfg.

Set a smaller resolution
  Try 640x480 or 640x360 if MUGEN is running too slowly in HD
  resolutions.

Turn off shadows
  You can turn shadows off to speed up drawing. Look in 
  data/mugen.cfg and set the "DrawShadows" option under [Config]
  to 0.

Use frameskip
  Auto-frameskip is enabled by default. The game will not draw
  some frames in case the computer is not fast enough, and this
  helps maintain a constant game speed.
  If you'd like to run at a constant framerate, you can hit Ctrl-F
  repeatedly to adjust the frameskip. It will switch from "auto"
  to "skip none" to "skip 1" to "skip 2" and then back to "auto".
  This works only when you are in the fight screen.

Free up memory
  Memory may be swapped to the hard disk when you run low, and
  this will severely impact performance. See the next section
  on how to reduce memory usage.

Disable precaching
  If you find the game slows down too much when loading in the
  background, you can disable precaching. This will increase
  load times, however. Under [Misc], set precache = 0.



=====================================================================
VI. Memory Issues
=====================================================================

If you find the program exiting or running slowly because you don't
have enough memory, here are some solutions:

Reduce the player cache
  M.U.G.E.N will try to keep players in memory in order to reduce
  loading times. You might want to reduce the number of players
  that are kept in memory at any one time.
  Open up data/mugen.cfg and look under the [Misc] section.
  Change PlayerCache to a smaller number. 0 will save you the
  most memory.

Reduce the number of characters
  Having a large number of characters can consume a substantial
  amount of memory. You can split your character roster up between
  multiple motifs. See "Using Motifs" in this readme file.

Disable buffered read
   You can save memory while loading characters by turning this
   option off. It is found under the [Misc] section, and called
   "BufferedRead". Loading times will increase as a result.

Reduce effects and limits
  Set the options under [Config] to a smaller numbers (see mugen.cfg
  for descriptions). Reducing HelperMax gives the most savings.

Enable system file unload
  Set UnloadSystem under [Misc] to 1.

Optimize your sprite files
  When you generate a sprite file, enable settings such as
  sprite.autocrop and sprite.detectduplicates.  If your sprites
  use 32 colors or less consider using lz5 compression (see 
  work/kfm/kfm-sff-optimized.def).



=====================================================================
VII. Known Issues / Notes
=====================================================================

An up-to-date known issues list is maintained on in our forum.
http://elecbyte.com/forum/



=====================================================================
VIII. Sample Content
=====================================================================


Sample content included in this distribution are:

Content                   Location
-------                   --------
Base motif                data/
"mugen1" HD motif         data/mugen1
KFM "classic" character   chars/kfm
KFM character             chars/kfm720
Fonts                     font/
Mountain temple stage     stages/kfm.def, stages/kfm.sff
Training room stage       stages/stage0.def, stages/stage0.sff
Training room HD stage    stages/stage0-720.def, stages/stage0-720.sff
Work files                work/


All the sample content is licensed under the Creative Commons
Noncommercial License, with optional attribution.

Basically, it means you don't need our permission to build upon or
use parts of any of that content for non-commercial purposes.  In
fact, we encourage you to use the sample content as a starting point
for your projects and replacing the graphics, sounds and behaviors.
Feel free to contact us if you have any questions.

More info about the CC License here:
http://creativecommons.org/licenses/by-nc/3.0/



=====================================================================
A. License Agreement
=====================================================================


By using M.U.G.E.N, you agree to the terms and conditions of this
license.

This license applies to the M.U.G.E.N Environment, defined as the
M.U.G.E.N executable, and other associated data files provided by
Elecbyte that are necessary for proper operation of the executable.


Usage

Under this license, permission is granted to use the M.U.G.E.N
Environment free of charge for non-commercial purposes.


Redistribution

Elecbyte provides a M.U.G.E.N redistributable package, containing a
minimal M.U.G.E.N Environment, that may be included with third party
content for redistribution. Such Works based on the M.U.G.E.N
Environment may be used and distributed, subject to the following:

i. Works containing the M.U.G.E.N Environment must be provided free
of charge and under the terms of this license.

ii. Works containing the M.U.G.E.N Environment must include an
unmodified copy of this license, as well as any other licenses
bundled with the M.U.G.E.N Environment.

iii. Works containing the M.U.G.E.N Environment must be plainly marked
as a such.

iv. You agree to indemnify Elecbyte from any legal liability for your
use, or distribution, of such Works.

Please note that Elecbyte places no restrictions on the distribution
of character files, stage files, add-on packs, or similar items which
operate under the M.U.G.E.N Environment, that do not contain any
significant portion of the M.U.G.E.N Environment itself.


Restrictions

This license is subject to the following restrictions:

1. The M.U.G.E.N Environment is copyrighted by Elecbyte and may not
be used for commercial purposes in whole or in part, altered or
unaltered, without Elecbyte's express written permission.

2. All distributions of the M.U.G.E.N Environment must retain a copy
of this license.

3. The M.U.G.E.N executable must not be modified for use or
redistribution.


Limitations

I. You agree to indemnify Elecbyte from liability for any damage
incurred to any computer hardware, software, or other property, as
well as from any injury incurred to your person or others, through
use of this software.  Elecbyte shall not be held responsible for any
failure of M.U.G.E.N and its associated tools to operate properly,
whether through deficiencies of the software or through user error.
Elecbyte disclaims all express and implied warranties, including but
not limited to warranties of merchantability and fitness for a
particular purpose.

II. Failure by Elecbyte to enforce any of the terms of this agreement
shall not constitute forfeiture of Elecbyte's right to enforce said
terms.

III. In the event of an inconsistency between this license agreement and
other Elecbyte documents, the terms of this license agreement shall
prevail, subject only to possible supersession by subsequent license
agreements. If any of the terms of this license agreement conflict with
the laws in your locale, the conflicting terms will be rendered null and
void. The remainder of this agreement shall still obtain.


Sample Content

Please note that the sample content included with the full M.U.G.E.N
package is not part of the M.U.G.E.N Environment, and is under a
separate license, the Creative Commons Noncommercial License, with
optional attribution.
http://creativecommons.org/licenses/by-nc/3.0/



=====================================================================
B. Acknowledgements
=====================================================================

Thanks to:
- All our beta testers.
- Everyone who contributed to us in any way.
- All of you who gave feedback to us.
- Everyone responsible for the software libraries we used:
  Allegro, FreeType Project, GLEW, libogg, libpng, SDL, SDL_gfx,
  SDL_image, SDL_mixer, SDL_ttf, SMPEG, zlib.  Also everyone
  reponsible for the other libraries we used in the older versions.

If we forgot to mention someone, please let us know!
