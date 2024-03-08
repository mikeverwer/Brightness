# "Brightness"
This is a Python implementation of psudocode provided by StackExchange users Myndex and VC.One on this post:  
 &nbsp;&nbsp;&nbsp;&nbsp;[Full Post](https://stackoverflow.com/questions/596216/formula-to-determine-perceived-brightness-of-rgb-color), [Answer](https://stackoverflow.com/a/56678483)  
They provide an excellent breakdown of the process in their answer.

The "brightness" of a colour turns out to be very complicated. This module calculates two measures of 
"brightness"; luminance and perceived lightness.  Luminance is required to calculate percieved lightness.

The main functions of this module are lightness(args) and luminance(args). They take a colour hex code and return the 
percieved lightness of the colour and the luminance, respectively.  Brightness, as perceived by the human eye, and 
luminance are not the same.  See the linked post above for more information.
The value L* (Lstar) is the percieved brightness while Y is the luminance. 

>L* is a value from 0 (black) to 100 (white) where 50 is the perceptual "middle grey". L* = 50 is the equivalent of Y = 18.4, or in other words an 18% grey card, representing the middle of a photographic exposure (Ansel Adams zone V).

If you are wondering which one to use for your needs, good luck!  (it's perceived lightness... i think)
