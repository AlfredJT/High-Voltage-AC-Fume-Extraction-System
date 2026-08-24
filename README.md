# High-Voltage AC Fume Extraction System

<img width="1086" height="1448" alt="image" src="https://github.com/user-attachments/assets/7fadaf65-5c03-4d02-9a41-0ce2c3112d35" />


A solder fume extractor built around a repurposed 120V AC vacuum motor, TRIAC-based speed control, and three-stage filtration.

## How it works
<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/0d622164-e882-4f7b-baa0-2b030c7ff348" />


Air gets pulled through the intake and passes through a three-stage filter path — HEPA, then activated carbon, then an electrostatic filter — before reaching the motor. Filtration sits upstream of the motor so the impeller only ever handles clean air, protecting the windings from particulate buildup.

<img width="676" height="600" alt="image" src="https://github.com/user-attachments/assets/1350a908-3832-4d94-b372-39066ab80eca" />


The motor is a salvaged universal AC motor, paired with an impeller and volute housing. Originally, I attempted a far smaller model with a desktop fan but it was far too weak. Universal motors handle static pressure (like pulling air through filters) with a far larger effective range and strength.

Speed is controlled with an analog TRIAC voltage controller and potentiometer, giving continuous adjustment over suction strength and noise instead of a single fixed speed. 

## Electrical safety

Since this runs off mains voltage with hand-wired, salvaged components, safety was a core part of the design:
- GFCI-protected outlet for fault protection
- Dedicated ground wire bonded to the motor housing, spliced and soldered to a proper 3-prong plug wire
- Soldered, individually insulated splices with strain relief
- Multimeter continuity/short testing before every power-on

## Difficulties

The hardest part of this project was probably the designing. The motor is very powerful so it shakes itself, which meant I needed to design really strong supports to hold it tight and in place.

<img width="527" height="426" alt="image" src="https://github.com/user-attachments/assets/615125af-e7f2-4e1f-a901-7a0db597bfe9" />

After some careful measuring, I designed this cage that fit around the motor tightly. It has holes on each side to allow me to screw the motor onto mounts in the enclosure. This took maybe 2-3 small test prints to get a tight fitting cage that could hold the motor rigid. 

<img width="593" height="373" alt="image" src="https://github.com/user-attachments/assets/0533b23a-9765-4101-ac3b-bc9814e8962b" />

Designing the enclosure itself to fit everything neatly was the next biggest challenge. Taking careful measurements of the AC controller so I could design a enclosure, bottom support and roof that would allow for easy handling.


## Closing Thoughts

This model very effectively solved the problem I set out to tackle. I wanted a way to deal with fumes during soldering because they kept getting into my face and posed potential health risks as well. The fan is very strong and only really needs roughly 30V to be incredibly strong and effective. It's allowed me to do more work and for longer while keeping the air in my surroundings good. 


