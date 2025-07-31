# Z88 Mechanical Keyboard
I've not had too much luck with the keyboard on my Z88 - seems a bit flaky after 40-odd years.  So I thought I'd try to create a mechanical replacement.<br>

I've modified the layout slightly to improve the arrangement - the cursors are now a "proper" inverted-T layout.<br>

## Layout
The layout almost matches a modern set of keycaps, apart from the custom ones.<br>
By this, I mean the SHIFTED characters on each key match a modern keyboard so a generic set of key caps, plus some blanks, should work.<br>

![Z88 Keyboard Layout](T_CURSOR/cambridge-computer-z88_T_cursor.jpg)

## Changes From Original Z88 Layout
The reason for these changes are either to improve the layout (cursors) or to simplify getting key caps (CAPS LOCK & DIAMOND)
- (Rev. A) Cursors are now an inverted-T
- (Rev. B) CAPS LOCK moved to standard location between TAB and LH SHIFT and is now 1.75u (a standard size in key cap sets)
- (Rev. B) DIAMOND moved to original DOWN cursor location (bottom right) and is now 1u (can use a blank)
- (Rev. C) Possibly external version via Z88 expansion port featuring switchable on/off backlit keys ... ?

## Construction
The board is designed to use Gateron Low Profile (KS-33) type key switches with Cherry MX-style key caps.<br>

- 64 key switches (Gateron KS-33)
- 53 x 1u key caps
- 5 x 1u blank (INDEX, MENU, HELP, SQUARE, DIAMOND)
- 1 x 1.25x2u (ISO ENTER)
- 1 x 1.5u (TAB)
- 1 x 1.75u (CAPS LOCK)
- 2 x 2u (SHIFT)
- 1 x 7u (SPACE)
- (Optional) Stabiliser for 7u SPACE bar? (must work with Gateron low-profile)
- 2 x 8-pin thin film connectors (e.g. TE Connectivity/AMP 5-520314-8 or similar)
- 2 x 8-pin strips of thin film cables (e.g. Parlex PSR1635-08 or similar)

I've not been able to find suitable stabilisers yet so am considering using three key switches for the SPACE bar.<br>

![3D image of keyboard](Z88_Mechanical_Keyboard_T_cursor_3D.png)

## Related Videos
- [Schematic & PCB layout](https://youtu.be/C3n-ExND1uk)
- [Track routing & final touches](https://youtu.be/aaBBvU5d50o)
- [Testing the Rev. A PCB](https://youtu.be/vxIY81ir3Ao)

## Further Work To Do 
### Rev. C
- Create an external version (no changes required to Z88) connecting via Z88 expansion port
- Z88 expansion port connector still available?

## Status
1-Jul-2025: Work in progress<br>
3-Jul-2025: Added 6.25u space bar layout<br>
4-Jul-2025: Added inverted-T cursor layout<br>
5-Jul-2025: Inverted-T cursor design routed, ready for test fabrication<br>
7-Jul-2025: Design tweaked, sent to PCBWAY for test fabrication<br>
12-Jul-2025: Test PCBs shipped from PCBWAY<br>
25-Jul-2025: Test PCBs arrived, working!!, need to adjust size of PCB slightly ... maybe (see [video](https://youtu.be/vxIY81ir3Ao))<br>
26-Jul-2025: Started work on Rev. B<br>
31-Jul-2025: Completed Rev. B changes<br>


