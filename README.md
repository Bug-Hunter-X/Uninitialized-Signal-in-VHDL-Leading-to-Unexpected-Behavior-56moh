# Uninitialized Signal in VHDL

This repository demonstrates a common error in VHDL: uninitialized signals.  Uninitialized signals can lead to unpredictable behavior and simulation results that don't reflect real-world hardware.  The example code shows how an uninitialized register can cause problems and how to fix it.

## The Problem

The provided VHDL code has an uninitialized signal `internal_reg`.  While the simulation might appear to work correctly, this is bad practice and could lead to unexpected behavior in a real implementation.

## The Solution

The solution involves explicitly initializing the signal to a known value.  Best practice is to set it to a value appropriate for the design's operation.

## How to Use

1. Clone this repository.
2. Open the files `bug.vhdl` and `bugSolution.vhdl` in a VHDL simulator or IDE.
3. Simulate both designs to observe the difference.
