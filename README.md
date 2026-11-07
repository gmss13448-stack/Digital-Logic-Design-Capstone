# Digital Logic Design Capstone

This repository contains two beginner-friendly sequential-circuit designs:

1. **Two-road traffic-light controller** using a Moore finite-state machine (FSM).
2. **MOD-6 synchronous counter** with terminal-count and wrap-around logic.

## Final submission
Open `Final-Submission/Capstone-Design.pdf` for the complete design document, including state tables, K-map tables, Boolean equations, circuit block diagrams, wrap-around proof, and the Moore-vs-Mealy reflection.

## Project files
- `Traffic-Light-Controller/Circuit-Diagram.png` — traffic-light controller block diagram.
- `Mod-N-Counter/Circuit-Diagram.png` — MOD-6 counter block diagram.
- `Final-Submission/Capstone-Design.pdf` — complete capstone PDF.

## Design choices
- Traffic-light FSM: four states, encoded with two state bits.
- Counter: MOD-6, counting 000 → 001 → 010 → 011 → 100 → 101 → 000.

## Note
These are logic-design diagrams and equations for an academic capstone. A real traffic controller requires validated timing, interlocks, fail-safe behaviour, and applicable safety standards.
