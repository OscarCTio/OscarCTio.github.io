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
  - Falstad
summary: "Designed and simulated a gate-level 4-bit ALU with arithmetic, logic, comparison, and status flag operations."
---

## Overview

This project involved the design, simulation, and implementation of a 4-bit Arithmetic Logic Unit (ALU). The ALU was built at the gate level and designed to perform a variety of arithmetic, logical, and comparison operations. The purpose of the project was to apply digital logic concepts to a complete processor-style component and verify its behavior through circuit simulation and SystemVerilog implementation.

The ALU supports operations such as addition, subtraction, multiplication, division by two, bitwise XOR, comparison, and scaling. Each operation was designed using digital logic components such as full adders, full subtractors, decoders, logic gates, multiplexers, and ROM-based lookup structures. Truth tables and logic diagrams were used throughout the design process to confirm that each operation behaved correctly for all 4-bit input combinations.

## Project Features

- Designed a 4-bit gate-level ALU
- Supported arithmetic operations such as addition, subtraction, multiplication, and division by two
- Supported logical operations such as bitwise XOR
- Implemented comparison logic for evaluating whether `A < B`
- Added scaling operations such as `2 × A`
- Generated status flags for zero, overflow, carry, and borrow conditions
- Integrated multiple subcircuits into one complete ALU architecture
- Simulated the circuit using Falstad Circuit Simulator
- Translated the design into modular SystemVerilog code

## Screenshot

<div class="screenshot-gallery">

  <figure>
    <img src="/img/alu2.png" alt="Digital ALU circuit design">
    <figcaption>Gate-level ALU circuit design created and simulated in Falstad.</figcaption>
  </figure>

</div>

<style>
.screenshot-gallery {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  margin: 1.5rem auto 2.5rem auto;
  max-width: 900px;
}

.screenshot-gallery figure {
  margin: 0;
  padding: 1rem;
  background: #f8f9fa;
  border: 1px solid #dee2e6;
  border-radius: 12px;
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.07);
}

.screenshot-gallery img {
  width: 100%;
  display: block;
  border-radius: 8px;
}

.screenshot-gallery figcaption {
  margin-top: 0.75rem;
  font-size: 0.95rem;
  color: #555;
  text-align: center;
}
</style>

## My Contributions

My work focused on designing and validating the ALU’s internal logic. I helped break the system into smaller subcircuits, including arithmetic units, comparison logic, control logic, and status flag generation. Each section had to be tested individually before being integrated into the complete ALU.

I also worked on verifying the correctness of the design using truth tables, logic diagrams, and circuit simulation. This included checking edge cases such as overflow, zero outputs, carry events, and borrow conditions. After the circuit design was completed, the logic was translated into SystemVerilog modules so that the design could be represented in hardware description language form.

## What I Learned

This project helped me better understand how higher-level computer architecture components are built from basic digital logic gates. Designing the ALU at the gate level showed how operations such as addition, subtraction, comparison, and overflow detection are implemented inside a digital system.

I also learned the importance of modular design. Building each operation as a smaller subcircuit made the overall ALU easier to test, debug, and integrate. The project also strengthened my understanding of how control signals are used to select operations and how status flags provide important information about the result of a computation.

Working with both Falstad and SystemVerilog helped connect circuit-level design with hardware description language implementation. This made the project useful for understanding both the visual behavior of digital circuits and the structured design process used in HDL-based systems.

## Project Report

[View full ALU design report PDF](https://drive.google.com/file/d/1aRiCzFURgQmIcU0sWAOrj4vAuj4ZrPIs/view?usp=sharing)
