# System Overview

## Architecture

The project demonstrates a 2D memory controller using two major digital building blocks:

- Address-line decoder
- D flip-flop based storage

The address decoder acts as the selection mechanism. The D flip-flops act as the storage mechanism.

## Data Flow

```text
Address Inputs
      |
      v
+------------------+
| Address Decoder  |
+------------------+
      |
      v
Memory Selection
      |
      v
+------------------+
| D Flip-Flop      |
| Storage Array    |
+------------------+
      |
      v
Output Indicators
```

## Address Decoding

A binary address is applied to the decoder. The decoder produces selection signals so that the appropriate memory section is enabled.

The decoder therefore performs the address-to-selection conversion required for memory organization.

## Storage

Each D flip-flop stores one binary value. Multiple D flip-flops form a multi-bit storage word. The complete arrangement provides the memory storage represented in the Proteus schematic.

## Simulation

The design is simulated in Proteus. Address inputs can be changed to verify that the decoder selects the appropriate memory path and that the corresponding stored/output state is observed.

## Scope

This documentation describes the architecture visible in the submitted Proteus schematic. Exact IC numbers, pin assignments, memory dimensions, and timing characteristics should be added after checking the original Proteus design file or a higher-resolution annotated schematic.
