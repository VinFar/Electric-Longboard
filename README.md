# Self-Build electric mountain- and longboard with VESC and BLDC motor

##### Pressreport: https://www.fh-muenster.de/hochschule/aktuelles/pressemitteilungen.php?pmid=7254

This is a small Repo about my selfbuild electric mountain- and longboard, which I began to build in 2016 and 2019.
These are never ending projects, cause I will always come up with new ideas.

## Mountainboard
<img src=https://github.com/VinFar/Electric-Longboard/blob/master/Photos/IMG_20190715_064443.jpg width="500">

The longboard has been running very well for some time now and it's a lot of fun to ride.
But the small wheels (70mm diameter) are annoying and dangerous, because you have to pay attention to all medium sized stones and edges on the road, which will make the rides exhausting. Due of this and also because I was looking for a new challenge, I started building a mountainboard in May 2019.
This must have the following improvements:

- big pneumatic tires (at least 130mm in diameter)
- higher range (at least 30 km)
- newer version of the VESC
- USB-C PD charging capability
- 12S4P Li-ion battery pack

The first rough prototype of this is shown in the picture above. The box in the middle is a temporary battery box for testing.
At the moment (27.08.19) it has pneumatic tires with a diameter of 160mm, a range of about 35km  with ~600Wh 12S2P Lipos and VESC 6 with Bluetooth module.

Another thing that bothered me with the first longboard, was that I always had to take a 12V PSU and a Lipo charger with me in order to charge the batteries.
So for the Mountainboard i came up with the idea of charging the batteries over a [60W - 100W USB C Power Delivery power supply](https://www.voelkner.de/products/1055964/LVSUN-80W-USB-C-QC3.0-LS-Q5U-PD-USB-Ladestation-Steckdose-Ausgangsstrom-max.-17000mA-5-x-USB-3.0-Buchse-A-USB-C-Buchse-USB.html?ref=43&gclid=CjwKCAjwqZPrBRBnEiwAmNJsNvpwpM6ajLzNNvfVCtntl1ii1nHgAlBQvSeEuug1pQpiML4Ajp89HRoCUrUQAvD_BwE). On awesome feature of USB C is that it can deliver up to [100W over the small USB-C plug](https://en.wikipedia.org/wiki/USB-C#USB_Power_Delivery) (20V and 5A).
I want to use this in combination with a [50V boost converter](https://www.droking.com/dc-boost-converter-power-supply-module-adjustable-regulator-dc-10v-40v-to-10-50v-6a-step-up-converter-dc-12v-24v-cc-cv-voltage-regulator-board) and the open source BMS [DieBieMS](https://github.com/DieBieEngineering/DieBieMS) to have to ability to charge it on every socket.

The 12S4P Li-ion battery pack will be mounted beneath the deck in the form of a modular system, which is shown below.
<img src=https://github.com/VinFar/Electric-Longboard/blob/master/Photos/assembly1.PNG width="500">
<img src=https://github.com/VinFar/Electric-Longboard/blob/master/Photos/akkubox_png.PNG width="500">

In every battery tray there is space for a 2S3P/3S2P/1S6P/6S1P battery pack. This trays are then connected in series to raise the voltage and/or the capacity. The BMS, the converter and the VESC will sit in the blue housing at the end of the mountainboard.

The first test ride with the this board were awesome. It runs so much better on all terrains, so you don't have to worry about stones and bumps any more. Even on uneven tracks like in a forest or on grass it runs good.

In the future I will get a second motor to also drive the second tire and to have more torque (at the moment the power is ok, but could definitly be more).



## Longboard
<img src=https://github.com/VinFar/Electric-Longboard/blob/master/Photos/IMG_20170927_134837_HDR.jpg width="500">
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

