---
layout: post
title: 'changing my keyboard part 1'
date: 2024-08-27
tags:
---
Ah the world of split ergonomic keyboards. Where one can get lost for days reading barely seen reddit posts and learning all about how programmers type even though you're not one.

First of all, what's wrong with a standard keyboard? Nothing! It works, it has all the keys. You can learn how to use it fast and efficiently. It seems most of (?) the people who are into this are motivated by repetitive stress injuries, which also leads to alternative layouts like [Colemak](https://colemak.com/). But I'm motivated purely by interest, I'm just here to have fun (thankfully). But the nerd in me perks up when I read about the questionable utility of the standard keyboard. I’ll stick with qwerty, but there are many functional ways that a standard keyboard is just kind of silly. I only hit the spacebar with my right thumb. I never hit right shift. Or caps lock. Or these things < >. Also they're [pretty](https://josefadamcik.github.io/SofleKeyboard/images/IMG_20200613_150327.jpg).

A few years ago, I taught myself how to touch type after hunting and pecking for about 20 years. I’m still not good at it but it really got the juices flowing around that neuroplasticity thing I've been hearing about. And around things big and small that I take for granted too. And there’s a lot of convergence here with many things that I enjoy. Designing is always fun, designing useful things is even more fun, and designing useful electronics is probably the best thing.

So where to start? I didn't want to go [crazy](https://kbd.news/Smiler18-2426.html), nor did I want to go [crazy](http://xahlee.info/kbd/iergo/Maltron_left_right_keypad__David_Cole_2015-11-07.jpg), so 58 keys total seemed manageable (a full keyboard with the numpad and stuff is 104 keys). I watched [this video](https://www.youtube.com/watch?v=7UXsD7nSfDY) and loved the approach--wireless, a hidden microcontroller and battery, and no need for LEDs.

I quickly stumbled upon some software that a lot of people swear by called [Ergogen](https://github.com/ergogen/ergogen). It was fun to use and helped me get my head around the layout and spacing of the keyboard. But probably the biggest drawback for me is that the end result of using this program is PCB footprints spaced out properly in KiCad. No schematic, no traces drawn. So I used Ergogen to get my layout into kicad then reverse engineered it to get the schematic (not very complicated) then layed out the PCB from there. But hey if Ergogen works for you, go for it! I understand that not everyone wants to learn KiCad either, and I'm sure there's some functionality to it that I hadn't tapped.

Anyway there's plenty of information out there so I'm not going to explain ulnar deviation or layers or home row mod-taps. PCBs and parts are arriving on the regular so I'll let you know if it was a horrible waste of time or not.

[![The PCBs are in](/assets/2024/pcbs1-th.jpg){:class="middle"}](/assets/2024/pcbs1.jpg)
[![Stacked PCBs](/assets/2024/pcbs2-th.jpg){:class="middle"}](/assets/2024/pcbs2.jpg)