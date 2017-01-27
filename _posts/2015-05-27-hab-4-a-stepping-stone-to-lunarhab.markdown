---
layout: post
title: "HAB-4: A Stepping Stone to LunarHAB"
date: 2015-05-27 20:44:11 -0500
category: Balloons
author: Josh Eiland & Nick Becker
published: true
---

After HAB-1, which followed on the heels of a lunar eclipse in October, Josh proposed that we should launch a balloon during one of these extraordinary events. It turns out that the next lunar eclipse will be occurring on September 28th of this year. As a way to prepare for this huge project (HAB-5), we're dedicating our next balloon, HAB-4, to testing out a payload similar to that of which we will fly during the eclipse. In many ways, HAB-4 will be the most important balloon we will launch in 2015. The summer provides incredible opportunity to develop our skills in electronics and photography, and also plenty of time to build and fine-tune a payload. Currently, we have more improvements planned for HAB-4 than any other balloon before it.

<div align="middle">
  <iframe src="http://www.salagram.net/lunar-eclipse.gif" width="700" height="379" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

The eclipse is projected to begin at around 9pm and last slightly under 3.5 hours, with the full eclipse occurring for a little over an hour in the middle (with maximum eclipse at 10:47pm). We hope to launch before the full eclipse begins, at around 9:30, and capture as much as possible with a photography-based payload. For more information on this eclipse visit [this site](http://www.timeanddate.com/eclipse/lunar/2015-september-28).

## Objectives for HAB-4

While preparation in photography and camera stability is vital for the success of LunarHAB, HAB-4 will test improvements in other areas of the balloon as well. Every member of Panthera Sciences is working over the summer to either pursue an area of interest or further develop a skill they already have. High altitude balloon payloads are an excellent application of several of these skills, and HAB-4 will definitely reflect our work as a whole over the summer.

### Data Collection

Our approach to data collection in HAB-4 is not based on additional variables to measure or a near space experiment. While we may decide to include additional sensors, the main area of improvement is skills based. Electronics prototyping, schematic design, and maybe even PCB fabrication are extremely important skills that can be applied to virtually any project. A high altitude balloon payload is an excellent environment to test new skills in electronics, and that is exactly what we aim to do.

Several members of the Makers Club have expressed interest to pursue more advanced electronics skills. If we want to truly elevate the complexity of Makers Club projects and distinguish ourselves from other student run engineering organizations, skills such as PCB design would surely provide a foundation to move in that direction. Learning these skills will enable us to pursue more advanced projects in the future, like a miniaturized satellite. Currently, we are evaluating several online resources and reaching out to some of our friends at Georgia Tech for possible collaboration.

Additionally, we will continue to improve the Arduino datalogger from HAB-3. We have the following changes in mind:

**Arduino Datalogger Improvements**
* Upgrade to an Arduino Mega for better performance
* Secure wires to ensure battery connection and full functionality
* Fabricate an enclosure for the Arduino to protect solder connections
* Determine collection intervals considering power efficiency and data quality
* Improve exterior sensor mounting
* Wire the Anker Astro3 as the main power source

### Photography & Cameras

One of the greatest challenges in the LunarHAB payload will be capturing the event. The eclipse occurs hours after sunset in conditions that we have never released a balloon payload before. Preparation for HAB-4 will require research in astrophotography and additional cameras. Though we will still include at least one GoPro Hero in the HAB-4 payload, it is possible that the contrast between the illuminated moon and night sky will result in a blurry and overexposed video.

Luckily, the Global Space Balloon Challenge team offers several [tutorials](https://balloonchallenge.org/HABPhotographyHow-to-1.pdf) on this very subject. Cameras in the Canon Powershot series are extremely versatile and are even able to be programmed specifically for HABs with resources like the [Canon Hack Development Kit](http://chdk.wikia.com/wiki/CHDK). Finding an affordable and compact camera is a main priority for HAB-4, and whichever camera we choose will likely be used in all of our payloads from now on.

### Payload Structure & Casing

While our existing triangle shell design has proven very effective for camera stability in the past, there is always room for experimentation and improvement. At the time of posting, the club has not finalized goals for payload structure improvements. Some proposals include Arduino controlled navigational fins and other flight control type apparatuses to guide the balloon. More information will come in later posts after we reconvene and decide what designs we want to pursue.

### Communications

Our current APRS setup is big, fragile, and relatively restrictive with programming and configuration. It is based on an ArgentData OpenTracker USB and Baofeng UV-5R radio. While it is effective, we wanted to move to a platform that is more compact and versatile. Upon researching alternatives, we found [Trackuino](https://github.com/trackuino/trackuino) to be a well documented and appealing option.

> Trackuino is an APRS tracker shield for the Arduino platform. It features on-board GPS and radio transmitter, so the only external components required are the GPS and VHF antennas. It was designed primarily to track high altitude balloons, so it has other handy features like reading temperature sensors and a buzzer for acoustic location.
- Javi Martin, [Trackuino on GitHub](https://github.com/trackuino/trackuino)

<div align="middle">
  <iframe src="https://www.flickr.com/photos/pantherasciences/24725492403/in/datetaken-public/player/" width="700" height="525" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

What is great about this shield is that it will allow us to transmit data from sensors and breakout boards that we already have. The Arduino platform is something we are familiar with, and it will likely open up several doors relating to data collection and in-flight communication with the balloon. Additionally, building a shield for Arduino, or even a PCB in general, is something we have never done before. This is a great opportunity to familiarize ourselves with Eagle for PCB design, and these skills are easily applicable to other projects.

This summer promises to be exciting for both the Makers Club and Panthera Sciences. We're thrilled to have the opportunity to pursue something like this and probably the only group of students who are looking forward to the Fall.

**EDIT: HAB-4 and HAB-5 have merged. HAB-4 will be our LunarHAB launch on September 27th. There will be no launch to test the LunarHAB payload. A blog post is coming soon with more information regarding the merge, so please be sure to [subscribe](https://feedburner.google.com/fb/a/mailverify?uri=pantherasciencesblog&loc=en_US) for email updates.**
