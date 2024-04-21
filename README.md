# Multi Threading Performance Analysis

## Methodology

In this project, we investigated the performance of matrix multiplication using multithreading in Python. The key steps of our methodology include:

1. **Matrix Multiplication Function**: We implemented a function to perform matrix multiplication using NumPy arrays. This function takes two parameters: the size of the matrices and the number of threads to use for parallel execution.

2. **Parallel Execution**: We utilized the `multiprocessing` module to enable parallel execution of matrix multiplication across multiple threads. By adjusting the number of threads, we explored the impact on performance and CPU utilization.

3. **Data Collection**: We collected data on the time taken for matrix multiplication and the CPU usage for different numbers of threads.

4. **Visualization**: We visualized the performance results using line plots to demonstrate the relationship between the number of threads, time taken for computation, and CPU usage.

## Result Table

The performance summary table below provides a concise overview of the results obtained from our experiments:

![Result Table 4](https://github.com/harshitstark13/Multi-Threading/assets/95651978/0dd56644-910c-442d-977b-981b209a0e2a)

## Result Graphs

### Time Taken vs Number of Threads

![Visualize Time Taken vs Number of Threads 1](https://github.com/harshitstark13/Multi-Threading/assets/95651978/96489fcf-a90d-4c50-b3b6-11bc43a9897b)

This graph illustrates the relationship between the number of threads and the time taken for matrix multiplication. As the number of threads increases, the time taken for computation decreases, indicating improved parallel processing efficiency.

### CPU Usage vs Number of Threads

![Visualize CPU Usage vs Number of Threads 2](https://github.com/harshitstark13/Multi-Threading/assets/95651978/00101d8c-6bbd-46e6-a392-7fb1a865f323)


This graph depicts the CPU usage as a function of the number of threads. As expected, higher thread counts lead to increased CPU utilization due to parallel execution of matrix multiplication tasks.

### Performance of 8 Threads in Parallel

![Visualizing Performance of 8 Threads in Parallel 3](https://github.com/harshitstark13/Multi-Threading/assets/95651978/7fc5780a-efce-460f-a53d-2457dbe6db4d)

This set of graphs displays the performance metrics for each individual thread when running in parallel. Each subplot represents the performance of a single thread, showcasing the variability in execution time and CPU usage across different threads.
