## Abstract

## Introduction

Besides bit-flip noise, real quantum computers experience 3 major categories of errors: phase-flip errors (dephasing), depolarizing errors (generalized gate noise), and readout errors (measurement assignment errors). 


## Methods & Experiments
### Noise Model
Build a standard Bell State circuit without errors.

Add bit-flip to bell state circuit with p_error = 0.05
- bit flip on 0 state
- bit flip on H gate (not really able to visualize)
- bit flip on bell circuit with p=0.05 - see non ideal distribution on 01, 10

Add phase flip to bell state circuit with p_error = 1 to see the changes.
(Note: need to change basis to X-basis in order to see changes before measurement)
    - see 50/50 on 01 and 10 comparing to 50/50 on 00 and 11 in ideal bell measuring on x basis

### Current Error correction 
- use X-basis to catch phase-flip noise
- use y-basis to catch complex phase errors

EC for bit flip on bell: 3-qubit bit flip code (repetition code)
- ancilla qubits, use syndrome measurement

## Results

## Summary

### References