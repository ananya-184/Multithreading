# Multithreading Matrix Multiplication Assignment

This assignment demonstrates matrix multiplication using multithreading in Python.

## Problem Statement

The task is to multiply 100 random matrices of size 1000x1000 with a constant matrix of the same size using multithreading.

## Multithreading Overview

Multithreading allows concurrent execution of tasks within the same process. Threads share the same memory space and can run independently, leveraging multiple CPU cores for parallel computation.

## Results

### Number of Threads vs. Total Time

| Number of Threads | Total Time (seconds) |
|-------------------|----------------------|
| 1                 | 2.126                |
| 2                 | 2.035                |
| 3                 | 2.020                |
| 4                 | 1.978                |
| 5                 | 2.052                |
| 6                 | 2.115                |
| 7                 | 2.102                |
| 8                 | 2.249                |
| 9                 | 2.719                |
| 10                | 3.271                |
| 11                | 3.611                |
| 12                | 3.756                |
| 13                | 3.762                |
| 14                | 3.782                |
| 15                | 3.802                |
| 16                | 4.056                |

### Graph

![Number of Threads vs. Total Time](https://i.postimg.cc/XJJQ6bHj/Screenshot-2024-04-09-at-9-58-26-PM.png)

The graph illustrates how the total time taken for matrix multiplication decreases as the number of threads increases due to parallelism.

### CPU Usage

![CPU usgae](https://i.imgur.com/1qnB9tR.png)

The CPU usage graph shows the utilization during the execution of the multithreading program, demonstrating the effectiveness of multithreading in leveraging CPU resources.
