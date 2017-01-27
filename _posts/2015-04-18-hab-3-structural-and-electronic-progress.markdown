---
layout: post
title: "HAB-3: Structural and Electronic Progress"
date: 2015-04-18 20:41:29 -0500
category: Balloons
author: Josh Eiland
published: true
---

With two weeks to go until HAB-3 ascends to near-space, we have made good headway towards being ready for our May 2nd launch (in case you're a reader outside of our email loop—we made the decision to postpone the launch from April 25 due to a thunderstorm forecast throughout the entire morning and afternoon). These past weeks we've made decisions regarding what changes need to be made before launch and have started work on finalizing HAB-3 for launch day.

### Battery

<div align="middle">
  <iframe src="https://www.flickr.com/photos/116202023@N05/17175704716/player/" width="480" height="640" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

We've successfully been able to strip and modify one USB mini-B cable to fit in a GoPro waterproof case while charging from an exterior source. This week we will be working on a second cord. Our goal is to trim these cords as much as possible so that the GoPro case can shut almost entirely, but we will also attempt to protect any remaining openings from cold and humidity with tape. We have a 12800mAh battery bank for charging, which should provide enough power to the GoPros to capture video up to the balloon's pop and hopefully more. This will, of course, depend on temperature, and we're currently researching and contacting other ballooners about potential methods to prevent hindrances on battery performance in near-space conditions.  

### Structure

<div align="middle">
  <iframe src="https://www.flickr.com/photos/116202023@N05/17175706416/player/" width="700" height="525" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

Though we're keeping the same trusty old Lightning McQueen lunchbox to enclose our payload, we're adjusting the foam inside—switching from the previous hollow triangular box made from styrofoam to more sturdy and neat insulation foam with compartments carved in for the electronics to be stored. This should improve insulation against low temperatures and also hold all electronics and wires in place more effectively to prevent any damage in case of likely turbulence and a rough landing. Additionally, this design is made to be modular. We will use four pieces of triangular foam insulation, stacked on top of each other. The bottom and top pieces will be solid bits of foam, that we will theoretically be able to reuse regardless of the payload's contents in the future. The middle two pieces of foam will be cut to accommodate the items in the payload—the radio, Arduino, and battery for the GoPros. By cutting compartments for each part, we will have more insulation for the parts, and the design will hold things in place instead of possibly being knocked around inside the lunchbox.

### APRS

The new antenna in our APRS configuration will have significantly longer range than the antenna equipped on HAB-2. The goal is to both increase the range of the sent data packets during flight and aid the chaser team during recovery. Once we find the general area of landing with SPOT and APRS packets, we will be able to pinpoint the location of the balloon. We plan to have a directional antenna on hand during recovery to aid this process if GPS fails.

<div align="middle">
  <iframe src="https://www.flickr.com/photos/116202023@N05/17259251171/player/" width="700" height="394" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

The directional antenna allows us to find the balloon in the case of a GPS malfunction. We will be able to tell in which direction the balloon is located based on the strength of the signal when we point the directional antenna in different areas.

### Datalogger

<div align="middle">
  <iframe src="https://www.flickr.com/photos/116202023@N05/17175703376/player/" width="480" height="640" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

Other than a few hiccups, the HAB-3 datalogger is complete and operational. Powered by an Arduino, the device's sensors will measure humidity, temperature, and altitude throughout the flight of the balloon. It also includes a 3-axis compass and accelerometer. The information gathered from the various sensors will then be written onto SD card for us to access upon payload retrieval. The sensors are attached to the outside of the payload with a custom 3D-printed mount. We will invest remaining time securing all wired connections, possibly with a 3D-printed encasement, and will also consider adding a new ultraviolet light sensor if we have the time and can get it working. A version of this device was made for use with HAB-2, however the connections were weak and it was not in working condition on launch day. We are excited to finally include these sensors on a balloon, as it is something we have looked forward to since HAB-1. We are equally excited to see the data recorded by the sensors at high altitudes. At the time of writing there is an issue with the SD card shield; however, we plan to have the issue sorted out by launch.

### Launch Details

Our launch is currently scheduled for Saturday, May 2nd at 8:00 AM to allow optimal lighting and adequate time for retrieval. We sent a request to the FAA for a location on the Chattahoochee River, but heard no response, thus we're planning to launch at Lake Allatoona in Cartersville, GA. Per FAA regulations, we are legally exempt from notifying the FAA of our launch at this location, as "Balloon payloads packages that weight less than six pounds ... are not subject to the provisions of Subpart D," which is the section that requires extensive criteria to be reported to the FAA for larger balloons. Since our balloon is predicted to weigh in at 5.5 pounds, we are exempt from this process. However, we are choosing to provide a HiBal (High Altitude Balloon Notice) to the FAA within 24 hours of the launch, as we did for the HAB-2 as a courtesy to airmen in the air. We're really excited to have a water launch, which should make for some great footage for our GSBC video in the competition!
