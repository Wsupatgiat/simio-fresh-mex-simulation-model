# Simio Fresh Mex Case Study Simulation Model
## Overview
This repository contains the simulation model developed for the [Simio Spring 2024 Fresh Mex Case Study](https://www.simio.com/academic-case-studies/simio-fresh-mex/). The model optimizes the restaurant operations to minimize labor costs by focusing on:
- **Staffing Requirements**: Number and allocations of workers.
- **Operational Strategies**: Task priorities, customer priorities, buffer sizes, etc.
## Solution
This solution for the operational strategy derived from the simulation model are as follows:
### Staffing Plan
| Shift                               | Number of Workers |
| ----------------------------------- | ----------------- |
| Morning Shift (10:00 AM - 2:00 PM)  | 5                 |
| Afternoon Shift (2:00 PM - 6:00 PM) | 3                 |
| Evening Shift (6:00 PM - 10:00 PM)  | 5                 |
#### Morning and Evening Shift Worker Allocation

| Worker | Assigned Station |
| ------ | ---------------- |
| 1      | Order            |
| 2      | Proteins         |
| 3      | Toppings         |
| 4      | Packaging        |
| 5      | Pay              |
#### Afternoon Shift Worker Allocation

| Worker | Assigned Station    |
| ------ | ------------------- |
| 1      | Order, Proteins     |
| 2      | Toppings, Packaging |
| 3      | Pay                 |
### Station Buffer Capacities

| Station     | Buffer Capacity |
| ----------- | --------------- |
| Order       | 1               |
| Proteins    | 3               |
| Toppings    | 2               |
| Packaging   | 2               |
| Payment     | 1               |
| Dining Room | 11 (Seats)      |

