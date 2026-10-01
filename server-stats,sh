#!/bin/bash


echo "===== SERVER STATS ====="

# CPU Usage
CPU=$(top -bn1 | grep "CPU(s)" | awk '{print 100 -$8}')
echo "CPU Usage: $CPU%

# Memory Usage
free -h | awk '/^Mem:/ {
	printf "Memory: Used %s / Total %s | Free %s | %2.f%% used \n",
	$3, $2, $4, ($3/$2)*100
 ,
}


#Disk Usage
df -h / | awk 'NR==2 {
	prinf "Disk: Used %s / Total %s | Free %s | %s used \n",
	$3, $2, $4, $5
 ,
}

#Top 5 Memory Processes
echo
echo "===== TOP 5 MEMORY PROCESSES ===="
ps aux --sort=-%mem | head -n 6



