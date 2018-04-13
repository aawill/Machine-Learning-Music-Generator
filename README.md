Uses basic trained models to generate song lyrics and music based on training data. This was created as a final project during Fall 2017 EECS 183 at the University of Michigan by Aaron Willette, Kayla Wiggins, Brad Gurwin, and Jessica Glynn.

The lyric and melody components were required, but the harmony and bassline generation was an original idea. Similarly, we decided to incorporate Max/MSP to design synth voices that sounded more interesting than pysynth. 

It should work out of the box using pysynth, but if you want to get the full experience download Max/MSP at https://cycling74.com/downloads. Also, make sure you have 64-bit java installed on your computer.  

To use:
1. Open MusicGen.maxpat (if using Max)
2. Open generate.py, and run! 

To listen to output generated using pysynth, check the 'wav' folder. To hear samples generated using both pysnth and our custom max/msp synths, look in the 'samples' folder. Which sounds better to you? ;)
