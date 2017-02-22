# Fixed-Wing Glider Simulation

This repository provides an example of a non-linear fixed-wing glider simulation with Matlab Simulink and FlightGear using tables of aerodynamic coefficients computed with Tornado [[1]](#tornado)., an implementation of the [Vortex Lattice Method](https://en.wikipedia.org/wiki/Vortex_lattice_method). 

The implementation also contains scripts to find the trimmed gliding state and deduce longitudinal and lateral linear time invariant systems ([LTI](https://en.wikipedia.org/wiki/Linear_time-invariant_theory)) for this state.

## Overview

Airframe
Rudder actions
Airfoil

### Airframe

### Tornado Setup

### Simulink Models

### FlightGear

## Applications

### Non-Linear Flight Simulation

### Longitudinal and Lateral LTI of Trimmed Gliding State

## Installation and Configuration

* Adjust the paths to your FlightGear installation in `runFlightGear.bat` and `runFlightGear.m` in `ExperimentalCarrierSimulink/utilities`.
* To run `mainComputeLTI.m`, check the configuration section to make the necessary adjustments to run this script in your environment and with the desired parameters.

## Running the Simulation

1. Open in Matlab the Simulink project ExperimentalCarrierSimulink.prj. This opens:
  * Plant model
  * ExperimentalCarrier model
  * ExperimentalCarrier_longitudinal model
  * ExperimentalCarrier_lateral model
  * FlightGear

# Appendix

## Test Flight Data

Data from test flight with physical model:

* Center of gravity: 92mm from leading edge of the wing.
* Weight: fully equipped with on-board computer (Tinkerforge) and 3-cell li-po and MVVS electric motor -> 1.56 kg
* Average velocity measured with GPS: ~45km/h.

# References

[1] <a name="tornado"></a> Melin Tomas, Tornado, http://tornado.redhammer.se/.
