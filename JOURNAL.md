---
title: "USB-C2easypads"
github: "https://github.com/Small-doge128/USB-C2easypads"
description: "A really small and simple USB-C PCB with 2 output pads. It's for 12V (47k resistor), but if you want higher voltage, buy a different Rset resistor and fuse."
created_at: "2026-10-09"
total_time: "13h"
---

# July 30, 2026: Starting or am I
<!-- fabricate:entry 308 -->

I made the whole schematic with all the necessary protection. I got the right values for the resistors and capacitors and added a chip that says to the USB-C port to draw more power and the 47k resistor makes it, so it draws 12V and not some crazy numbers. I already got the USB-C port on me, so just some small stuff to buy. Last I made some stuff for the repo.

Small_doge

![image](https://cdn.hackclub.com/019fb33c-6058-7ae0-a01e-378fb8012be6/image.png)

**Total time spent: 1h 30m**

# July 31, 2026: Locked in
<!-- fabricate:entry 305 -->

I got locked in. First I made the schematic cleaner for better future use and I'll add a silkscreen table of current:Rset resistor. I found all for the parts I need at home or LCSC. All of that was real hard work :).

Small_doge 

![image](https://cdn.hackclub.com/019fb9c1-b457-73f1-b2af-4144dc5241bc/image.png)

**Total time spent: 1h 36m**

# July 31, 2026 (entry 2): Now the schematic is done
<!-- fabricate:entry 306 -->

First I made more changes I actually read the actual measurements from a data sheet, so it should be right. I found some resistors and capacitors at home, so money saved. The PCB editor chapter has started.

Small_doge

![image](https://cdn.hackclub.com/019fb751-d985-746d-9361-3e354818755a/image.png)

**Total time spent: 1h 24m**

# July 31, 2026 (entry 3): Schematic done?
<!-- fabricate:entry 307 -->

So the schematic is done and I also tried finding some parts. I did find some, but maybe we have some parts at home, so I'll need to check that. I also started with the PCB.

Small_doge

![image](https://cdn.hackclub.com/019fb700-424e-71ce-9f74-9701dbb85a28/image.png)

**Total time spent: 42m**

# August 4, 2026: PCB editor
<!-- fabricate:entry 304 -->

I played around a little with the PCB editor and made this this may be the final model I don't know. I do need to find the polyfuse, because of that I'll need to change it a little bit, but still pretty small, but packed with features.

Small_doge

![image](https://cdn.hackclub.com/019fcc8b-8892-71e3-b923-a3258877d992/image.png)

![image](https://cdn.hackclub.com/019fcc8c-2bda-76d4-8cad-39fbbc937b2e/image.png)

**Total time spent: 1h 12m**

# August 7, 2026: Almost
<!-- fabricate:entry 303 -->

I made the whole PCB cleaner, better and found the right polyfuse for the job. Then I saw that I had in some resistors wrong casings, so I fixed that. The only thing to fix is adding copper fill.

Small_doge

![image](https://cdn.hackclub.com/019fdce5-d83f-735c-8884-70953f310bc0/image.png)

**Total time spent: 1h**

# August 8, 2026: Done with ki cad
<!-- fabricate:entry 302 -->

I rechecked everything found some errors, so I fixed that. Now there's no errors by me and DRC and 0 unrouted. I added stability and better ground with copper fills.

Small_doge

![image](https://cdn.hackclub.com/019fe0c1-b591-764a-9db4-471029e22824/image.png)

**Total time spent: 24m**

# August 9, 2026: Big problem
<!-- fabricate:entry 301 -->

First I made the BOM and adjusted the repo. When I rechecked all of the parts I found a bad polyfuse and diode for the job, so that will be adjusted, which means changing the price and maybe even changing the PCB. I also chose a stencil for easier soldering.

Small_doge

![image](https://cdn.hackclub.com/019fe578-57ba-7891-8961-01175995dca8/image.png)

**Total time spent: 1h 6m**

# August 10, 2026: Price
<!-- fabricate:entry 299 -->

First I checked if the SOD-323HE is bigger and it is, but I have the hand soldering footprint, which is longer, so it will work. Then I checked the PCB and I change a text from silkscreen to user drawings.
After that I looked what is cheaper to buy PCBway or JLCPCB and it was PCBway. I've never bought from PCBway but I'll learn along the way.

Small_doge

![image](https://cdn.hackclub.com/019feb12-490a-73b2-8933-6090518a44e0/image.png)

![image](https://cdn.hackclub.com/019feb13-80e5-75d6-9aaf-60e894c9e5fe/image.png)

**Total time spent: 1h 24m**

# August 10, 2026 (entry 2): I solved the problem
<!-- fabricate:entry 300 -->

I solved it I just need to take some time to learn again the words for polyfuse and TVS diode like clamping voltage, breakdown voltage and many more and I nailed it, because I found the ones I wanted and they're the same package, so nothing to change on the PCB and it got the right measurements. All I need to do now is just some clean up and I'm ready to go.

Small_doge

![image](https://cdn.hackclub.com/019feae7-24c6-79f6-8ce1-3721df709419/image.png)

**Total time spent: 1h 12m**

# August 11, 2026: Done?
<!-- fabricate:entry 298 -->

First I checked the prices again and the total was big on LCSC, so I sat and watched in sadness, that almost no hours from this project will go to a new laptop. Then I adjusted the repo, added a BOM in the readme and adjusted the BOM.csv that I had before that's all.

Small_doge

![image](https://cdn.hackclub.com/019fefa4-b7bf-7776-975c-9ed843f005d2/image.png)

**Total time spent: 1h**

# August 12, 2026: Done
<!-- fabricate:entry 297 -->

I rechecked everything again i know just to make sure even with my brother. I remembered that the capacitor shall be a 1uf and not 100nf, but for now it will be 100nf. I changed some words in the repo and I hope everything is right.

Small_doge

![image](https://cdn.hackclub.com/019ff551-d7f2-75ce-a5aa-1e4457e3ce89/image.png)

**Total time spent: 30m**
