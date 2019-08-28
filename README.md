# [Modules](#modules) | [About](#about) | [Contact](#contact)

## Modules

Every module is released under CC Attribution Share Alike 4.0. With this license anyone is free to build, sell, or modify these designs as long as they share any changes they make under the same license.

I'm currently in the process of fully documenting each module and transferring ownership from my personal GitHub to the Simple Circuits Modular organization. 

### Stable

#### [Drone](https://simplecircuitsmodular.github.io/drone/)

This module is the only pure analog module I've designed so far. Based on a reverse avalanche transistor oscillator, the module offers a saw wave drone with built in passive filtering. It features 3 oscillators and a tone control but requires amplification to reach modular levels.

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

Based on an Arduino mega, this 6 channel Euclidian sequencer gives full control over the creation of euclidian rhythms including changing pattern length and rotating patterns. Note that this module is still in the prototype phase and is very rough in its current state.

## About

My name is Nick Biederman. I started Simple Circuits Modular to share my designs with others interested in SynthDIY. My focus has always been on sharing my work openly so others can build from it. Every circuit board, schematic, or piece of code I create is uploaded publicly to Simple Circuits Modular's GitHub. I encourage you to build these modules yourself, improve my designs, and share your modifications with the world. This website is hosted through GitHub, and each module page has a link directly to the repository.

All the information you need to build these modules yourself has been made available, but I understand that some people prefer to purchase panels, PCBs, or complete modules. If you'd like to purchase PCBs, panels, or you're looking for a complete module you can contact me at the email address below. 

There's many great online resources for SynthDIY information, but my personal favorite is the [Synth DIY Subreddit.](https://www.reddit.com/r/synthdiy) I source most of my components from [Mouser](https://www.mouser.com) and [Modular Addict](https://modularaddict.com/). I buy my PCBs from [PCBWay](https://www.pcbway.com/). I make my panels out of 1/8" acrylic sheet I cut on a laser cutter at the Columbus Idea Foundry, a large makerspace in central Ohio.

#### A note on best practices

I've sort of thrown best practice to the wind with this project. I started designing and building these modules for fun, not to make indestructable, top of the line modules. I spend all day writing code that handles every edge case and possible user input I can come up with, and it gets tedious after a while. I don't have any formal training or professional experince with circuit design. While I know what I'm doing isn't perfect and I do know how to properly protect inputs and buffer outputs, I don't really care. Sometimes I just want to make something that works, and this project reflects that. A lot of the code I have posted here would never pass a code review and my circuits lack the protection you'd expect to see on a commercial module. You probably won't break anything if you use the modules the way they're intended to be used, but I can't gaurentee you won't let some magic smoke out at some point. Use these modules at your own risk.

## Contact

If you'd like to reach me directly you can email me at [nbiederman97@gmail.com.](mailto:nbiederman97@gmail.com)
