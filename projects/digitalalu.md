---
layout: project
type: project
image: img/alu2.png
title: "Digital ALU"
date: 2023-12-07
published: true
labels:
  - Digital Logic Design
  - SystemVerilog
summary: "Designed a digital ALU that was deployed in Falstad Circuit Simulator."
---

The Digital ALU (Arithmetic Logic Unit) project is a digital design assignment where you build, simulate, and implement a 4-bit ALU. The ALU was designed at the gate level and supports a comprehensive set of arithmetic and logical operations, including addition, subtraction (A−B and B−A), multiplication, division by two, bitwise XOR, comparison (A < B), and scaling operations such as 2×A. Each operation was carefully designed with proper handling of carry, borrow, overflow, and zero conditions, using a combination of full adders, full subtractors, decoders, logic gates, and ROM-based lookup structures where appropriate. Detailed logic diagrams and truth tables were developed to validate correctness and ensure predictable behavior across all possible 4-bit input combinations

Beyond individual operations, the major accomplishment of this project was the successful integration of all subcircuits into a single ALU architecture with shared control logic and status flags. A decoder-based control scheme was used to select operations, while dedicated logic generated condition flags (Z, V, and C) to reflect result state, overflow, and carry/borrow events. The complete design was then translated into SystemVerilog, consolidating each operation into reusable modules.

Project Report:
[View full ALU design report (PDF)](https://drive.google.com/file/d/1aRiCzFURgQmIcU0sWAOrj4vAuj4ZrPIs/view?usp=sharing)


