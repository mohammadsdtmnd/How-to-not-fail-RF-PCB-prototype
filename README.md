# How-to-not-fail-RF-PCB-prototype
I've made GPS amplifier for hobby time, it failed. I've learned what I should not have done again to prevent failure. My motivation for doing this was to see the GPS signal spectrum. :) Note I had tried my best to minimize cost. For example by eliminating stensil and soldermask. Though still PCB is metalized with bot layer gnd. I think I could also not making it metalized. Making it stiching with thin wire, instead. Since metalizing caused my manufacturer to prolong a long time.

**You can look at schematic and PCB and see these strength:**

+ Simple
+ High gain
+ Extremely compact design
+ 0.25mm PCB thickness chosen to decrease track and match them to RF amps
+ small footprint which also causes them to be more stable because of less leakage

This compact design chosen to minimize distortion in GPS RF signal.

**PCB Weakness:**
  
+ 0.5mm pitch footprint is small for handsoldering
+ Amplifier package does not have edge lead tail, to make you certain about solder connectivity

But other than foot print and devices package chosen, tools are extremely important:

**Tools weakness:**
  
+ Bulky 60W iron used and caused catastrophy there :(
+ Use of thick solder wire
+ Lower melting point solder plus hot air could help success of assmbling but was missed

**Tools strength:**
  
+ Precise tweezer
+ Good lenz for zooming

And the thing I had really missed was to be patience to waint until accessing at least SMD specialized iron.

**Here is manufactured PCB:**

![IMG_20250624_083752](https://github.com/user-attachments/assets/3fd29ae7-df1e-40a6-a53c-563fe9e2a456)
![IMG_20250624_113647](https://github.com/user-attachments/assets/d582aef8-2aa4-4ab6-8d26-b90def981c93)


**Prepaird workbench:**

![IMG_20250905_204330](https://github.com/user-attachments/assets/aa4f5fbe-a757-4a29-89ca-714252a844c0)



**First try success:**

![IMG_20250905_214846](https://github.com/user-attachments/assets/303cb038-166b-42fc-a3e8-f6b6cfd96043)


**but the secound not:**

![IMG_20250905_232118](https://github.com/user-attachments/assets/27b2e5fb-d540-406e-90f0-22d07de4d401)

I had placed tip of my bulky iron beneath the IC and the resin of PCB burnd!! Though I've been dissapointed. I told OK. I will make the secound PCB with success.
The secound PCB had inherent wrong. It missed one track in sensitive area, Under amplifier. :(

![IMG_20250906_100344](https://github.com/user-attachments/assets/d7764e4c-b13e-4eae-ace6-3e4983697bfc)
But I managed to handle it with 0.1mm Wire, Low melting solder and Hot air

![IMG_20250907_084615](https://github.com/user-attachments/assets/27e2cb02-078c-4bcb-9a10-d3f575117920)
![IMG_20250906_100121](https://github.com/user-attachments/assets/4aff40d4-5087-497a-a7c3-0953717914b2)



**And the result was promising:**

![IMG_20250907_091124](https://github.com/user-attachments/assets/06fdc8c7-01cb-4ff0-80ed-434fa9533dbc)

Though I've assembled all amplifier with success. Then I tried to place other components with my bulky iron and wire solder. Then another tack removed and caused to one amplifier being detached.
![IMG_20250907_230608](https://github.com/user-attachments/assets/52244024-8f82-4a0d-a5bf-35181737087a)

Now next time I will be sure to use smd iron.
Then all components should have more than 1mm pitch for handsoldering. Otherwise I should have sharp tip iron with low melting point solder if possible. Plus patience.
