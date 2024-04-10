# Multithreading  

This assignment demonstrates matrix multiplication using multithreading in Python.We need to multiply 100 random matrices of size 1000x1000 with a constant matrix of the same size using multithreading.

## Outputs
### Number of Cores: 2
### Number of Threads vs Total Time

| Num of Threads | Time Taken (seconds) |
|----------------|----------------------|
| 1              | 10.2753              |
| 2              | 9.6080               |
| 3              | 9.5644               |
| 4              | 9.6756               |
| 5              | 9.6300               |
| 6              | 9.4874               |
| 7              | 8.3563               |
| 8              | 9.2798               |
| 9              | 9.2211               |
| 10             | 8.8941               |
| 11             | 8.4360               |
| 12             | 9.1727               |
| 13             | 9.1981               |
| 14             | 8.4837               |
| 15             | 9.2542               |
| 16             | 9.0827               |


### Graph

![Number of Threads vs. Total Time](https://github.com/nishtha20k/Multithreading/blob/main/plot.png)


The graph illustrates how the total time taken for matrix multiplication decreases as the number of threads increases due to parallelism.

### CPU Usage

![CPU usgae](https://github.com/nishtha20k/Multithreading/blob/main/CPU_usage.png)

The CPU usage graph shows the utilization during the execution of the multithreading program, demonstrating the effectiveness of multithreading in leveraging CPU resources.
