# ICubeX-mapper-juce

A JUCE-based sensor interfacing framework with libmapper bindings.

It started off as an interface application between I-CubeX (www.icubex.com) Sensors and libmapper, but has since been extended as a general sensor visualization.

Currently it is a sandbox project as part of experimentation with the JUCE framework and to aid in the architectural design of the system. Major refactoring will be expected.

Some Goals:

- interface with other microcontrollers
- apply signal visualization, analysis, and processing components
- use the above components to perform higher level feature extraction
- more usable interface for connecting with mapping tools, and/or built in mapping tools


Current development configuration:

Software:
- Mac OSX
- Juce 4.0.x (required modules are included with code base)

Hardware:
- I-CubeX USB microDig (or Wi-Microdig)
- Some sensors of your choice

Software:
- libmapper (https://github.com/malloch/libmapper)
- ICubeX Connect (http://infusionsystems.com/connectmac)

Developed as part of the requirements of MUMT609, McGill University
Johnty Wang (johntywang@gmail.com)
Input Devices and Music Interactions Lab, McGill University
Apr 2015
