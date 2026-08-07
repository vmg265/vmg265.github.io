---
layout: post
title: "How to make an iPod at home for 4$ and a Tic-Tac box"
date: 2026-08-07 23:52:00 -0530
categories: [blog]
---

{% comment %}
Here is a paragraph with **bold text**, *italics*, or lists:
- First point
- Second point
{% endcomment %}

**A follow up of my 2yr old YouTube short**
So a while back I uploaded this short not knowing it'll start reaching to a wide audience up until recently. Its funny how YouTube will keep a video dormant and then suddenly find audience for it and will blow it up. I have noticed this before and I still find it weird.

So in my monthly haul of new modules and parts I had bought a GPD2846A, a tiny mp3 decoder with a built in mono 2W amp. It can play mp3 files off a SD card (not to be confused with a GPD2856C which seems to be its bigger brother with a USB interface, a repeat track switch which I miss on here, and a built in 3.5mm female jack. The GPD2846A seems like a smaller, toned down, but much more versatile module)
The GPD2846A has a mono audio out via its SPK+ and SPK- pins. I have connected the SPK- to the ring2 which is GND on my TRRS female jack. You can also just leave the SPK- and connect the ring2 to the GPD2846a board's ground pin (one where tp4056's out- is connected).
Another thing I would change if I build a new one is I would add a 5v buck boost voltage regulator, these small modules keep the voltage at a steady 5v which the GPD2846a will happily run off of. The show build just got nominal 3.7v (same as the attached lipo battery) which means it'll fluctuate between 3v-4.2v and although the module still works it can shutdown under very low voltages and can potentially damage the module or the SD card. So I do recommend adding that 5v buck boost voltage converter and regulator

<img src="path/to/your-image.jpg" alt="Description of image" style="width: 90%; max-width: 100%; height: auto; border-radius: 12px; display: block; margin: 0 auto;" />
