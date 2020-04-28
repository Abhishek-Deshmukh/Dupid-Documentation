# Simulation

A Dupid Simulation can be initiated using the following commands:
```
from Dupid.dupid import Simulation
test_simulation = Simulation()
```

This will define a simulation with the following parameters

- Distance Resolution: 1 nanometer
- Time Resolution: 10^(-8) nanosecond or 10^(-17) nanoseconds

These parameters/simulation properties are set keeping in mind
that the simulation will be using light of visible wavelength and
interacting with object of order 10 nanometer.

### Set Resolution
Changes the resolution of the simulation spaces and redefined it.
