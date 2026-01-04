# 4-Bit Synchronous Counter with State Control

**Computer Architecture & Organization Assignment**  
Course: TSN1101 | Trimester 2510 | Multimedia University

## Overview

Digital logic design implementing a 4-bit synchronous counter with dual state sequences controlled by external input. Features K-map optimization, flip-flop logic implementation, and CircuitVerse simulation.

## State Sequences

**When I = 0:**  
7 → 10 → 12 → 9 (repeat)  
Undesired states redirect to 10

**When I = 1:**  
9 → 13 → 11 → 5 (repeat)  
Undesired states redirect to 13

## Design Components

- State transition diagrams for both input cases
- Complete present-to-next state table
- K-map simplification for logic minimization
- Mixed flip-flop implementation (T, D, JK)
- Circuit simulation and validation

## Technical Implementation

**Flip-Flop Configuration:**
- TD (MSB) - T flip-flop for QD
- DC - D flip-flop for QC
- DB - D flip-flop for QB
- JA and KA (LSB) - JK flip-flop for QA

**Boolean Expressions:**
Derived through K-map optimization for minimal logic gates

## Simulation

Platform: CircuitVerse  
Result: Successfully validated both state sequences with proper invalid state handling

## Key Achievements

- Dual-mode operation with single control input
- Optimized logic using K-map simplification
- Proper handling of all 16 possible states
- Functional circuit implementation

## Technologies Used

- **Concepts:** Digital Logic Design, Sequential Circuits, State Machines
- **Tools:** K-map, CircuitVerse
- **Components:** Flip-flops (T, D, JK), Logic Gates

## Team Members

- **Eba Mohamed Abbas Ahmed** (Leader) - 242UC243BE
- Lama M. R. Siam - 242UC243B4
- Hamsa Hashim Omer - 242UC241DB
- Siti Zulaikha Binti Abdul Razif - 242UC243TL

## Course Information

**Course:** TSN1101 - Computer Architecture and Organization  
**Tutorial Section:** T21L  
**Group:** 3  
**Trimester:** 2510
