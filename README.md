# Aviation Flight Planning Simulator

I am a commercial and agricultural pilot with nearly two decades of experience navigating varied aircraft under dynamic conditions across California and the western United States. I have worked in both piston and turbine-class platforms, including the Citation CJ3, conducting flight planning across a broad range of operational contexts—regional trips, agricultural missions, and business-class legs under IFR and VFR.

The modeling work represented here reflects an interest in documenting the judgment behind those decisions: the route planning, the weather assessments, and the structured fuel logic required to operate effectively. I do not claim that this simulation mirrors full-scale flight dispatch architecture, nor is it intended for use in active operations. What it does reflect is the procedural mindset required to navigate aircraft responsibly under real-world constraints.

The notebooks included simulate routing logic, fuel consumption modeling, weather interpretation, and visibility thresholds adapted from experience across both controlled and uncontrolled airspace. Each simulation is structured to document the core decisions that precede flight—not just airspeed and fuel burn, but weather impact and visibility risk. 

I have found the opportunity to model these workflows—however simplified—instructive. The act of documenting operational logic in code has allowed me to approach aviation from a new angle: one that is quiet, deliberate, and structured. That effort is what this repository represents.

## Repository Structure

- `planning/`:  
   └─ `flight_plan_generator.ipynb`: CJ3 route simulation from San Carlos to Monterey  
   └─ `cj3_flight_plan_koak_kvny.ipynb`: CJ3 fuel modeling from Oakland to Van Nuys with visibility risk  
- `data/`:  
   └─ `aircraft_profiles.csv`: Performance metrics for selected aircraft types  
   └─ `sample_weather_forecast.csv`: Simulated weather input for METAR-style planning  
- `docs/`:  
   └─ `pilot_workflow_notes.md`: Narrative description of flight logic applied during agricultural and commercial missions

## Objective

To simulate and document the structure of flight planning logic used in general aviation and regional air operations. While simplified for demonstration, the framework reflects the kind of discipline and measured reasoning used by working pilots in active environments.
