# 2D Memory Controller Using Address-Line Decoder and D Flip-Flops

## Project Overview

This project is a **2D memory controller** designed and simulated in **Proteus** using address-line decoding and D flip-flop based storage elements.

The uploaded Proteus schematic shows the complete digital circuit implementation, including address-selection logic, decoder stages, D flip-flop based memory elements, logic gates, and output indicators.

## Project Objectives

- Design a 2D memory organization using digital logic.
- Use an **address-line decoder** to select the required memory location.
- Use **D flip-flops** as the basic storage elements.
- Demonstrate address-based memory selection.
- Simulate and verify the circuit in Proteus.
- Observe the selected memory outputs using indicators.

## Main Concepts

### 1. Address-Line Decoder

The decoder converts the binary address input into a unique selection signal. Only the memory location corresponding to the applied address is enabled.

### 2. D Flip-Flop

A D flip-flop stores one bit of information. Multiple D flip-flops can therefore be combined to form a memory word.

### 3. 2D Memory Organization

The memory is arranged using two-dimensional selection logic. Address decoding determines which memory section/line is selected, while the storage elements retain the data.

### 4. Read/Write Selection

The controller uses address-selection and logic circuitry to control access to the required storage elements. The Proteus schematic is the reference implementation for the project's exact connections.

## Circuit Implementation

The Proteus schematic provided for this project contains:

- Address input lines
- Decoder/address-selection circuitry
- Logic gates
- D flip-flop based storage
- Output indicators/LEDs
- Interconnections for memory selection
- Power and ground connections

> **Important:** The exact IC part numbers, pin mapping, and individual address/data widths are not assumed here because they are not clearly readable from the provided schematic image. The repository documents the demonstrated architecture without inventing component specifications.

## Software

**Proteus 8 Demonstration / Schematic Capture**

The project is intended for digital circuit simulation and verification in Proteus.

## Working Principle

1. A binary address is applied to the address inputs.
2. The address is processed by the decoder circuitry.
3. The decoder generates the corresponding selection signal.
4. The selected memory section is enabled.
5. D flip-flops provide the storage for the data bits.
6. Logic circuitry controls the required data path.
7. The selected output can be observed using the connected indicators.
8. Different address combinations can be applied to verify different memory selections.

## Simulation Verification

The circuit can be verified by applying different binary address combinations in Proteus and observing the corresponding selected output.

### Suggested Verification Table

| Address Input | Expected Observation |
|---|---|
| Address 1 | Corresponding decoded memory section selected |
| Address 2 | Corresponding decoded memory section selected |
| Address 3 | Corresponding decoded memory section selected |
| Address 4 | Corresponding decoded memory section selected |
| Other valid addresses | Corresponding decoded selection changes |

The exact address combinations and observed output states should be recorded from the user's Proteus simulation during final verification.

## Project Structure

```text
2d-memory-controller/
├── README.md
├── documentation/
│   └── system-overview.md
├── simulation/
│   └── README.md
└── .gitignore
```

## Learning Outcomes

After completing this project, the learner can:

- Understand the operation of address-line decoders.
- Explain how binary addresses select memory locations.
- Understand D flip-flop based digital storage.
- Design basic memory-selection logic.
- Understand two-dimensional memory organization.
- Build and simulate digital memory circuits in Proteus.
- Verify address decoding through simulated outputs.
- Relate combinational decoding logic with sequential storage elements.

## Future Improvements

- Add a clearly documented read/write control signal.
- Add separate data input and output buses.
- Document exact IC numbers and pin connections.
- Add a complete truth table for every address.
- Add timing/waveform verification.
- Expand the memory capacity by increasing address and data lines.
- Add a formal block diagram and annotated schematic.

## Author

**Sarabjit Kumar**  
B.Tech Electronics & Communication Engineering  
Lovely Professional University
