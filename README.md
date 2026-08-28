# Configurable Dual-Clock Asynchronous FIFO

A parameterized asynchronous FIFO for safe data transfer between independent write and read clock domains.

## Key features

- Gray-code read and write pointers
- Two-flip-flop pointer synchronizers
- Full and empty status flags
- Programmable almost-full and almost-empty watermarks
- Safe asynchronous-reset de-assertion
- Self-checking CDC stress-test environment

## Repository structure

- src: synthesizable SystemVerilog RTL
- tb: self-checking testbench
- constraints: CDC and timing constraints
- docs: design documentation and diagrams
- scripts: simulation and synthesis scripts
- logs: verification and synthesis logs
- outputs: waveforms and reports
- presentation: VELTRAXX '26 presentation

## Status

Initial repository setup in progress.
