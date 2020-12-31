---
title: "How to contact the ISS with a Baofeng"
date: 2020-12-30T10:14:08-08:00
draft: false
---

I've been a bit obsessed with trying to talk to space lately

Did you know the International Space Station has a ham radio repeater? I've known this for years but now that I'm in the world of ham radio, I can do something about it. 

First off you should know what I'm working with:

- Baofeng UV-5R 4w
- [Ed Fong Dual Band DBJ-1](https://edsantennas.weebly.com/)

![Image of antenna and baofeng](/posts/photos/iss-baofeng.jpg)

Why would you want to do this? Well the repeater can allow you to get contacts to people in areas outside of your normal range with just VHF/UHF, also beaming to space is fun. 

To track ISS passes, I use the Android app [ISS detector](https://play.google.com/store/apps/details?id=com.runar.issdetector&hl=en_US&gl=US) and set it to inform me of all passes. When a pass is coming up, I run outside and point my antenna to the sky, but which freqencies?
```
VHF/UHF Repeater Uplink: 145.99 (PL 67 Hz)
VHF/UHF Repeater Downlink: 437.80
```

This is what it looks like if you program you repeater in with chirp
![Chirp Iss Repeater](/posts/photos/chirp-iss-rep.png)

This will allow you to transmit on the right frequency and listen to the pass. When trying to contact the ISS you want to say your [grid square](https://www.levinecentral.com/ham/grid_square.php) and your callsign. Then see if anyone responds back. If they do, congrats! If they don't keep trying! The closer the degree pass is to 90 Degrees the better your signal will be. 

There's also another neat feature with the ISS of Slow Scan TV Images, I'll save that for another blog though.

Enjoy!

73

K6XSS