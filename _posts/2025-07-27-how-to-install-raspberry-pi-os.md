---
layout: default
title: How to install Raspberry Pi OS?
author: ernugraha
date: 2025-07-27 06:30:00 +0700
category: software
---

# This site work-in-progress!
Tested on raspberry pi 4 4gb
## Table of Contents
- [What you need](#what-you-need)
- [Installing The Imager](#installing-the-imager)
- [Flash the OS](#flash-the-os)
- [Final](#final)
- [Source](#image-source)


## What you need
- Raspberry Pi (work on pi 4, 5)
- Micro SD (min. 16gb)
- Micro SD Adapter (optional)
- a PC for flashing OS

## Installing The Imager
First you need installing a app called "Raspberry Pi Imager" for flashing os to microSD.
To install it you can open this [link](https://www.raspberrypi.com/software/), then click download
(select the correct OS you use). ![w1](/assets/imgs/rpi/w1.png)

Because i use Linux, type this on terminal
```bash
sudo apt install rpi-imager
```

## Flash the OS
After you installed rpi-imager, insert your microSD to adapter or SD port or anything that can read microSD,
then open Raspberry Pi Imager app.

![w2](/assets/imgs/rpi/w2.png)

Then choose the Raspberry pi Device (if you use raspberry pi 5 example, select Raspberry Pi 5). Because i use rpi4, i will choose Raspberry 4. Next choose the operating system (OS), i recommend to use Raspberry Pi OS 64 Bit. Then choose the storage, usually on linux labeled with "Generic Storage Device".

Maybe result look like this.

![w3](/assets/imgs/rpi/w3.png)

Then click "Next". You will be asked for apply OS customization settings, if you want to do that later, click "No" and skip next tutorial and go to [final](#final).

![w4](/assets/imgs/rpi/w4.png)

If you click "Edit Settings", you will be able see customization settings.

![w5](/assets/imgs/rpi/w5.png)

Just set it then click "Save"

Done? Next click "Yes" then... click "Yes" again.

![w6](/assets/imgs/rpi/w6.png)

And well done... wait until finish.
(DONT UNPLUG YOUR MICROSD UNTIL FINISH!)
![w7](/assets/imgs/rpi/w7.png)


## Final
Unplug the microSD, then plug to your Raspberry Pi, turn on, and Done!

![w8](/assets/imgs/rpi/w8.png)

What Next? Checkout [https://ernugrahadev.github.io/raspberry-pi/](https://ernugrahadev.github.io/raspberry-pi/). Bye!
## Image Sources
https://www.raspberrypi.com/software/