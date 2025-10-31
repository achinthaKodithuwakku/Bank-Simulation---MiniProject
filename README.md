# Bank Queue Simulation - Performance Modeling Project

## Project Overview

This repository contains the Performance Modeling mini project with analyzing the queue system at the Commercial Bank branch in Gelioya, Sri Lanka.

## System Description

The Commercial Bank branch in Gelioya is a small banking facility serving the local community with limited resources:

- **Resources:** 1 Teller Counter, 1 ATM Machine
- **Operating Hours:** 9:00 AM - 3:00 PM (6 hours daily)
- **Service Distribution:** ~60% customers use teller, ~40% use ATM
- **Average Arrival Rate:** 1 customer every 4 minutes

## Performance Objectives

The primary goal is to optimize the queue system performance by:

1. **Minimizing Customer Wait Time** - Target: Reduce average wait time to under 5 minutes
2. **Optimizing Resource Utilization** - Target: Maintain 60-75% utilization (currently >90%)
3. **Reducing Queue Length** - Target: Average queue <2 customers, max queue <5 customers
4. **Identifying Bottlenecks** - Determine which resources create constraints
5. **Maximizing Throughput** - Increase customer service capacity by 15-20%

## Repository Contents

### 1. Deliverable_01.docx

Comprehensive document describing:

- System characteristics and stakeholders
- Performance objectives and metrics

### 2. bank_simulation_dataset.csv

Simulation dataset containing 31 customer transaction records:

- **Current Setup:** 1 Teller, 1 ATM (baseline)

**Dataset Fields:**

- `customer_id`: Unique transaction identifier
- `arrival_time_min`: Customer arrival time (minutes from opening)
- `service_type`: Teller or ATM
- `service_time_min`: Service duration
- `wait_time_min`: Queue waiting time
- `queue_length_on_arrival`: Queue size at arrival

**Last Updated:** October 31, 2025

