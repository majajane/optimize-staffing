# optimize-staffing
Math Modeling (Final Course Output)

## Overview
The goal of this study is to analyze the occupancy data in the e-Library and to determine the busiest period. This way, the library does not exceed its capacity and allows students to utilize available space effectively.

## Mathematical Models
- **Time Series**: Tracks hourly occupancy changes
- **Moving Average**: Smooths technique to lessen fluctuations (k = 3)
- **Rate of Change**: Identifies when occupancy rises or falls
- **Linear Programming**: Optimizes staff allocation at the e-Lib
  
## How to access the code
- Download MATLAB R2025b and Optimization Toolbox (for `linprog`)
- Open MATLAB
- Go to the downloaded files containing the CSV
- Run `optimize-staffing.m`
- Figures will automatically show up
- Results will appear in the command window

## Results Summary
	- Current peak staff: 18
	- Optimal peak staff: 11
	- Total working hours saved: 50/day (30.9% reduction)

## Files
	- `optimize-staffing.m` - main MATLAB script
	- `SEPT.csv` - September occupancy data
	- `NOV.csv` - November occupancy data
