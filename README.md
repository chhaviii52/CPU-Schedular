
# CPU Scheduling Simulator
A comprehensive web-based tool for visualizing and analyzing CPU scheduling algorithms in operating systems.

## Overview
The CPU Scheduling Simulator provides an interactive platform to demonstrate how different scheduling algorithms allocate processor time to processes. It offers real-time visualization through Gantt charts and calculates key performance metrics to facilitate algorithm comparison.

## Key Features
### Scheduling Algorithms
- First Come First Serve (FCFS) : Simple queue-based scheduling based on arrival order
- Shortest Job First (SJF) : Minimizes waiting time by prioritizing shorter processes
- Priority Scheduling : Executes processes based on assigned priority values
- Round Robin : Ensures fairness using time slices with configurable quantum
### Interactive Process Management

- Contextual input fields that adapt to the selected algorithm
- Drag-and-drop process reordering
### Visual Analysis Tools
- Color-coded Gantt chart visualization
- Process execution timeline
- Automatic metrics calculation
### Performance Metrics
- Average Waiting Time
- Average Turnaround Time
## Implementation
The simulator is built using standard web technologies:

- HTML5 for structure
- CSS3 for responsive styling
- Vanilla JavaScript for algorithm implementation and visualization

## File Structure


![Screenshot (51)](https://github.com/user-attachments/assets/f3db1788-8671-4707-be5e-6e1f74e6348d)

  

## Example Scenario
For a workload with three processes:

- Process A: Arrival at 0ms, Burst time of 5ms
- Process B: Arrival at 2ms, Burst time of 3ms
- Process C: Arrival at 4ms, Burst time of 1ms
The FCFS algorithm produces:

- Execution order: A → B → C
- Average Waiting Time: 2.67ms
- Average Turnaround Time: 6ms




