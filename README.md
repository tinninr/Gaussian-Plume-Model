# Air Pollution Modelling with the Gaussian Plume Model

This project explores how pollutants disperse from an industrial stack using the Gaussian plume model, implemented in Python.

---

## Project Overview

An industrial facility emits pollutants into the atmosphere. This model simulates ground-level concentrations and evaluates environmental risk at different locations.

### Scenario:
- Emission rate: 50 g/s  
- Stack height: 50 m  
- Wind speed: 5 m/s  
- Stability class: D (neutral)  
- Domain: 0–5 km downwind  

---

## Example Receptor Locations

| Site | Location (x, y) | Description | Result |
|------|----------------|------------|--------|
| A | (1000 m, 0 m) | Primary school | ❌ Exceeds limit |
| B | (2000 m, 300 m) | Residential area | ✅ Safe |
| C | (500 m, 0 m) | Industrial boundary | ✅ Safe |

---

## Key Insights

- Peak concentration occurs downwind, not at the source  
- Centreline locations experience the highest exposure  
- Atmospheric stability affects plume spread and mixing  
- Higher wind speeds reduce concentrations (inverse relationship)  

---

## Model Limitations

- Assumes steady wind and constant conditions  
- Flat terrain (no buildings or obstacles)  
- No chemical reactions or deposition  

---

## Project Structure

gaussian-plume-model/
├── notebook/ # analysis notebook
├── src/ # reusable plume model code

---

## What I Learned

This project helped me understand how air pollution models are used to assess environmental risk and how factors like stability and wind speed influence pollutant dispersion.

---

## Tools Used

- Python  
- NumPy  
- Matplotlib 

