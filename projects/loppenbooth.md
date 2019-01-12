---
layout: post
title: 'Loppenbooth'
---

Loppenbooth is a photobooth created for the music venue Loppen. It is now in its 3rd iteration and currently consist of

* An iron enclosure with 
    * 10w LED light and diffuser
    * Raspberry Pi with camera taking photos and pushing them to the cloud plus printing them over usb
    * Pushbutton for snapping photos
* A Epson Thermal usb printer with 80mm paper 

The photobooth currently has the following behavior

1. on button press go to 2.
2. fade up the LED 
3. take photo with PiCamera
4. fade down the LED
5. print photo via usb thermal printer
6. upload photo to AWS S3 bucket for further experiments
7. latest 50 pictures are available at [booth.loppen.dk](http://booth.loppen.dk/)

The photobooth of course tells about this behaviour and is explicit about the upload etc.

The printed photos has a certain aesthetic to them with their rastering and so forth and reminds people of a combination of gameboy camera and polaroid. 

Printing of a photo takes a few seconds.


{% include image.html url="https://youtu.be/4fXzuDtlc6Q" image="projects/loppenbooth/thumb.jpg" %}

Watch the video [here](https://youtu.be/4fXzuDtlc6Q).
Get the code [here](https://github.com/sloev/photobooth_web)
