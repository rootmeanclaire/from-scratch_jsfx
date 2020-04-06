Swung LFO (14-bit)
==================

Generates a MIDI CC LFO with a swing rhythm.

Parameters
----------

### MIDI CC (MSB)

The MSB of the CC Parameter to modulate. Some parameters are recognized by some synthesizers automatically. The default value is 3 which does not have a defined purpose.

### Swing Ratio

Ratio of long notes to short notes, expressed as a percentage of the note which lasts twice as long.

With swung eighth notes and the default swing ratio of 67, every odd eighth beat lasts 67% of every quarter beat, and every even eighth beat lasts 33% of every quarter beat.

### Swing on Nth Notes

Sets the subdivision whose notes are swung. Any integer fraction of a whole note is allowed.

### Cycles per Note

The number of cycles that the LFO will complete within each subdivision. The "Long Note" slider always refers to the first swung note of every grouping, regardless of whether it is actually longer than the "Short Note".

### Phase

The initial phase of the LFO

### Waveform

The waveform of the LFO


Usage
-----

For a more complete description see section 19 of the [Reaper User Guide](https://www.reaper.fm/userguide.php).

1. Insert the Swung LFO before the effect you wish to use it with.
2. Click the "Param" button on the effect you with to use the LFO with.
3. Open the menu `FX paramater list -> Paramater modulation/MIDI link`
4. Select the paramater you with to modify with the LFO
5. Check "Enable parameter modulation" and "Link from MIDI or FX parameter"
6. Click the box that says "(none)".
7. Open the menu `MIDI -> CC 14-bit`
8. Select the parameter whose first number matches the value you've chosen with on "MIDI CC (MSB)" slider of the Swung LFO
