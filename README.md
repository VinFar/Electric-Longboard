# Self-Build electric mountain- and longboard with VESC and BLDC motor

##### Pressreport: https://www.fh-muenster.de/hochschule/aktuelles/pressemitteilungen.php?pmid=7254

<img src=https://github.com/VinFar/Electric-Longboard/blob/master/Photos/IMG_20170927_134837_HDR.jpg width="500">
This is a small Repo about my selfbuild electric mountain- and longboard, which I began to build in 2016 and 2019.
These are never ending projects, cause I will always come up with new ideas.

## Mountainboard
<img src=https://github.com/VinFar/Electric-Longboard/blob/master/Photos/IMG_20190715_064443.jpg width="500">

## Longboard
<img src=https://github.com/VinFar/Electric-Longboard/blob/master/Photos/IMG_20170807_081234.jpg width="500">

#### ToDo's:
* Backlight with Brakelight
* [Failsafe Function with Rubberband](https://www.svb.de/de/sicherheits-schalter.html)
  -If you jump off the board, let the board make a full brake


#### Not-ToDo's (already done):
* Cleaner Cable Managment
  - XT-60 Box
* Built cases
  - VESC-Case
  - CC converter case
  - Battery case
* Better Motorplate
  - 3mm stainless steel
* Changed Transmitter Case
  - [Baby Buffalo](https://www.thingiverse.com/thing:1810252)
* [LED-Headlight](https://github.com/VinFar/Electric-Longboard/tree/master/Inventor%20Files/LED-Headlight)

For the motor I choose [this BLDC Motor](http://www.hellray.de/shop/#!/eSk8-de-Motor-esk8-6354-200kV-2-2KW-mit-Sensoren/p/65758944/category=15255004).
It is recommend for 2,2kW, but due to sufficient cooling it can be powered with up to ~3.2kW (~40V with 80A max, efficiency ignored).

For the ESC I went with the aweseome [VESC 4](http://vedder.se/2015/01/vesc-open-source-esc/).

As Batteries two 5s LiPos are used, which are connected in series to get a voltage of up to 42V.
They have 5Ah each, so a total energy of around 200Wh can be consumed, which is enough 10-15 km depending on the driving speed.

For the Communication between the VESC and the driver, I got a [GT2B](https://www.google.de/search?q=GT2B&rlz=1C1CHBF_deDE742DE742&oq=GT2B&aqs=chrome..69i57j69i60j69i59j69i60l2j69i59.1148j0j4&sourceid=chrome&ie=UTF-8), which i then put into a [3D printed housing](https://www.thingiverse.com/thing:1810252) to get a small and ergonomic remote.

