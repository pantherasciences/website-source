---
layout: post
title: "HAB-3: Technical Overview"
date: 2015-05-22 20:43:19 -0500
category: Balloons
author: Nick Becker
published: true
---

HAB-3 represents every test, improvement, and lesson learned throughout the year in the Lovett Makers Club. In the Fall, we launched our first high altitude balloon with a very simple payload to challenge the idea that we can send something to the stratosphere and then retrieve it. Not only have we successfully recovered every payload to date, but each HAB has pushed the limits of what we thought we were capable of achieving. The following is a look into the process and design behind the HAB-3 payload, and most importantly, what we learned from it.

<div align="middle">
  <iframe src="https://www.flickr.com/photos/pantherasciences/17925999086/in/datetaken-public/player/" width="700" height="540" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

### Structure

<div align="middle">
  <iframe src="https://www.flickr.com/photos/pantherasciences/17952728185/in/datetaken-public/player/" width="700" height="370" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

The HAB-3 structure was built with the existing shell and payload bay from HAB-2. The outer shell is 3/4in schedule 20 PVC, and the payload bay is an equilateral triangle lunch box with a side length of 10.5 inches. Inside the lunch box, the electronics are insulated with polystyrene foam sheets. The foam is intended to be modular, thus allowing payload security and flexibility with the organization of the enclosed electronics.

After retrieving HAB-2, we observed that the paracord and rope connections were the weakest points in the payload train. To further secure the connection to the payload bay, we designed and fabricated "paracord stoppers" on a Makerbot Replicator 2. These stoppers successfully prevented any tearing on
the lunch box and secured the payload effectively.

<div align="middle">
  <iframe src="https://c8.staticflickr.com/9/8758/16581439423_8d477441b5_k.jpg" width="700" height="540" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

In future payloads, we plan to further protect electronics and radio by making better use of the modular polystyrene foam. We have learned that payload security is extremely important. Although often overshadowed by electronics, radio, and photography, the insulating and protecting foam is the only thing protecting our electronics from near space and impact after descent.

A PDF of the above wireframe can be found [here](https://drive.google.com/file/d/0B-Udy9R0pBXpcGNKZGdLeXN2Uk0/view?usp=sharing).

### Data Collection

<div align="middle">
  <iframe src="https://www.flickr.com/photos/pantherasciences/17052610527/in/datetaken-public/player/" width="700" height="525" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

The data collector for HAB-3 used an Arduino Uno Rev3 microcontroller to power 3 digital sensors. Almost the entirety of the datalogger was prototyped and coded by Ned Ellis and Davis Rackley in the Lovett Makers Club. Ellis and Rackley wrote a program to collect data from a barometer, thermometer, accelerometer, gyroscope, and humidity sensor and write it to an SD card. Details on the logger are below.

* [Adafruit Data Logging Shield for Arduino](http://www.adafruit.com/products/1141)
* [MS5607 Barometer/Altimeter Module](https://www.parallax.com/product/29124)
* [LL3GD20H + LSM303 Adafruit Accelerometer/Gyroscope Breakout](http://www.adafruit.com/products/1714)
* [HTU210D-F Adafruit Temperature/Humidity Breakout](http://www.adafruit.com/product/1899)

<div align="middle">
  <iframe src="https://www.flickr.com/photos/pantherasciences/17952963361/in/datetaken-public/player/" width="700" height="525" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>

The three breakout boards were mounted to a 3D printed sensor plate. The mount was secured on the exterior of the lunch box, allowing the sensors to be exposed to the elements.

The theme of payload security carries over to the area of data collection as well. While the datalogger was fully functional in testing, the power connection was not properly protected from the tight fit of the payload bay. In future payloads, we plan to protect the datalogger's connections with custom casing and eventually custom PCBs to minimize loose solder connections.

### Communications

The Ham Radio APRS configuration in HAB-3 was nearly identical to that of HAB-2. It included a ArgentData OpenTracker USB which interfaced with a Baofeng UV-5R handheld radio.

The OpenTracker was configured to collect and transmit latitude, longitude, altitude, and course data from a ADS-GM2 GPS receiver. The setup uses the Automatic Packet Reporting System, a digital communications information channel in amateur radio, to transmit data packets that included this information. After transmission, the data packets cross over from the local RF network to APRS-IS via gateways that can be found all over the country. After this point, the data is visible on sites such as aprs.fi and able to be followed by a chasing car or spectators easily.

Unfortunately, the UV-5R keypad was not locked while preparing the payload prior to launch. At some point in the shuffle, the keypad was hit and the radio changed frequencies. In order for data to be collected and stored in the APRS Internet System, it must be transmitted on 144.39. No data from the ADS-GM2 GPS was collected during the HAB-3 flight. Moving forward, we plan to replace our existing configuration with an [Arduino based alternative](http://www.trackuino.org/). More to come on this in future updates for HAB-4.

### Photography

The outer PVC shell supported two GoPro Hero cameras to capture the entirety of the flight. Notice in the wireframe how the camera mounts are slightly off center to account for the weight displacement caused by the SPOT GPS.

We decided to use a Hero 2 mounted at -45º and a Hero 4 Black positioned to be roughly horizontal.

One of the biggest challenges while preparing HAB-3 was ensuring the cameras would capture the entire flight. To do this, we modified two Mini USB cables to fit under the insulated GoPro casing. A 12800mAh Anker Asto3 battery was stored within the insulated lunch box and provided constant power to the GoPros via these USB cables. The modified cables allowed the casing to maintain its seal.

<div align="middle">
  <iframe src="https://www.flickr.com/photos/pantherasciences/17785846848/in/datetaken-public/player/" width="700" height="394" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

  <iframe src="https://www.flickr.com/photos/pantherasciences/17785844068/in/datetaken-public/player/" width="700" height="394" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

  <iframe src="https://www.flickr.com/photos/pantherasciences/17973720045/in/datetaken-public/player/" width="700" height="394" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

  <iframe src="https://www.flickr.com/photos/pantherasciences/17351118524/in/datetaken-public/player/" width="700" height="394" frameborder="0" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
</div>
