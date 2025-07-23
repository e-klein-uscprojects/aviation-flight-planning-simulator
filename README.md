# Aviation Flight Planning Simulator

I am a commercial and agricultural pilot with nearly two decades of experience operating across California and the western United States. I have flown piston and turbine-class aircraft across varied terrain and weather systems, including repeated CJ3 missions into and out of Southern California airspace. The Citation CJ3’s performance profile—its fuel consumption, routing flexibility, and cruise capabilities—has informed the technical framework presented here.

This repository offers a simulation of flight planning logic using Python. It draws from routine operational procedures, including wind and precipitation adjustments, fuel burn calculations, and visibility-based arrival assessments. The example flight modeled here reflects a CJ3 mission from Oakland International (KOAK) to Van Nuys Airport (KVNY), incorporating meteorological factors and fuel planning thresholds in a way that mirrors structured cockpit decision-making.

The work is not intended for dispatch use, nor is it a substitute for certified planning systems. But in documenting how turbine-class aircraft are prepared for regional flights—including the assumptions, estimates, and risk checks—I have found the process both technically useful and personally reflective. These notebooks don’t simply recreate data—they reorganize judgment into procedural form.

## Repository Structure

- `planning/`:  
   └─ `cj3_flight_plan_koak_kvny.ipynb`: Citation CJ3 routing logic, adjusted fuel calculations, and visibility planning for KOAK to KVNY  
- `data/`:  
   └─ `aircraft_profiles.csv`: Structured performance data for representative aircraft types  
   └─ `sample_weather_forecast.csv`: Simplified METAR-style conditions for planning inputs  
- `docs/`:  
   └─ `pilot_workflow_notes.md`: Written overview of flight procedures and decision structure adapted from operational experience

## Objective

To restructure flight planning logic in technical form, using code to reflect the kind of measured preparation involved in route planning, fuel modeling, and weather impact assessment. While simplified, the simulation remains grounded in experience and attentive to detail.

