# Eviscerator
([back](README.md))
<br>Current Version brief overview:
- overhead spinner w/4WD
- ~9in diameter 120g weapon
- weapon motor: 1300KV 2806.5 brushless
- drive consists of 4 1000RPM N20 motors

Final version that won 1st at Texas Robot Combat (TRC) Texas Cup 2024 Plastic Antweight Division:
![Eviscerator V7](ImagesEviscerator/o4.webp)

![Eviscerator V7](ImagesEviscerator/p6.jpg)

Note: This was a late/final version of V7

Results of my match with Bucktoof (Bucktoof pictured below) which colored the ends of my weapon red:
![Eviscerator V7](ImagesEviscerator/p4.jpg)

![Eviscerator V7](ImagesEviscerator/p5.jpg)

Design Journey
---
**V0:**
---

  I initially based my design on Icewave from Battlebots and knew a few key things that I needed my design to have which were: a low center of mass, and wide flat base. To achieve this I decided to try and move the weapon motor above the weapon and have a reduction to give the motor enough torque.

![Eviscerator V0](ImagesEviscerator/n44.png)
![Eviscerator V0](ImagesEviscerator/n43.png)
![Eviscerator V0](ImagesEviscerator/n42.png)
![Eviscerator V0](ImagesEviscerator/n41.png)

---
**V1:**
---

  I thought that I could save weight by having a 3d printing bearing instead of a metal bearing and dived straight into CAD tutorial after tutorial. I would later realize this was a mistake, but it helped me learn how to work with assemblies better. The bearing I was trying to make was a slew bearing, but due to a variety of factors including tolerances and print imperfections, the bearing only worked well while not under heavy load.

![Eviscerator V1](ImagesEviscerator/n40.png)
![Eviscerator V1](ImagesEviscerator/n39.png)
![Eviscerator V2](ImagesEviscerator/n38.png)
![Eviscerator V2](ImagesEviscerator/n37.png)
![Eviscerator V2](ImagesEviscerator/n36.png)

---
**V2:**
---

  I mainly just played around with the design while trying to optimize it and get drive working well and have a good weapon design. I faced 3 main issues, which were that the round belts I was using for drive either slipped a lot or had too much tension and the bot seemed to just flip itself when the spun up and was incapable of self-righting. It also didn't help that the night before one of my early competitions the bot basically exploded itself due to the chassis being insufficient in strength. It might have been V4 that exploded, but I don't remember exactly. Switching to a large diameter metal bearing was heavy, but ultimately lighter than the 3d printed abomination I had been designing and worked great.  

![Eviscerator V3](ImagesEviscerator/n35.png)
![Eviscerator V3](ImagesEviscerator/n34.png)
![Eviscerator V3](ImagesEviscerator/n33.png)
<!-- ![Eviscerator V0](ImagesEviscerator/n32.png) -->
<!-- ![Eviscerator V0](ImagesEviscerator/n31.png) -->
![Eviscerator V3](ImagesEviscerator/n30.jpg)

---
**V3:**
---

  Due to belt slippage and the tiny tires, the bot was very slow. To make matters worse I still had not fixed the spontaneous self-flipping issue. That was when I had started to learn about the Intermediate Axis Theorem, which explained why I was flipping myself, but it would take me a long while to understand it better and resolve that problem. I tried to implement "wings" to increase the moment of inertia (MOI) of my bot along the axis horizontally perpendicular to the main weapon axis, but as it would later turn out, I misread the MOI values by a decimal place, leading me to falsely believe I had a stable ratio.  

![Eviscerator V4](ImagesEviscerator/n29.png)
![Eviscerator V4](ImagesEviscerator/n28.png)
![Eviscerator V4](ImagesEviscerator/n26.png)
![Eviscerator V4](ImagesEviscerator/n25.png)
![Eviscerator V4](ImagesEviscerator/n24.png)
![Eviscerator V4](ImagesEviscerator/n23.png)
![Eviscerator V4](ImagesEviscerator/n22.png)
![Eviscerator V4](ImagesEviscerator/n21.png)
![Eviscerator V4](ImagesEviscerator/n20.jpg)
![Eviscerator V4](ImagesEviscerator/n20.png)

---
**V4:**
---

