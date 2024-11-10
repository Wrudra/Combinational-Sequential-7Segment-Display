# 7-Segment-Display-Circuit-DL2-31D230S12

## Project Overview
This repository contains the design and implementation details of a combinational and sequential circuit to display the string "DL2-31D230S12" using a 7-segment display. The project leverages concepts from digital logic design, employing both combinational and sequential circuit components to achieve the desired display output.

## Table of Contents
1. [Introduction](#introduction)
2. [Combinational Circuit Design](#combinational-circuit-design)
3. [Sequential Circuit Design](#sequential-circuit-design)
4. [Simulations](#simulations)
5. [Conclusion](#conclusion)

## Introduction
The goal of this project is to design and implement a circuit capable of displaying "DL2-31D230S12" on a 7-segment display. The circuit design includes:
- **Combinational Part**: To handle static segments of the string.
- **Sequential Part**: To manage the dynamic or timed display transitions.

This project was developed as part of the Digital Logic Design course (CSE231L.8) at North South University.

## Combinational Circuit Design
The combinational part of the design includes:
- **Truth Tables**: Mapping of inputs to outputs for each character.
- **Canonical SOP and POS Forms**: Logical expressions derived from the truth table to implement the display logic.
- **K-Maps and Optimization**: Used to simplify logic expressions and reduce circuit complexity.

### Logic Implementation
- **NAND Gate Implementation**: Used for efficient realization of logic functions.
- **NOR Gate Implementation**: Applied where beneficial for circuit simplification.
- **Multiplexer Usage**: A 16-to-1 MUX was implemented using 8-to-1 MUXs to handle display selection.

## Sequential Circuit Design
The sequential circuit employs flip-flops to control the order and timing of character displays:
- **J-K Flip-Flop**: Chosen for its efficient use in state transitions without forbidden states.
- **D and T Flip-Flops**: Analyzed but found less optimal in terms of gate complexity and resource usage.
- **State Transitions**: Detailed using truth tables and K-maps for accurate simulation.

### Key Points
- **J-K Flip-Flop Optimization**: Selected for its reduced gate count and reliable performance.
- **Clock and Timing Mechanism**: Managed using flip-flops and a 555 timer IC.

## Simulations
Simulations were conducted using Logisim, showing accurate transitions and character displays:
- **Screenshot 1**: State - 0000 displaying "D".
- **Screenshot 2**: State - 1100 displaying "2".

## Conclusion
This project successfully demonstrates the use of combinational and sequential circuits to control a 7-segment display. The optimized design using J-K flip-flops ensures minimal complexity and reliable operation.

## Contributors
- Asrar Al Mohaimen Ahmed (ID: 2112324642)
- Nuzhat Tahsin (ID: 2121613642)
- Tahsinul Haque Wrudra (ID: 2131252642)
- Simon Yeamin (ID: 2132131642)
- Anindita Das Mishi (ID: 2211364642)

## Acknowledgements
- North South University, Department of Electrical & Computer Engineering
- Prof. Dr. M. A. Razzak (Azz) and Jannatul Ferdaous for their guidance.
