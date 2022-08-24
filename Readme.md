# The Handler: My Eight Key Handheld "Dream" Keyboard

![Typing On The Mark VII](/images/type.gif)

## Background

I am a heavy user of a proprietary one-handed keyboard system. Recent maintenance issues and the lack of user serviceability have turned my attention to creating a longer term solution. The result is the Handler Mark VII, my current prototype for a single-handed (110 mm length, 40mm girth) "dream" keyboard, the name referencing its proprietary competitor and [fashion doll](https://en.wikipedia.org/wiki/Ruth_Handler) aesthetics. 

## Case

The case was 3D printed in two parts on my CR-10 using [3DFillies Pink PLA+](https://3dfillies.com/plaplus-filament-175mm-1kg).

The case uses [M4 15mm nuts and bolts](https://www.bunnings.com.au/pinnacle-m4-x-15mm-zinc-plated-round-head-bolts-and-nuts-18-pack_p0168393) that are easily sourced here in Australia from the big box hardware store. I am unsure of their availability in other markets.

The case should be printed in two sessions with a layer height of .1mm. The bottom part of the case should be printed vertically so that the closed end touches the base plate. The top part of the case should be printed flat side down. Supports should only be needed in the shafts for the nuts.

## Microcontroller

The current case is designed to house a Pro Micro form-factor Arduino.

##Wiring

Wiring, as you can see here, was by hand. Care needs to be taken so as to not have any wires stray to the outside of the the keys as one of the flaws of the current version is how thin the vertical walls are, with the the keys almost touching them as is. I am currently using a column to row diode arrangement with two key columns and four key rows.

## Caps and Switches

The Mark VII uses clear Gateron switches. I would like to experiment with a version using Chocs. At the moment, the Gaterons are the lightest switches I was able to source. The caps are from E-Element.

## Software 

The current prototype uses QMK and the [Ardux](https://ardux.io) layout. 

## Todo

While there are some issues with the physical unit I would like to address such as the aforementioned thin walls, I'd like to do a few more software iterations before returning to the hardware. 

I am unsure of the direction I want the software to take next. I may double down on minimalism and refine [Arduix](https://github.com/trevorjay/arduix), my "bare-metal" Ardux implementation, or I may embrace what I otherwise find a disturbing trend within the keyboard community towards beefier microprocessors and move towards a platform like the Raspberry Pi Pico. That would allow me to implement a full lisp machine onboard the keyboard, which I must admit is an enticing prospect.

## Licensing 

All of the designs available here are made available under a Creative commons license. See the  license file.
