Ring Mod MonoSynth
==================

A simple [ring modulation](https://en.wikipedia.org/wiki/Ring_modulation) synthesizer.

Parameters
----------

### Carrier Waveform

The waveform whose pitch will always match that of the current note being played.

### Modulation Type

Whether the carrier wave will be multiplied or divided by the program wave

### Program Waveform

The waveform used to modulate the carrier.

### Program Frequency

The frequency of the program wave relative to the carrier.

### Program Phase

The phase of the program wave relative to the carrier.

### Program Intensity

The strength of the modulation

### ADSR

**Attack:** Milliseconds to reach peak volume  
**Decay:** Milliseconds from peak volume to sustain volume  
**Sustain:** Volume until MIDI note off message is received  
**Release:** Milliseconds from MIDI note off message until silence
