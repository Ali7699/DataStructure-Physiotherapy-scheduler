# Physiotherapy Center Scheduler

A discrete-event simulation of a physiotherapy center built in C++ for the 
CMP S103 Data Structures & Algorithms course at Cairo University.

## Overview
Simulates patient flow across three treatment types (electro-therapy, 
ultrasound-therapy, gym exercises), managing shared resources, appointment 
scheduling, and producing end-of-simulation statistics.

## Features
- Normal and recovering patient types with different scheduling logic
- Late patient penalty system with sorted re-insertion
- Probabilistic cancellation and rescheduling events
- Interactive and silent simulation modes

## How to run
Open in Visual Studio, build, and select an input file from the Input/ folder.
Input file format is documented in the project spec.

## Tech
C++ — no STL. All data structures (stack, queue, priority queue) implemented from scratch.