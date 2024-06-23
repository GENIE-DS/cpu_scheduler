

# CPU_schedular:
# Project Description:
-A CPU scheduler is an essential part of an operating system that manages process execution. It determines which process will use the CPU and for what duration, aiming to maximize resource efficiency. By employing various algorithms and policies, it balances factors such as throughput, response time, and fairness to enhance overall system performance. Essentially, the CPU scheduler functions as a traffic controller for the CPU, directing the flow of processes to ensure smooth operation.

This project is a CPU Scheduler simulator implemented using Qt. It demonstrates various CPU scheduling algorithms including FCFS (First Come First Serve), NSJF (Non-preemptive Shortest Job First), PSJF (Preemptive Shortest Job First), RR (Round Robin), and PR (Priority Algorithm).






## Features

- Input data for processes.
- Display and simulate different scheduling algorithms.
- Visual representation of the scheduling process.
- Calculate and display waiting and turnaround times.

## Prerequisites

- Qt 5.x or later
- Qt Creator

## Project Structure

- `sub_window.h`: Header file for the sub_window class.
- `sub_window.cpp`: Implementation file for the sub_window class.
- `sub_window.ui`: UI file for the sub_window class.
- `main.cpp`: Main entry point of the application.
- `main_window.h` and `main_window.cpp`: Files for the main window (to be created).

## Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GENIE-DS/cpu_scheduler.git
   cd CPU_Scheduler
