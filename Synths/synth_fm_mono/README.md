FM MonoSynth
============

A simple [frequency modulation synthesizer](https://en.wikipedia.org/wiki/Frequency_modulation_synthesis).

Oscillator 1 is the carrier. Oscillators 2-4 each modulate the oscillator directly above them. All oscillators have a frequency relative to that of the currently sounding note.


Parameters
----------

### Osc N Amp

The amplitude of oscillator N. Set to 0 if you do not wish for oscillator N to have an effect on the sound. This will also remove the effect of any oscillators modulating oscillator N.

### Osc N Tune

The tuning of oscillator N relative to the note currently sounding. Expressed in semitones.

### Octave

Shifts the note played up or down an octave before it is passed to any oscillators.

### ADSR

**Attack:** Milliseconds to reach peak volume  
**Decay:** Milliseconds from peak volume to sustain volume  
**Sustain:** Volume until MIDI note off message is received  
**Release:** Milliseconds from MIDI note off message until silence
