---
layout: post
title: "HAB-2: The Successful Launch of Our Second High Altitude Balloon"
date: 2015-04-05 20:39:21 -0500
category: Balloons
author: Nick Becker
published: true
---

On Sunday, March 15 at approximately 7:52am, we launched our second high-altitude balloon project: HAB-2. The balloon reached an altitude of over 115,000 feet, and the flight was around 2 hours and 45 minutes in duration.

<div align="middle">
  <iframe src="https://www.flickr.com/photos/116202023@N05/16426537423/player/" width="700" height="700" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

  <iframe src="https://www.flickr.com/photos/116202023@N05/17041112282/player" width="700" height="394" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

The primary objective of HAB-2 was to test various improvements from HAB-1, and also to begin preparing for the Global Space Balloon Challenge. Areas of improvement include footage quality, payload fitness, tracking, and data collection.

### Footage Quality
In order to improve both the quality and types of footage that we captured on the balloon, we added two more GoPros to the payload. We pointed a Hero2 used in our previous balloon upwards to capture a view of the balloon and the sky. Additionally, we added a Hero3+ Silver facing outwards to record a view of the horizon and Earth’s curvature. To top it off we included a Hero4 Black facing downwards to get a nice view of the full landscape below. All cameras recorded in 1080p at 30 frames per second.

<div align="middle">
  <iframe src="https://www.flickr.com/photos/116202023@N05/17041823731/player" width="700" height="394" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

Preliminary battery tests suggested that the GoPros should have lasted between 1.5 to 3 hours, and though we suspected that the cold temperatures of near space would decrease this amount, we were relatively surprised to learn after recovery that the GoPros died relatively fast. Though we are still looking into possible causes for the cameras all dying in the span of a few minutes of each other, our best bet at the moment is simply that the payload experienced a drastic decrease in temperature at a certain altitude, which killed the batteries very quickly.

| Camera        | Test 1 | Test 2 | Test 3 | HAB-2 Flight |
|---------------|--------|--------|--------|--------------|
| Hero 4 Black  | 1:25   | 1:22   | 1:35   | 0:45         |
| Hero 2        | 2:25   | 2:30   | 3:02   | 0:46         |
| Hero 3+ Black | 1:35   | 1:12   | 1:13   | 0:48         |

To improve the GoPros’ battery lives, we are planning on installing a mini solar pad (called a Bushnell Bear Grylls SolarWrap Mini) and/or a battery bank and connecting them to the cameras with mini USB cords that we would modify fit inside of the GoPro case while it is closed.

### Payload Fitness
The HAB-1 payload was altered to better operate in terms of its profile and ability to be recovered. We used PVC with a slightly smaller schedule (thinner thickness) and made the triangle base slightly smaller to conserve mass, but maintained the same design aside from this adjustment. We also added insulating foam around the PVC shell to aid in floatation in case the payload landed in a body of water.

<div align="middle">
  <iframe src="https://www.flickr.com/photos/116202023@N05/17016565686/player" width="700" height="700" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

One improvement that we plan to make in future balloons is more strategic proportions and lengths of the payload train’s segments. We found that the beginning of the GoPro footage was shaky as the balloon was twisted in the wind, and to improve this we plan on lengthening the line between the parachute and payload so that the payload isn’t flung around as easily.

### Predictions & tracking

Using HabHub, we predicted that the balloon would travel roughly 110 miles east (and slightly south) from our launch site at Garrard Landing Park to an area of farmland just inside of the Georgia - South Carolina border.

<div align="middle">
  <iframe src="https://www.flickr.com/photos/116202023@N05/17041465222/player" width="700" height="404" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

HAB-2 was equipped with two GPS tracking devices. We tested the HAM radio Automatic Packet Reporting System (APRS) for the first time, and also used the SPOT GPS tracker from HAB-1. Our HAM radio APRS configuration reported location and altitude in 2 minute increments. Other than a few inconsistencies, the configuration preformed as expected. One of the weaknesses in our configuration was the standard Baofeng UV-5R rubber duck antenna we used. Unfortunately, no packets were received under 55,000ft during the descent.

Luckily, the SPOT was able to guide us within a few hundred feet of the actual landing, as will be explained in a later post. The reasoning for the 1.5 hour gap in the SPOT data is that the SPOT is limited to operation under 30,000ft. All recorded location and altitude data is below.

The following map includes data from both the SPOT GPS and the HAM radio APRS. Click any data point to reveal coordinates, altitude, course, and speed:

<div align="middle">
  <iframe src="https://mapsengine.google.com/map/u/0/embed?mid=zPjwrvJhFgJA.kQ23brCTRHmA" width="700" height="374"></iframe>
</div>

### Data collection

To better understand how conditions such as temperature and pressure change as the balloon rises in altitude to near-space, we hoped to send up an Arduino-based data logging system on the balloon. We created the datalogger with an Arduino Uno, Adafruit Data Logger Shield, and several Adafruit sensors including a temperature, humidity sensor, and a barometer (reporting pressure and altitude). We had planned to test a UV light sensor, however, the values we received while testing were abnormal, and we believe that the sensor was damaged.

<div align="middle">
  <iframe src="https://www.flickr.com/photos/116202023@N05/16854776588/player" width="700" height="934" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

Unfortunately, as we were preparing the payload during inflation of the balloon, a wire connection came undone which inhibited the datalogger from functioning properly. We were not equipped to rejoin the wire to the datalogger and made the decision to remove it from the payload. Nonetheless, the progress we made was very encouraging, and we have no doubt that with more time and careful soldering, it will be ready to go for the HAB-3 launch.

### Launch

The morning of the launch proceeded without any major holdups other than the datalogger drop mentioned above. The night before we constructed an adapter to the existing inflation tube that we used for HAB-1 which worked very well. After arriving to Garrard Landing Park at around 7:30, we unpacked and began inflating and final checkups, and the launch followed slightly over 20 minutes later, with photography by Cole Johnson and my Phantom.

### Balloon & Payload Specifications
Ballon type: 1600g (purchased from Hwoyee)
Payload mass: 1881.1g
Payload instrumentation: Baofeng UV-5R, Argentdata Opentracker USB, Argentdata ADS-GM2 GPS Receiver, SPOT GPS tracker, GoPro Hero 2, GoPro Hero 3+ Black, GoPro Hero 4 Black, (Arduino datalogger was removed prior to launch)

Contact us for any questions about the HAB-2 payload.
