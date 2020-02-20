# [Modules](#modules) | [About](#about) | [Contact](#contact)

## Modules

Every module is released under CC Attribution Share Alike 4.0. With this license anyone is free to build, sell, or modify these designs as long as they share any changes they make under the same license. 

### Stable

#### [Drone](https://simplecircuitsmodular.github.io/drone/)

This module is the first true analog module I have designed. Based on a reverse avalanche transistor oscillator, the module offers a saw wave drone with built in passive filtering. It features 3 oscillators and a tone control but requires amplification to reach modular levels.

#### [Drums](https://simplecircuitsmodular.github.io/drums/)

Two ATMega based drum modules offer a simple, low power draw method to add some drums to your rack. Both modules use the same board, but have different panels and code loaded onto them.

#### [Passives](https://simplecircuitsmodular.github.io/passive/)

These are simple passive modules shared for people who don't want to deal with designing panels themselves. They're not powered and are great beginner/learn to solder projects.

### In Development

#### [Master Clock](https://simplecircuitsmodular.github.io/masterClock/)

This module packs a bunch of clock utilities into one small package. The large arcade button makes it easy to set the tempo with the tap of your finger. An external clock input allows the module to function as a traditional clock multiplier and divider. The rate knob has two modes. In mode 1 it modifies the base clock rate allowing you to speed up or slow down the tempo of an external clock or tap tempo. In mode 2 the knob sets the clock rate directly.

#### [Arcade Sequencer](https://simplecircuitsmodular.github.io/bads/)

This module offers a 6 channel drum sequencer with 3-64 steps. Each function is mapped to a single piece of hardware, and it can be synced to an internal or external clock. An additional set of jacks allows this module to record other trigger sources for playback as well.

#### [Euclid](https://simplecircuitsmodular.github.io/euclid/)

Based on an Arduino mega, this 6 channel Euclidian sequencer gives full control over the creation of Euclidian rhythms including changing pattern length and rotating patterns. Note that this module is still in the prototype phase and is very rough in its current state.

#### [DigiMult](https://simplecircuitsmodular.github.io/DigiMult/)

A programable digital utility module with 4 potentiometer, 2 DAC outputs, a trigger input, and an analog input. Based on the ATTiny84.

#### [Sub Oscillator](https://simplecircuitsmodular.github.io/octave/)

My take on the common 4024 sub oscillator. This module offers -1, -2, and -3 octave outputs (selectable via a rotary switch), volume control, sub enable switch, and an input through. This allows the sub oscillator to be easily mixed, added, or removed. This is another true analog module.

#### [XY-Z](https://simplecircuitsmodular.github.io/XY-Z/)

This is a 16 step 2 dimensional CV sequencer. Each step is controlled by a potentiometer. The pots are laid out in a 4x4 grid, and 2 inputs (X and Y) allow you to move between rows and columns.


## About

My name is Nick Biederman. I started Simple Circuits Modular to share my designs with others interested in SynthDIY. My focus has always been on sharing my work openly so others can build from it. Every circuit board, schematic, or piece of code I create is uploaded publicly to Simple Circuits Modular's GitHub. I encourage you to build these modules yourself, improve my designs, and share your modifications with the world. This website is hosted through GitHub, and each module page has a link directly to the repository.

All the information you need to build these modules yourself has been made available, but I understand that some people prefer to purchase panels, PCBs, or complete modules. If you'd like to purchase PCBs, panels, or you're looking for a complete module you can contact me at the email address below. 

There's many great online resources for SynthDIY information, but my personal favorite is the [Synth DIY Subreddit.](https://www.reddit.com/r/synthdiy) I source most of my components from [Mouser](https://www.mouser.com) and [Modular Addict](https://modularaddict.com/). I buy my PCBs from [PCBWay](https://www.pcbway.com/). I make my panels out of 1/8" acrylic sheet I cut on a laser cutter at the Columbus Idea Foundry, a large makerspace in central Ohio.

#### A note on best practices

I am completely self taught in the field of hardware design. This project has largely served as a way for me to experiment and become familiar with the process of designing robust electronic circuits. My lack of experience is evident in many of my early designs, and this has lead to some poor coding practices to interface firmware with hardwaere that is not best suited to the application. A lot of the code I have posted here would never pass a code review and many of my circuits lack the protection you'd expect to see on a commercial module. I am in the process of revisiting early projects to improve the hardware and create robust modules. The vast majority of these modules operate at a 5v logic level. This means they are unlikely to damage commercial modules that are designed to work with the semistandard 10v PP Eurorack audio levels and +/-8 to 10v control levels, but the lack of proper buffering and protection on inputs and outputs may lead to issues when intigrated into a standard Eurorack system.

## Contact

If you'd like to reach me directly you can email me at [nbiederman97@gmail.com.](mailto:nbiederman97@gmail.com)
