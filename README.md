# How-to-not-fail-RF-PCB-prototype
I've made GPS amplifier for hobby time, it failed. I've learned what I should not have done again to prevent failure. My motivation for doing this was to see the GPS signal spectrum. :)
You can look at schematic and PCB and see these strength:
+ Simple
+ High gain
+ Extremely compact design
+ 0.25mm PCB thickness chosen to decrease track and match them to RF amps small footprint which also causes them to be more stable because of less leakage
This compact design chosen to minimize distortion in GPS RF signal.
Weakness:
+ 0.5mm pitch footprint which is small for handsoldering
+ Amplifier package does not have edge lead tail to make you certain about solder connectivity
But other than foot print and devices package chosen, tools are extremely important:
Tools weakness:
+ Bulky 60W iron used and caused catastrophy there :(
+ Use of thick solder wire
+ Lower melting point solder plus hot air could help success of assmbling but was missed
Tools strength:
+ Precise tweezer
+ Good lenz for zooming
And the thing I had really missed was to be patience to waint until accessing at least SMD specialized iron.

**Here is manufactured PCB:**
![IMG_20250624_083752](https://github.com/user-attachments/assets/8e78c9e2-b2cd-4b41-af41-df1265cf875f)
![IMG_20250624_113647](https://github.com/user-attachments/assets/315ea4e8-9e94-4dab-bcd9-b8652218518a)

**Prepaird workbench:**
![IMG_20250905_204330](https://github.com/user-attachments/assets/fe51be2c-062c-4b2a-aa13-b24c9f3f2ecb)

**First try success:**
![IMG_20250905_214846](https://github.com/user-attachments/assets/f469aa5f-2dd0-4288-9fab-4b31b325d452)
**but the secound not:**
![IMG_20250905_232118](https://github.com/user-attachments/assets/2f8507a4-beaa-4d74-8245-24f91b3cd3ac)
I had placed tip of my bulky iron beneath the IC and the resin of PCB burnd!! Though I've been dissapointed. I told OK. I will make the secound PCB with success.
The secound PCB had inherent wrong. It missed one track in sensitive area, Under amplifier. :(
![IMG_20250906_100344](https://github.com/user-attachments/assets/6d7473c9-5858-4d10-9cb3-789918a21652)
But I managed to handle it with 0.1mm Wire, Low melting solder and Hot air
![IMG_20250906_100121](https://github.com/user-attachments/assets/b1072d5a-c1ed-46f5-84fb-72e0b9b5929a)
![IMG_20250907_084615](https://github.com/user-attachments/assets/0375b59e-15a7-4296-a5c1-6c118d046a73)

**And the result was promising:**
![IMG_20250907_091124](https://github.com/user-attachments/assets/2d81c0c1-ee9e-42c4-ab93-c215d217f33a)
Though I've assembled all amplifier with success. Then I tried to place other components with my bulky iron and wire solder. Then another tack removed and caused to one amplifier being detached.

Now next time I will be sure to use smd iron.
Then all components should have more than 1mm pitch for handsoldering. Otherwise I should have sharp tip iron with low melting point solder if possible. Plus patience.
