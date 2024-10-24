
# NS2 Setup and Blackhole Simulation

## Overview

This repository contains the necessary files to run **NS2** simulations focused on mobile ad hoc networks and blackhole attacks and solutions. You can follow the steps below to set up NS2, visualize simulations, and explore both the blackhole attack scenario and its prevention solution.

---

## NS2 Installation Guide

To install NS2, follow the steps described in the [YouTube tutorial](https://youtu.be/tH0yrJdovWM?si=Wf9jVncsuJva619Y).

1. **Watch the video** linked above and download NS2 as shown in the tutorial.
2. **Install NS2 simulator** by following the step-by-step instructions provided in the video.

---

## Repository Structure

- **`1.mobile adhoc`** – Contains files to simulate mobile ad hoc networks (MANETs).
- **`2.blackhole`** – Simulates blackhole attacks in MANET.
- **`solution`** – Implements the solution to prevent blackhole attacks.

---

## How to Use This Repository

1. **Clone or download this repository:**
   ```bash
   git clone https://github.com/Sathish111j/BlackHole-attack-and-solution-implemtation-in-NS2
   cd BlackHole
   ```

2. **Visualize Mobile Ad Hoc Networks (MANET):**
   ```bash
   cd 1.mobile\ adhoc
   ns AODV_25.tcl
   nam AODV.nam &
   ```

3. **Run Blackhole Attack Simulation:**
   ```bash
   cd ../2.blackhole
   ns BH_AODV_25.tcl
   nam blackhole.nam &
   ```

4. **View Solution to Prevent Blackhole Attacks:**
   ```bash
   cd ../solution
   ns solution.tcl
   nam solution.nam &
   ```

---
This repository provides everything needed to set up and explore **MANET simulations**, **blackhole attacks**, and **solutions to mitigate them** using the NS2 simulator. Follow the instructions carefully to ensure a smooth setup and execution.


