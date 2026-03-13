# AGRAV

**Personal Ground-Effect Vehicle Concept Sandbox**

`AGRAV` is an experimental browser-based engineering sandbox exploring the feasibility of **personal-scale ground-effect (WIG) vehicles**.

Rather than proposing a fictional anti-gravity bike, the system models a **low-altitude aerodynamic vehicle** that rides on compressed airflow near the surface.
The tool allows rapid exploration of how mass, speed, lift coefficient, and ground-effect amplification interact to determine whether a compact vehicle could sustain flight within the ground-effect regime.

---

## Concept: Personal WIG Vehicle

Ground-effect vehicles operate in the narrow aerodynamic region close to a surface where lift efficiency increases due to restricted airflow beneath the lifting surface.

AGRAV explores whether this phenomenon could scale down to a **single-pilot mobility platform**.

Instead of focusing on cinematic hover vehicles, the project treats the craft as a **small ekranoplan-like system**, where forward velocity and aerodynamic lift remain essential.

---

## Simulation Model

The sandbox uses simplified aerodynamic relationships to estimate lift, drag, and propulsion requirements:

Lift

```
L = 0.5 · ρ · V² · C_L · S · WIG
```

Drag

```
D = D_parasitic + D_induced
```

Power

```
P ≈ (Drag × Velocity) / Propulsion Efficiency
```

The model is intentionally simplified to make parameter relationships visually understandable rather than to produce certification-grade predictions.

---

## Interactive Design Sandbox

The browser interface allows users to modify core parameters such as:

* Total system mass (pilot + craft)
* Cruise speed in ground-effect flight
* Lift coefficient and effective lifting area
* Ground-effect amplification factor
* Aspect ratio and parasitic drag
* Propulsion efficiency

Outputs are visualized in real time, providing estimates of:

* Required lifting surface
* Required thrust
* Power demand
* Stability control margin

---

## Purpose

AGRAV is not a production vehicle design.

It is a **concept exploration tool** intended to:

* visualize aerodynamic constraints for personal WIG vehicles
* explore scaling limits of ground-effect flight
* provide an intuitive educational interface for experimental mobility concepts

---

## Status

Experimental concept UI.

Not intended for real-world flight design or engineering certification.

---

## License

© DIMProductions