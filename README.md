# LogicCraft

A client-side digital design workbench and boolean minimization engine.

## Overview
- **Truth Table Generator:** Evaluates Boolean expressions, parses variable bindings, and outputs complete truth tables alongside canonical SOP (minterms) and POS (maxterms).
- **Karnaugh Map (K-Map):** Interactive 2, 3, and 4-variable Gray-coded matrices supporting dynamic state toggling (0, 1, Don't Care) and minimal SOP reduction.
- **Logic Gates Playground:** Live visual logic gates (AND, OR, NOT, XOR, NAND, NOR) with real-time signal state propagation.
- **Radix & Complements:** Decimal, 8-bit binary, hexadecimal, 1's complement, and 2's complement conversions.

## Architecture
- 100% Client-side execution (Zero runtime dependencies).
- Standalone single-file engine.
