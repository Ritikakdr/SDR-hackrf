

# SDR-hackrf 

homework assignment from the Michael Ossmann series.

A note that all these flowgraphs are made in the Gnu version 3.10.7.0 (Python 3.11.6)
# Lesson 1
Q.) FM radio flowgraph: Create a flowgraph in GNU Radio Companion like the one in the video or the screenshot below. Test the flowgraph by listening to a strong FM radio signal.


# Lesson 2
WX GUI FFT sink is not available in this version Gnu, so we've replaced it with frequency sink.
Since the whole WX widget is not present, I have replaced it with QT number sink and frequency sink.

# Lesson 3|
| dB | ratio  |
|-- |--|
|  0| 1:1 |
|  1|1.2: 1
|   2|1.6: 1
|  3|2:1
|  4|2.4: 1
|  5|3.2: 1
|  6|4: 1
|  7|4.8: 1
|  8|6.4 :1
|  9|8: 1
|  10|10: 1
|  11|12.8: 1
|  12|16:1
|  13|20:1
| 14 |25.6:1
|  15|32:1
|  16|40 :1
|  17|51.2 :1
|  18|64: 1
|  19|80 : 1
|  20|100 : 1
|  21|128:1
|  22|160:1
|  23|200:1
|  24|256:1
|  25|320:1
|  26|400:1
|  27|512:1
|  28|640:1
|  29|800:1
|  30|1024:1

# Lesson 4
Start with the flowgraph from the [lesson 2](https://greatscottgadgets.com/sdr/2) homework. Add a scope sink.
-> the scope sink in version 10 is missing
# Lesson 7
Q.) Launch GNU Radio Companion and locate the block called Quadrature Demod. This block implements the method for frequency demodulation presented in the video. Notice that it takes complex input and produces real-valued (float) output which is a sequence of angles.
