# Prototype-Rhococo
Prototype of my Retro Home color computer, a 8-bit Z80 based home computer remake with 128 (bank switched) RAM, that uses a Parallax propeller chip for all the stuff that homecomputers from the previous century did with lots of simple CMOS logic circuits and sometimes dedicated VLSI chips did, such as generating TV pictures, and sound.
My rhococo should be able to generate 27 colors of VGA video in 512 x 480 resolution, and should be able to generate PSG quality sound. 
instead of relying on cassette tapes, of floppy-disks, it can use SD-cards. It doesn't store its permanent memory on (E)PROMS but on a serial EEPROM read out by the propeller,and copied to Z80 RAM at boot time. 
Its not based on any one retro computer but borrows ideas from all of them, mainly from the sinclair spectrum, Commodore 64, and MSX computers.


on these page I will commit CAD files, (main page is Rhococo.sch with sub-schematics Z80CPU+RAM.sch, and KEYBOARD.sch, and RHOCOCO.kicad.PCB for the layout) , but eventually I will also upload ideas, code and other stuff so that others can also build and test prototypes of my retro home computer.

Note that I explicitly call this a prototype, as Rhococo is still in development, and not a fully functioning device.
Lots of things are not even tested yet, as for testing them other stuff must work first.

If hardware bugs are found I will upload updated files fo new PCBś, and/or information to patch existing PCB's.

Weekly updated information and progress reports will be posted on my Wiki at: https://revspace.nl/Designing_the_RhoCoCo_Retro_Home_COlor_COmputer_hardware

if you want to discuss this meaterial with me, the best place for now would be here: https://www.raspberrypi.org/forums/viewtopic.php?f=62&t=226889
