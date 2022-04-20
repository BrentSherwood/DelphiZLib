-- notes ---------------------------------------------------------------------

  the zlibex.pas unit included in this archive will work with delphi 5, 6,
  and 7.  if you previously downloaded my delphi 5 unit, you will notice
  that the unit has been renamed.  this was done because borland included in
  its delphi 6 and 7 lib directories a zlib.dcu file; and i felt it was more
  correct to rename my unit and force developers to have to update their
  code than to make developers worry about the possible file contention in
  delphi 6 and 7.

  please contact me if you find any errors, make any changes, add new
  functionality, or have any general suggestions so that i may incorporate
  them into my version.  i can be reached via my website at
  http://www.base2ti.com.

  thanks.

-- acknowledgements ----------------------------------------------------------

  erik turner - thanks for the enhancements and recommendations.
    specifically, the ZCompressionStream and ZDecompressionStream routines.
    my apologies for the delay in getting these in here.

  david bennion - thanks for finding that nasty little endless loop quirk
    with the TZDecompressionStream.Read method.

  burak kalayci - thanks for emailing to inform me about the zlib 1.1.4
    update; and again for emailing about 1.2.1.

-- installation --------------------------------------------------------------

  first, copy all of the files into a folder (for example, c:\delphi\zlib).
  next, include the folder in the library path in the environment options.
  finally, "use" the zlibex unit as needed.

-- contents ------------------------------------------------------------------

  delphi 5/6/7 files

    zlibex.pas

  objects files used by zlibex.pas

    adler32.obj
    compress.obj
    crc32.obj
    deflate.obj
    infback.obj
    inffast.obj
    inflate.obj
    inftrees.obj
    trees.obj

  c++ Builder 6 files

    DelphiZLib.bpr
    DelphiZlib.cpp

  zlib 1.2.1 source files (http://www.gzip.org/zlib)

    adler32.c
    compress.c
    crc32.c
    deflate.c
    example.c
    gzio.c
    infback.c
    inffast.c
    inflate.c
    inftrees.c
    minigzip.c
    trees.c
    uncompr.c
    zutil.c
    deflate.h
    infback.h
    inffast.h
    inffixed.h
    inftrees.h
    trees.h
    zconf.h
    zlib.h
    zutil.h

