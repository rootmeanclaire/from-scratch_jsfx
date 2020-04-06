Ripple MonoSynth
================

A simple [wavetable synthesizer](https://en.wikipedia.org/wiki/Wavetable_synthesis).

The wavetable is given by the function:

    sin((ax)^p + (by)^q + θ)

`a`, `p`, `b`, `y`, `q`, and `θ` can all be adjusted via sliders.


Visualizer
----------

A visualizer is available below the sliders to help you see what's going on with the wavetable.

Black corresponds to an output amplitude of -1. Blue corresponds to an output amplitude of 1.

The "slice" of the wavetable that is currently active is given by the horizontal yellow line. The white lines indicate regions where x or y are equal to 0;


Parameters
----------

### X Ripples

The number of complete cycles that take place on a horizontal line going through the center of the wavetable.

Changes value of `a` in wavetable equation.

### Y Ripples

The number of complete cycles that take place on a vertical line going through the center of the wavetable.

Changes value of `b` in wavetable equation.

### X Pow

Changes value of `p` in wavetable equation.

### Y Pow

Changes value of `q` in wavetable equation.

### Y Phase

Changes value of `y` in wavetable equation.

### Ripple Phase

Changes value of `θ` in wavetable equation.

### ADSR

**Attack:** Milliseconds to reach peak volume  
**Decay:** Milliseconds from peak volume to sustain volume  
**Sustain:** Volume until MIDI note off message is received  
**Release:** Milliseconds from MIDI note off message until silence
