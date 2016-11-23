M.U.G.E.N In-game common sound effects
--------------------------------------

M.U.G.E.N       2001 Elecbyte
                www.elecbyte.com


This version updated: 5 July 2000

This directory contains the sprites required to build
data/common.snd, the sound file for in-game sound effects.

Unzip these files in work/common/sound under your MUGEN directory.
You will need SndMaker, available from our web page.

From your MUGEN directory, you can type
  sndmaker < work\common\sound\sound.txt

These sound effects are accessible by all characters.
For example, in the character's cns file:

[State 200, 1]
type = PlaySnd
trigger1 = Time = 0
value = F5,0

This will play back sound 5,0 from data/common.snd.
See the state controllers documentation for details.
