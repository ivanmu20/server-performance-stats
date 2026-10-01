# Server Performance Stats

A simple Bash script that analyzes basic performance statistics on a Linux server.

This project was created to practice Linux commands, Bash scripting, and basic server monitoring.

## Features

The script displays:

- Total CPU usage
- Memory usage (used, free, and percentage)
- Disk usage (used, free, and percentage)
- Top 5 processes by CPU usage
- Top 5 processes by memory usage

## Requirements

- Linux operating system
- Bash shell
- Standard Linux utilities such as:
  - `top`
  - `free`
  - `df`
  - `ps`
  - `awk`

## How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/server-performance-stats.git
```

Enter the project directory:

```bash
cd server-performance-stats
```

Give the script execution permission:

```bash
chmod +x server-stats.sh
```

Run the script:

```bash
./server-stats.sh
```

## Example Output

```text
===== SERVER STATS =====

CPU Usage: 12.5%

Memory: Used 2.1Gi / Total 7.7Gi | Free 3.2Gi | 27.27% used

Disk: Used 15G / Total 100G | Free 85G | 15% used

===== TOP 5 CPU PROCESSES =====
...

===== TOP 5 MEMORY PROCESSES =====
...
```

## What I Learned

Through this project I practiced:

- Writing Bash scripts
- Monitoring Linux server resources
- Using Linux commands such as `top`, `free`, `df`, and `ps`
- Using `awk` to extract and process command output
- Sorting processes by CPU and memory usage
- Making Bash scripts executable with `chmod`

## Project

This project is part of the DevOps projects from roadmap.sh:

https://roadmap.sh/projects/server-stats
