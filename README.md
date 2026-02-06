# Single-Stage Pipeline Register (Valid/Ready)

This repository contains a synthesizable SystemVerilog implementation of a
single-stage pipeline register using a standard valid/ready handshake.

## Description
The module sits between an input and output interface, stores one data word,
and correctly handles backpressure without data loss or duplication.

## Features
- Standard valid/ready handshake
- Proper backpressure handling
- Clean reset to empty state
- Fully synthesizable RTL

## Files
- `rtl/pipeline_reg.sv` : RTL implementation of the pipeline register

