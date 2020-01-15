---
title: Roboauto
banner: uploads/roboauto.jpg
alt: Our v1 car at the June race.
rank: 6
---

In Spring 2019, IT company Futurice challenged Castor to build a self-driving remote controlled car for their race in June. Futurice sponsored the chassis, and we fit it with a camera, a Jetson Nano single-board computer and the open-source Donkeycar software library. The car learns by mirroring what a human driver does on the track: we first manually drive the car on the track, and gather the camera images and throttle/steering data. Then, a convolutional neural network learns what kind of image necessitates which amount of throttle and steering. The race was held at the Särkänniemi bumper car track between different company and university teams. Castor didn't make it to the podium due to a camera failure the night before, but there's always next year! markku.ai has info on Futurice's car.

Future work with the car include modeling and making new hardware parts, optimizing the camera image for driving on a track, testing different neural network structures, and setting new records at the Tietotalo track.

The car is a good platform for tinkering with deep learning and autonomous driving. Managing Donkeycar is a good experience in working with larger Python projects, and if you haven't used the Unix terminal much, handling Ubuntu will come naturally once you've used the car for a few times. Unlike Amazon's AWS DeepRacer, skills needed also include electrical and machine engineering, since the car must be built and maintained too.

Technical details:

* 1:16 Tamiya TT-02 RC car chassis
* Brushless motor with encoder
* Jetson Nano as computer for the car
* Intel Realsense camera
* Donkeycar, Tensorflow libraries
* AWS for training neural network
* 5-channel RC car controller
* Two-lane track with sidelines and middle line
