# ZX80 Pixel Synchronisation
This daughterboard for the Minstrel 2 v2.8 or earlier fixes an issue in the original ZX80's video output circuit.<br>

The issue would not have been noticeable back in the 1980s if using a CRT.<br>

The fix was created by Dave at Tynemouth Software for his Minstrel 2 computer, a recreation of the ZX80.  This fix is already implemented in the v2.9 board (latest as at May-2025).<br>

## Background
Please refer to Dave's blog posts where he details the issue and how he fixed it.<br>
- [Minstrel 2 Pixel Synchronisation (Part 1)](http://blog.tynemouthsoftware.co.uk/2022/09/minstrel-2-pixel-synchronisation-part-1.html)
- [Minstrel 2 Pixel Synchronisation (Part 2)](http://blog.tynemouthsoftware.co.uk/2022/09/minstrel-2-pixel-synchronisation-part-2.html)

## My Implementation
Thanks to Dave's help supplying me with the v2.6 and v2.9 schematics I was able to design a daughterboard that can replace the 74LS08 on the pre-V2.9 boards that replicates his fix.<br>

This has been successfully tested (Rev. A).  I didn't like how the tap wires crossed over each other so I re-arranged them and created a Rev. B board - this has not yet been tested but, apart from the re-arranged tap signals, is idential to Rev. A.<br>

## Testing
This YouTube video covers the testing of this board:<br>
[Minstrel 2 (Sinclair ZX80 Clone): Part 2 (Pixel Synch. Issue)](https://youtu.be/O-Urgigq2Vk)
