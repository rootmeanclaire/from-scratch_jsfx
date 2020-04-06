Basic Reverb
============

A quick attempt at a reverb effect. Not very powerful, but it can help a little.

Parameters
----------

### Delay (ms)

Controls the size of the buffer in which reverberations are stored. The contents of the buffer will loop every N milliseconds, where N is the value stored of this slider.

### Simultaneous Reverberations

The number of times the sound repeats. Each repeat is overlapped and slightly offset.

### Dry/Wet Mix

0 corresponds to 100% a "dry" signal, in which the originial signal is passed through unmodified.

1 corresponds to 100% a "wet" signal, in which the reverberated sound is the only sound passed through.

### Decay

The buffer is overwritten as time passes, but its old values are partially retained. The maximum value of 0.90 means that each 90% of the old buffer is retained in each rewrite.
