Buffer Distortion
=================

Removes some samples and interpolates their values during playback.


Parameters
----------

### Buffer Size

The size of the interpolation interval (in samples).

### Algorithm Type

Flat: A new output amplitude is calculated only when the old one has played for the length of the interpolation interval.

Rolling: A new output amplitude is calculated every sample. Interpolation is based on every sample in the interpolated intervals.

### Algorithm

**Constant:** The first sample in the buffer always used.  
**Mean:** The average value of all the samples in the buffer is always used.  
**Linear:** The first and last values are used to calculate a slope and determine the values in between.  
**Random:** A random value is chosen from the buffer.  
