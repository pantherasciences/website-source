---
layout: post
title: "LunarHAB Description and Planning"
date: 2015-08-25 20:45:02 -0500
category: Balloons
author: Josh Eiland
published: true
---

For the sake of saving time and resources in addition to the fact that we were very busy over the summer, we decided to drop our plans for the HAB-4 launch plans and instead invest our time preparing for LunarHAB, which we'll conduct on September 27th (and recover the morning of September 28th). While we realize that this means we won't have a practice launch, we believe that devoting more time to LunarHAB will make for better results. From here on out, HAB-4 means the same thing as LunarHAB, and HAB-5 will be a separate project later this year.

### Launch Site

For LunarHAB, we plan to launch in northern Georgia near Blue Ridge, where hopefully the sky will be clear enough from light pollution for the lunar eclipse and other celestial bodies to be visible.

<div align="middle">
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4216.435009396665!2d-84.12982758428976!3d34.59499999751654!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzTCsDM1JzQyLjAiTiA4NMKwMDcnMzkuNSJX!5e1!3m2!1sen!2sus!4v1455593918938" width="700" height="525" frameborder="0" style="border:0" allowfullscreen></iframe>
</div>

We're hoping to launch LunarHAB in this small open mountaintop meadow in Amicalola Falls State Park, which is a well-known and acclaimed area for astrophotography and stargazing. Our alternative site will likely be an open area near Jacks River Falls, with an exact location TBD.

### Areas of Improvement

Right now we have several different groups focused on aspects of the payload, including:

* Cameras: We're hacking my old Canon Powershot ELPH 100HS using Canon Hack Development Kit, and are hoping to be able to optimize its settings for capturing the night sky without excessive exposure rates (which will be impossible due to the balloon's rapid motion and rotation).

    * We'll also be attempting to test our GoPros (and our new Xiaomi Yi camera) to find the best settings for the eclipse filming.


* Radio: We are attempting to convert our previous HAM-Radio configuration to a system termed the "Trackuino," which is a shield compatible with Arduino that will allow us to replicate the operations of the old setup with a much lighter system.

* Electronics: We're getting the gist of our new Eagle Flight Computer (which [we won for our GSBC video](http://pantherasciences.com/blog/07/28/gsbc-2015-winners-best-video)), which will give us data from an unlocked GPS as well as a temperature/pressure sensor. We're also converting our old datalogger from an Arduino Uno to an Arduino Mega for more expandability. This results in the possibility to include more sensors and collect more data.

* Power Supply: While managing these tasks, we'll be simultaneously testing the capability of our Anker battery pack to power our datalogger in addition to cameras to ensure we don't run into more issues gathering flight-long data. We hope to power everything onboard the payload from the Anker for HAB-4.

Payload design and more detailed descriptions of our progress will be published in a post within the next week or two. Stay tuned!
