# Kaushal-SGA-1-CLI
# Linux System Administration Lab Assignment

## Student Information

**Name:** Kaushal Kumar Tank

---

# Overview

This assignment demonstrates the use of fundamental Linux commands for system administration, networking, environment inspection, file I/O, and storage management. Each question includes command execution, observations, and report generation.

---

# Question 1 – Environment Investigation

### Objective
Investigate the Linux user environment and gather basic system information.

### Commands Used
- `whoami`
- `groups`
- `echo $SHELL`
- `pwd`
- `ls -la`

### Files Created
- `Environment_Report.txt`
- `Explanation.txt`

### Outcome
Collected information about:
- Current user
- User groups
- Default shell
- Current working directory
- Directory contents and permissions

---

# Question 2 – Network and Link Analysis

### Objective
Analyze basic network connectivity and system links.

### Commands Used
- `ping -c 4 google.com`
- Other networking/link inspection commands provided in the lab

### Files Created
- `Link_Analysis_Report.txt`
- `Explanation.txt`

### Outcome
Verified internet connectivity, analyzed network communication, and documented observations.

---

# Question 3 – Process Investigation

### Objective
Explore running processes and process management.

### Commands Used
- `ps`
- `top`
- `pstree`
- Other process-related commands

### Files Created
- `Process_Investigation_Report.txt`
- `Explanation.txt`

### Outcome
Observed running processes, parent-child relationships, CPU usage, and process information.

---

# Question 4 – Input/Output Investigation

### Objective
Investigate Linux file descriptors, I/O redirection, and system limits.

### Commands Used
- `ls /proc/$$/fd`
- `echo`
- Output redirection (`>`)
- Error redirection (`2>`)
- `ulimit -a`

### Files Created
- `IO_Investigation_Report.txt`
- `Explanation.txt`

### Outcome
Studied:
- Standard input/output/error
- File descriptors
- Output and error redirection
- Shell resource limits

---

# Question 5 – Storage Assessment

### Objective
Analyze Linux storage devices and filesystem usage.

### Commands Used
- `lsblk`
- `df -h`
- `df -i`
- `du -sh .`
- `mount | head`

### Files Created
- `Storage_Assessment_Report.txt`
- `Explanation.txt`

### Outcome
Examined:
- Block devices
- Mounted filesystems
- Disk usage
- Inode usage
- Directory size

---

# Skills Demonstrated

- Linux Command Line
- File System Navigation
- User and Group Management
- Process Monitoring
- Networking Basics
- File Descriptors
- Input/Output Redirection
- Storage Management
- Report Documentation

---

# Project Structure

```
Linux-System-Administration-Lab/
│
├── Question1/
│   ├── Environment_Report.txt
│   └── Explanation.txt
│
├── Question2/
│   ├── Link_Analysis_Report.txt
│   └── Explanation.txt
│
├── Question3/
│   ├── Process_Investigation_Report.txt
│   └── Explanation.txt
│
├── Question4/
│   ├── IO_Investigation_Report.txt
│   └── Explanation.txt
│
├── Question5/
│   ├── Storage_Assessment_Report.txt
│   └── Explanation.txt
│
└── README.md
```

---

# Conclusion

This lab provided practical experience with essential Linux system administration commands. It covered user environment analysis, networking, process monitoring, file input/output operations, and storage management. The exercises improved understanding of Linux system utilities and command-line operations through hands-on practice.
