# 6T SRAM Cell Design and Layout using Cadence Virtuoso

## Overview

This project demonstrates the complete custom VLSI design flow of a 6T SRAM cell using Cadence Virtuoso and GPDK90 technology.

## Tools Used

- Cadence Virtuoso
- Spectre Simulator
- GPDK90 Technology Library

## SRAM Sizing

| Device | Width |
|----------|----------|
| Pull-Up PMOS | 120 nm |
| Access NMOS | 120 nm |
| Pull-Down NMOS | 240 nm |

## Verification Results

### DRC

✔ 0 Errors

### LVS

✔ Netlists Matched

### Extraction

✔ Successful

## Schematic

![schematic](schematic.jpeg)

## Layout

![layout](layout.jpeg)

## DRC Result

![drc](drc_clean.jpeg)

## LVS Result

![lvs](lvs_match.jpeg)

## Extracted View

![extracted](extracted_view.jpeg)

## DC Transfer Characteristics

![vtc](vtc_curve.jpeg)

## Project Flow

Schematic → Layout → DRC → Extraction → LVS → Characterization
