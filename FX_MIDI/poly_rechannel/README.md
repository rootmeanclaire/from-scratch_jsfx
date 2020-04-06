Polyphonic Rechanneller
=======================

Can be used in conjunction with a MIDI channel filter to have several monophonic synthesizers act as a single polyphonic synthesizer.


Parameters
----------

### Polyphony

The number of notes of polyphony that are being used.

### Enable CC

Enable a CC to be sent to control a single parameter of all of the synthesizers downstream from the rechanneller.

### CC Parameter

The CC parameter to send downstream if "Enable CC" is set to "Yes".

Some parameters are recognized by some synthesizers automatically. The default value is 3 which does not have a defined purpose.

### CC Value

The value of the CC parameter to send downstream if "Enable CC" is set to "Yes".


Usage
-----

1. Set up the MIDI to play on a track without a synthesizer.
2. Set this track to send to several tracks with monophonic synthesizers on them.
3. Add a MIDI channel filter with a unique channel before each synthesizer in the FX chain.
