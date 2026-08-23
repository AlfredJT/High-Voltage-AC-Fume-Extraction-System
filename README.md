# High-Voltage AC Fume Extraction System

A solder fume extractor built around a repurposed 120V AC vacuum motor, TRIAC-based speed control, and three-stage filtration.

## How it works

Air gets pulled through the intake and passes through a three-stage filter path — HEPA, then activated carbon, then an electrostatic filter — before reaching the motor. Filtration sits upstream of the motor so the impeller only ever handles clean air, protecting the windings from particulate buildup.

The motor is a salvaged universal AC motor, kept intact with its factory-matched impeller and volute housing rather than rebuilt from scratch — universal motors handle static pressure (like pulling air through filters) far better than a standard axial fan would.

Speed is controlled with an analog TRIAC voltage controller and potentiometer, giving continuous adjustment over suction strength and noise instead of a single fixed speed. Note: the dial doesn't function as an off switch — it modulates the AC waveform, not peak voltage, so the circuit stays live at any setting above zero.

## Electrical safety

Since this runs off mains voltage with hand-wired, salvaged components, safety was a core part of the design:
- GFCI-protected outlet for fault protection
- Dedicated ground wire bonded to the motor housing, wired into a proper 3-prong plug
- Soldered, individually insulated splices with strain relief
- Multimeter continuity/short testing before every power-on

## Notes

- Motor sits downstream of the filter stack (pull-through), which protects it from particulate exposure and gives more even suction at the intake.
- Capture strength drops off sharply with distance from the intake, so the hood is designed to be used close to the work rather than relying on raw motor power.

**Skills:** TRIAC motor control, mains power circuit design, high-voltage safety design, multi-stage filtration, Fusion 360.
