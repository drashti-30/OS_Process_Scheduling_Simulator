<h1 align="center">Step-Based OS Visualizer</h1>

<p align="center">
An interactive Operating System visualization tool built using <b>HTML, CSS, and JavaScript</b> to demonstrate process scheduling, context switching, interrupts, PCB management, and CPU execution in a step-by-step manner.
</p>

## Overview

The **Step-Based OS Visualizer** is an educational web application that simulates the execution of processes inside an Operating System. Unlike traditional animations, the simulator executes **one step at a time**, allowing users to understand every stage of process scheduling and context switching.

The application visually demonstrates how the CPU selects processes from the Ready Queue, executes them, handles interrupts, performs context switching, saves process states into the Process Control Block (PCB), and updates the execution timeline using a Gantt Chart.

This project is designed to help students understand fundamental Operating System concepts through an interactive and easy-to-follow visualization.

## Features

- Step-by-step execution using the **Next Step** button
- Interactive Ready Queue visualization
- Process execution simulation
- Dynamic Gantt Chart generation
- Context Switching visualization
- Interrupt handling simulation
- User Mode and Kernel Mode switching
- Register to PCB state saving animation
- Process Control Block (PCB) visualization
- Memory state visualization
- Educational interface for Operating System concepts

## Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure of the application |
| CSS3 | Styling and layout |
| JavaScript | Simulation logic and animations |

## Operating System Concepts Covered

- Process Scheduling
- CPU Scheduling
- Ready Queue
- Process Execution
- Context Switching
- Interrupt Handling
- Process Control Block (PCB)
- Register Saving
- User Mode & Kernel Mode
- Gantt Chart Visualization

## Project Structure

```text
Step-Based-OS-Visualizer/
│
├── os_innovative.html
└── README.md
```

## How It Works

1. Click **Next Step** to begin the simulation.
2. A process is selected from the Ready Queue.
3. The CPU executes the selected process.
4. If an interrupt occurs:
   - The system switches to Kernel Mode.
   - Register values are saved into the PCB.
   - The process is moved back to the Ready Queue.
5. If no interrupt occurs, the process completes execution.
6. A Context Switch is performed before selecting the next process.
7. The Gantt Chart updates after every execution step.
8. The simulation continues until all processes are completed.

## Interface Components

### Ready Queue
Displays all processes waiting for CPU execution.

### Memory (PCB)
Shows the processes currently stored in the Process Control Block.

### Register ↔ PCB
Illustrates how CPU register values are saved into the PCB during interrupts and context switches.

### Gantt Chart
Represents the execution timeline of processes along with context switch gaps.

### Status Panel
Displays the current state of the operating system during execution.

### Mode Indicator
Shows whether the CPU is operating in **User Mode** or **Kernel Mode**.

## Running the Project

1. Download or clone the repository.

```bash
git clone https://github.com/your-username/Step-Based-OS-Visualizer.git
```

2. Open the project folder.

3. Double-click **os_innovative.html**

or

Open it using any modern web browser.

No additional software or installation is required.

## Learning Outcomes

This project demonstrates the practical implementation of:

- Process Scheduling
- CPU Scheduling Algorithms
- Context Switching
- Interrupt Handling
- Process Control Block (PCB)
- User Mode & Kernel Mode
- Gantt Chart Construction
- Interactive Process Visualization
- Frontend Development using HTML, CSS, and JavaScript

## Future Enhancements

- Multiple CPU Scheduling Algorithms (FCFS, SJF, Round Robin, Priority)
- Adjustable Time Quantum
- Process Creation and Termination
- Deadlock Visualization
- Memory Allocation Simulation
- Paging and Segmentation Visualization
- Multi-Core CPU Simulation
- Performance Metrics (Waiting Time, Turnaround Time, Response Time)

## Author

**Drashti Patel**

B.Tech Computer Science & Engineering
