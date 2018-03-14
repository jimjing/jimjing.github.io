---
layout: post
title: Make a small benchtop power supply
key: 20180313
tags:
  - Tool
  - Hardware
  - Electrical
  - Mechanical
---
I didn't move my benchtop power supply with me when I moved to an apartment.
So the first thing I would like to make is a power supply for all my future electronic projects.
I got this [adjustable voltage regulator](https://www.amazon.com/gp/product/B01DZSFDE6/) long time ago, which is perfect for this purpose.
To protect the board and make it safer to use, I got this [enclosure](https://www.amazon.com/gp/product/B0725ZQGVP).

[![voltage regulator](/assets/images/mini_power_supply/voltage_regulator.png){:width="256px"}](https://www.amazon.com/gp/product/B01DZSFDE6/)
[![enclosure](/assets/images/mini_power_supply/enclosure.png){:width="256px"}](https://www.amazon.com/gp/product/B0725ZQGVP)

With my newly built [mini drill station]({{ site.baseurl }}{% post_url 2018-03-11-make-a-mini-drill-station %}), I am able to drill some holes on two sides of the enclosure to install two female 5.5mm-2.1mm coaxial power connectors: one for input, one for output.
With these connectors, I can use an old laptop power supply for the input and make different output cables (alligator clips, banana connectors, *etc*.).

![connector](/assets/images/mini_power_supply/connector.jpg){:width="512px"}

Since the enclosure is deeper than I wanted, I drilled 1/8" holes at the end of four 1/4" nylon bolts and use them to extend the buttons on the regulator board.

![botls](/assets/images/mini_power_supply/bolts.jpg){:width="512px"}

Finally, I drilled four 1/4" holes on the cover of the enclosure for the bolts to go through and some 1/8" holes to provide ventilation.
Maybe in the future I will add a small fan if overheating is an issue.

![cover](/assets/images/mini_power_supply/cover.jpg){:width="512px"}

Inside of the enclosure

![inside](/assets/images/mini_power_supply/inside.jpg){:width="512px"}

Final assembly

![front_view](/assets/images/mini_power_supply/front_view.jpg){:width="512px"}

With laptop power supply as input (left) and alligator clips as output (right)

![wiring](/assets/images/mini_power_supply/wiring.jpg){:width="512px"}

The output range of the voltage regulator is 0-32V with 5A.

![demo1](/assets/images/mini_power_supply/demo1.jpg){:width="256px"}
![demo2](/assets/images/mini_power_supply/demo2.jpg){:width="256px"}
