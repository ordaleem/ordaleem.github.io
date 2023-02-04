---
layout: post
title: 'dintree 106 step sequencer'
date: 2021-05-28
tags:
- modular synth build
---	
<p class="aligncenter">
<a href="/assets/2021/d-front.jpg"><img src="/assets/2021/d-front-th.jpg"></a>
<a href="/assets/2021/d-back.jpg"><img src="/assets/2021/d-back-th.jpg"></a><br />
</p>	
<p>
This is the dintree 106 step sequencer, built on strip board from a schematic. Andrew (dintree boy) does a great job summing up the module over on <a href="https://github.com/hires/Dintree">their page</a>, so I won't repeat any of that, but I'd like to share my strategies for a couple neat light mods.
</p>
<p>
The pots are wired from -5 to +5V with an optional input per step. I used a negative 5V voltage regulator to wire that voltage to one side of the pots, and hooked the pots to the switching side of the optional input jack. Andrew mentions regulating the 4052s' power voltages to be able to pass a synth signal though them. In my case I dropped all voltages going into the multiplexers (either from the +/-5V pots or an input signal) with a voltage divider, then instead of just buffering the outputs I amplified them back up to their original levels. This conveniently uses the same value resistors between input (voltage divider) and output (op-amp gain).
</p>
<p>
I etched the panel for this one. I spraypainted the back of the panel black in a failed attempt to destroy that ugly FR4 green color. Does anyone know a good source for colored copper clad?
</p>
<p>
Anyway, once I figured out how the hell to flash a program onto a microcontroller it worked well! It's fun fast, fun slow... The step inputs really add to the functionality. I'd probably build it on two boards if I could do it again, this thing is deep.
</p>