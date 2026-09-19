# CPU Scheduling System

A CPU Scheduling Simulator implemented in C++ and Python that demonstrates and compares multiple CPU scheduling algorithms. The system simulates process execution, generates execution timelines, and calculates important scheduling metrics.

## Features

- Supports multiple CPU scheduling algorithms:
  - First Come First Serve (FCFS)
  - Round Robin (RR)
  - Shortest Process Next (SPN)
  - Shortest Remaining Time (SRT)
  - Highest Response Ratio Next (HRRN)
  - Feedback Queue with Quantum 1 (FB-1)
  - Feedback Queue with Increasing Quantum (FB-2i)
  - Aging
- Generates CPU execution timelines
- Calculates:
  - Process completion/finish time
  - Turnaround time
  - Normalized turnaround time
- Supports trace-based execution visualization
- Supports statistical output for scheduling analysis

## Scheduling Algorithms

| Algorithm | Type |
|-----------|------|
| FCFS | Non-preemptive |
| RR | Preemptive |
| SPN | Non-preemptive |
| SRT | Preemptive |
| HRRN | Non-preemptive |
| FB-1 | Preemptive |
| FB-2i | Preemptive |
| Aging | Preemptive |

## Input Format

The program accepts scheduling configuration followed by process information.

### General Format

```text
<operation> <algorithms> <last_instant> <process_count>
<process_name>,<arrival_time>,<service_time>
...
