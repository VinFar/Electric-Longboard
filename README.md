# Self-Build Electric-longboard with VESC and 4kW brushless motor

### This Readme isn't finished yet!

##### Pressreport: https://www.fh-muenster.de/hochschule/aktuelles/pressemitteilungen.php?pmid=7254

<img src=https://github.com/VinFar/Electric-Longboard/blob/master/Photos/IMG_20170927_134837_HDR.jpg width="500">
<img src=https://github.com/VinFar/Electric-Longboard/blob/master/Photos/IMG_20170807_081234.jpg width="500">
This Repo is about my self-build electric Longboard, which I began to build in 2016. It runs flawlessly and very smooth.
But this is a never ending Project, because I always come up with new ideas.

#### ToDo's:
* Implement OLED Display in Transmitter or into the Board for Realtime Informations
  - Drained Energy
  - Battery Voltage
  - traveled distance
  - speed
  - etc...
* Backlight with Brakelight
* Failsafe Function with Rubberband
  -If you jump off the board, let the board make a full brake
* Follow-me Function with my Drone


#### Not-ToDo's (already done):
* Cleaner Cable Managment
  - XT-60 Box
* Built cases for everything
  - VESC-Case
  - CC converter case
* Better Motorplate
  - 3mm stainless steel
* Changed Transmitter Case
  - [Baby Buffalo](https://www.thingiverse.com/thing:1810252)
* [LED-Headlight](https://github.com/VinFar/Electric-Longboard/tree/master/Inventor%20Files/LED-Headlight)

I used [this Brushless Motor](http://www.hellray.de/shop/#!/eSk8-de-Motor-esk8-6354-200kV-2-2KW-mit-Sensoren/p/65758944/category=15255004).
It is recommend for 2,2kW, but because of the sufficient cooling I am powering it with ~4kW (42V with 100A, efficiency ignored).

For the ESC i am using the aweseome [VESC](http://vedder.se/2015/01/vesc-open-source-esc/), which is perfectly for smooth low-RPM start-up!

As Batteries I used two 5s LiPos (higher discharge rate in comparison to Li-ion) connected in series to get the high voltage of 42V.
They have 5Ah each, so i get total energy of around 200Wh, which is enough 10-15 km depending on the driving speed.

For the Communication between the VESC and me, I used the [GT2B](https://www.google.de/search?q=GT2B&rlz=1C1CHBF_deDE742DE742&oq=GT2B&aqs=chrome..69i57j69i60j69i59j69i60l2j69i59.1148j0j4&sourceid=chrome&ie=UTF-8), which is reliably and affordable.

