# LED-Headlight for Electric Longboard

#### I wanted to solve Problem that I couldn't properly watcht the road when it is dark outside. So I build this LED-Headlight,
#### which perfectly fits beneath the front of the Board
<img src="../Photos/IMG_20170927_134837_HDR.jpg" width="500">

I scanned the outline of the bottom layer and converted it into a 2D Frame.
Then i took [this](http://www.ebay.de/itm/LED-Linse-Optik-Reflektor-10-Stck-Linsen-30-f%C3%BCr-1W-3W-5W-Power-LED-Leds-Lens/182454739604?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2057872.m2749.l2648) LED Lenses with an angle of 30° and made a 3D model where the Lenses fit in.
The front LEDs are facing 10° towards the ground and the two rear LEDs are facing 10° towards the ground and 10° towards the outside.
With this constellation i get a wider Lightarea.


`ToDo for Version 2:
    Put caps above the LEDs to prevend dazzling other traffic members!
`

I used normal 3W Power LEDs with a small additional heat sink. To drive the LED I took a [LM2596HV](http://www.ebay.de/itm/DC-DC-LM2596-HV-S-Buck-Constant-Current-Voltage-CC-CV-Step-Down-Module-60V-3A-/232457602919?hash=item361f8d8767:g:trsAAOSwzz1Zmt-e) CC Buck Converter.
For my requirements it was necessary to use the HV version of the Convert, because of the relatively High Voltage of 42V from the Lipo.
Also it is recommend to use the CC Version, because such Power LEDs has to be driven by a constant current and not a constant voltage!
For the Converter i created an external small case which sits in front of the Battery Cases.

To switch the Headlights on and off i used the unused third channel of the Remote Control.
I used a simply microcontroller, wich permanently monitors the PWM Signal of the third Channel.
The controller switches a simple Mosfet switch, which switches the High side.

The Headlight is [Version1.stl](https://github.com/VinFar/Electric-Longboard/blob/master/Inventor%20Files/LED-Headlight/Version1.stl)

The Converter Case is [Stromquelle_gehäuse.stl](https://github.com/VinFar/Electric-Longboard/blob/master/Inventor%20Files/LED-Headlight/Stromquelle_geh%C3%A4use.stl)

A timelapse Video of the 3D modeling phase is here(click! this is only a gif):
[![Demo CountPages alpha](https://github.com/VinFar/Electric-Longboard/blob/master/Inventor%20Files/LED-Headlight/timelapse1.gif)](https://youtu.be/nJyjoMh7dLY)

A timelapse Video of the 3D Printing is here(click! this is only a gif):
[![Demo CountPages alpha](https://github.com/VinFar/Electric-Longboard/blob/master/Inventor%20Files/LED-Headlight/timelapse2.gif)](https://youtu.be/3woWbC7GaZc)



<img src="../Inventor%20Files/LED-Headlight/1.PNG" width="500">
<img src="../Inventor%20Files/LED-Headlight/2.PNG" width="500">
<img src="../Inventor%20Files/LED-Headlight/3.PNG" width="500">
<img src="../Inventor%20Files/LED-Headlight/4.PNG" width="500">
<img src="../Inventor%20Files/LED-Headlight/5.PNG" width="500">
<img src="../Inventor%20Files/LED-Headlight/6.PNG" width="500">
<img src="../Photos/IMG_20170927_135013_HDR.jpg" width="500">

<img src="../Photos/IMG_20170927_140043_HDR.jpg" width="500">



