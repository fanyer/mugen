M.U.G.E.N Fonts
---------------

M.U.G.E.N       (c) 2009 Elecbyte
                www.elecbyte.com


This version updated: 27 Jul 2009

This directory contains the sprites required to build all the font
files used in MUGEN.  These are FNT v2 files for use with MUGEN 1.0
and newer.

These files should reside in work/font under your MUGEN directory.
Use SprMaker to build the SFFs for these fonts, e.g.

  sprmake2 work/font/f-4x6/f-4x6-sff.def

When creating new fonts, it is recommended you do not overwrite the
files existing in font/. If you are making a new motif, put your
fonts in your motif's directory and modify the DEF files accordingly.


Files
-----

f-4x6 - Example small font SFF built using individual image files for
        each character glyph.

num48 - SFF for font used for time counter in the fight screen.  Uses
        a single pcx file as input with cropping specified in the
        SprMaker def file.