This was where things started to click. I had given up on the belts and made sure that I could at least drive upside-down to be able to continue the match. Prior to this most of matches went like this:

-> I spun up my weapon

-> I hit my opponent one time

-> I flip over

-> I get stuck and get counted out

So being able to stay in the match was a huge improvement, however my new weapon geometry was highly unfavorable for self-righting with my smaller brushless motor and the pulley on the weapon motor tended to melt away. Nonetheless, this was a major improvement in many facets. 

![Eviscerator V5](ImagesEviscerator/n19.png)
![Eviscerator V5](ImagesEviscerator/n18.png)
![Eviscerator V5](ImagesEviscerator/n17.png)
![Eviscerator V5](ImagesEviscerator/n16.jpg)
![Eviscerator V5](ImagesEviscerator/n15.jpg)
![Eviscerator V5](ImagesEviscerator/n15.png)
![Eviscerator V5](ImagesEviscerator/n14.jpg)
![Eviscerator V5](ImagesEviscerator/n14.png)

---
**V5:**
---

  My biggest failure. In many ways an upgrade in design, but a major step back in performance. The first competition it was in I had to use a substitute motor, which did not have anywhere near enough torque. The weapon was also poorly designed when checked by the Intermediate Axis Theorem and resulted in very short matches that I lost. The cone also did not work at all to help with self-righting, in part due to my terrible weapon geometry. I tried to play around with aerodymanics, but for a variety of reasons there is a negligible benefit. The only positive for this design was I had converted to a monolith chassis with 4 small N20 motors which not only gave me 4WD and better steering, but aslo helped greatly with durability. 

![Eviscerator V5](ImagesEviscerator/n13.png)
![Eviscerator V5](ImagesEviscerator/n12.png)
![Eviscerator V5](ImagesEviscerator/n11.png)
![Eviscerator V5](ImagesEviscerator/n10.png)

---
**V6:**
---

  It was at this time that I reached the cusp below true competitive viability. There were major issues, but they were just points for me to improve. To begin with, I started to learn about the importance of design adaptability for facing specific opponents. A wedge for facing other horizontal spinners and forks for facing vertical spinners and wedges. A tri-blade weapon design allowed for high stability and the new powerful motor had around double the torque. It was around this point that I changed from running a singular 3S Lithium Polymer (Lipo) battery to 2 4S Lipo running in series to gain a higher output voltage. A large dome on top allowed for the bot to roll over due to an intentionally offset COM. The initial dome design did not work however, and although not pictured, was shrunk down prior to competition and adjusted to allow for consistent self-righting. 
	I had also identified an issue with the N20 drive motors. The large gears within their gearbox stuck out a fraction of a millimeter, and when rubbing on the side of the walls retaining them within the chassis caused the motors to bind. The screws holding the forks also liked to work themselves out and were extremely difficult to install and tighten. Additionally, when self-righting, the chassis would spin instead of the weapon, which is what created the instability necessary to rock and self-right using the dome. However, the chassis hitting the ground often broke the forks towards the edge. Due to me not having a wedge and my dome popping off when hitting people (it would break at the layer lines just above where it mounted to the weapon and pop off like an umbrella) I lost a match to a strong competitor who placed in the top 3. That bot was a horizontal ring spinner named Double Stuff. That was an important matched that showcased the newfound stability of my bot and it's newfound performance. Despite this, I essentially lost all of my matches.  

![Eviscerator V6](ImagesEviscerator/n9.png)
![Eviscerator V6](ImagesEviscerator/n8.png)
![Eviscerator V6](ImagesEviscerator/n7.png)
![Eviscerator V6](ImagesEviscerator/n6.png)
![Eviscerator V6](ImagesEviscerator/n5.png)
![Eviscerator V6](ImagesEviscerator/n4.png)
![Eviscerator V6](ImagesEviscerator/n3.png)

---
**V7:**
---

![Eviscerator V7](ImagesEviscerator/n2.png)
![Eviscerator V7](ImagesEviscerator/n1.png)
![Eviscerator V7](ImagesEviscerator/p1.jpg)
![Eviscerator V7](ImagesEviscerator/p2.jpg)
![Eviscerator V7](ImagesEviscerator/p3.jpg)
