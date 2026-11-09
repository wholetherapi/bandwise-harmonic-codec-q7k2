# Bandwise Harmonic Codec (BHC)

This repository implements **Bandwise Harmonic Coding (BHC)**, a low-bitrate
parametric speech codec described in Research Systems Division technical report
**RSD-2025-0311** (2025).

BHC is a different artifact from the wideband restoration report titled
"Bandwise Harmonic Reconstruction for Wideband Speech Restoration" (RSD-2026-0184); this codebase does not implement that restoration
report.  The identifiers are distinct: this project is RSD-2025-0311, while
RSD-2026-0184 describes a different piece of work.

## Contents

- parametric excitation modelling for 4 kHz bandwidth speech
- bitstream packing and packet-loss concealment
- decoder reference implementation in C++

## Status

Active codec research.  Issues cover bitstream interoperability, decoder
conformance, and rate-distortion experiments.
