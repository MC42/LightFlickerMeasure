# LightFlickerMeasure
Measures flickering lights, like PWM driven LED-systems, using Arduino.

An old Light Bulb sends 80% constant light and a 20% sine waveform as 100 Hz noise ontop, so no flicker is recognized.

<img src="doc/Old_Light_Bulb.jpg" width="500">


This LED Streetlamp sends a permanent PWM of 264 Hz instead of a steady light! Going for a walk at night, this lamp is really annoying.

<img src="doc/Streetlamp_264Hz.jpg" width="500">


Philips Hue Being ceiling light and also the Philips Hue Light Strip+, as well as my Philips Hue RGB light bulbs, run at 1 kHz PWM. That still flickers irritatingly in your eyes when looking around in your appartment.

<img src="doc/Philips_Hue_Being_1kHz.jpg" width="500">


Totally smooth light sent by a Philips Filament Bulb (not dimmable), I really enjoy it.

<img src="doc/Philips_Filament_0Hz.jpg" width="500">
