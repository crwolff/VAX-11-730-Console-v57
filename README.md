#VAX-11-730-Console-v57
##by Mark J. Blair <nf6x@nf6x.net>

These three VAX-11/730 console tape images were downloaded from:
    [http://www.heeltoe.com/download/vax/tapes-730/README.html](http://www.heeltoe.com/download/vax/tapes-730/README.html])

and then contents were extracted with:
    [https://github.com/NF6X/pyRT11](https://github.com/NF6X/pyRT11)
    
Images files were then renamed with .tu58 extensions. contents.txt is
original listing file downloaded with the images.

*-files directories contain files extracted from images

*.bootblocks files contain boot blocks extracted from images

*-listing files contain directory listings of images

Console tapes appear to be version 57.

##BE-T173I-ME.tu58
    Main console tape:
    Mount in internal drive at powerup to load WCS with microcode and
    then (optionally) boot operating system.

##BE-T175I-DE.tu58
    Not sure about this tape yet. Not bootable on 730.
    DEFBOO.CMD says: "DX0 DIAGNOSTIC SUPERVISOR FLOPPY BOOT"

##BE-T176I-DE.tu58
    Customer-Runnable Diagnostics:
    Mount in external drive, with main console tape in internal drive.
    Switch default drive with "DIR DD0:".
    Launch tests with "T".
    Requires a separate CRD RL02 pack.
    I have a compatible pack which came with my 11/730, but no way to
    image it yet.

##vax730-console-v58.tu58
    As a bonus, here is an image of a version 58 console tape, assembled
    from files provided by another VAX-11/730 owner.

