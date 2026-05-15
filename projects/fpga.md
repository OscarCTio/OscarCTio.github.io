---
layout: project
type: project
image: img/fpga2.png
title: "FPGA ALU Design"
date: 2024-11-19
published: true
labels:
  - FPGA Design
  - SystemVerilog
  - Vivado
  - Digital Logic
summary: "Designed, implemented, and tested a SystemVerilog-based arithmetic logic unit on a Digilent Basys3 FPGA board."
---

## Overview

This project focused on designing and deploying an Arithmetic Logic Unit (ALU) on a physical FPGA using the Digilent Basys3 development board. The ALU was written in SystemVerilog and synthesized using Vivado. It operates on two 4-bit inputs and supports several core arithmetic and logic operations, including addition, subtraction, bitwise OR, and bitwise AND.

The goal of the project was to move beyond simulation and verify that the hardware description could be successfully implemented on real hardware. User inputs were controlled through the Basys3 board’s onboard switches and push buttons, while outputs were displayed using the board’s LEDs. After synthesis, implementation, and bitstream generation, the design was programmed onto the FPGA and tested directly on the board.

## Project Features

- Designed a 4-bit ALU using SystemVerilog
- Implemented arithmetic operations such as addition and subtraction
- Implemented logic operations such as bitwise AND and OR
- Used switches and buttons on the Basys3 board for user input
- Displayed output values using onboard LEDs
- Synthesized, implemented, and programmed the design using Vivado
- Verified the ALU through simulation and physical hardware testing

## Basys3 Board

<div class="screenshot-gallery">

  <figure>
    <img src="/img/fpga3.jpg" alt="Basys3 FPGA board during hardware testing">
    <figcaption>Hardware testing on the Digilent Basys3 FPGA board.</figcaption>
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

This project was completed as a two-person team. I contributed to the design, integration, testing, and debugging of the ALU system. My work involved helping develop the SystemVerilog modules, checking that the ALU operations produced the correct outputs, and verifying that the design worked correctly after being deployed to the Basys3 board.

I also helped debug issues that appeared during hardware testing. This included checking input mappings, validating output behavior, and making sure that the FPGA implementation matched the expected logic from the SystemVerilog design. Working with a teammate required clear communication and careful review of each part of the design so that the final system worked as intended.

## What I Learned

This project gave me hands-on experience with the full FPGA development process, from writing HDL code to testing a working design on physical hardware. I learned how SystemVerilog modules are connected, synthesized, and translated into a real digital circuit on an FPGA.

I also gained a better understanding of the difference between software debugging and hardware debugging. Unlike normal software, FPGA designs require careful attention to signal behavior, timing, pin assignments, and physical board constraints. Testing the ALU on the Basys3 board helped reinforce how digital logic concepts are applied in real hardware.

Beyond the technical skills, this project also improved my ability to collaborate on a hardware design project. Since the system depended on multiple modules working together correctly, communication, testing, and peer review were important parts of the development process.

## Project Report

[View full FPGA report PDF](https://drive.google.com/file/d/1LhuWa4bCDADen1m-3xfEuMSkE2qni4cQ/view?usp=sharing)
